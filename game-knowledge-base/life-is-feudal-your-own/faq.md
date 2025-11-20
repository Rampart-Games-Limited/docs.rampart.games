---
icon: comment-question
---

# Faq

<details>

<summary>How do I fix performance issues ?</summary>

Try:

* Lowering player cap
* Reducing AI/creature counts
* Selecting a smaller or less intensive map
* Upgrading CPU/RAM resources
* Restarting the server regularly

</details>

<details>

<summary>Are backups available for my server?</summary>

All Servers at Rampart Come with a Backup System that you Control

* Quick and Efficient Backups
* Quick Backup Restoration!

</details>

<details>

<summary>How do i install tradepost mod?</summary>

In order to get the trading post mod up and running on your server, the server must be registered and permanently connected in the FeudalTools Server Manager using an active premium account.

#### Download the server-side mod

First you have to download the server-side mod files. You can find the download option in \
[feudal tools](https://feudal.tools/) Server Manager on each servers detail page.

Unzip the Tradepost folder in your server main directory (where the .exe is located).

#### Tradepost Mod Setup

Edit the contained config.cs file in the Tradepost folder and adjust the ServerID setting. It must match your servers ID on the Server Managers detail page for your server. There’s an example in the Tradepost Mod download dialog.

Furthermore, add this line to the end of your servers **main.cs** file:

```
exec("Tradepost/init.cs");
```

Restart the server after this.

#### Activate The Tradepost Mod

In the Server Manager’s detail page you can toggle the tradepost mod on and off for each server. **Note that it is OFF by default**. You’ll have to enable it if you are using the tradepost mod for the first time on this server. The enable/disable option is available for premium accounts only.

</details>

<details>

<summary>How do i install the Yolauncher connector?</summary>

1\) Load up and login to the page [https://yolauncher.app/](https://yolauncher.app/)

2\) Create Server by clicking the "Add Server" Button\
![](<../../.gitbook/assets/image (3) (1).png>)

3\) Once you have Entered the name you will see the below, please click the downward arrow to download the Connector.

<figure><img src="../../.gitbook/assets/image (4).png" alt=""><figcaption></figcaption></figure>

4\) Extract the zip files contents that you recently Downloaded to the mods folder Directory

* IF  YOU HAVE THE LIFX FRAMEWORK INSTALLED IT WILL LOAD AUTOMATICALLY FOR YOU.

<mark style="color:red;">PROCEED TO STEP 5</mark> \
<mark style="color:red;">If LiFx Framework is already installed</mark>\
\
\
If you do not have the Lifx Framework installed, \
\
You will need to add a new Exec command to your main.cs file which resides in the route directory.\


```
exec("mods/yolauncher/init.cs");
```

The block should now look like the below

```
function compileFiles(%pattern)
{  
   %path = filePath(%pattern);

   %saveDSO    = $Scripts::OverrideDSOPath;
   %saveIgnore = $Scripts::ignoreDSOs;
   
   $Scripts::OverrideDSOPath  = %path;
   $Scripts::ignoreDSOs       = false;
   %mainCsFile = "main.cs";//makeFullPath("main.cs");
   %localConfigFile = "config_local.cs";
   %ddctdConfigFile = "ddctd_config.cs";

   for (%file = findFirstFileMultiExpr(%pattern); %file !$= ""; %file = findNextFileMultiExpr(%pattern))
   {
      // we don't want to try and compile the primary main.cs
      if(%mainCsFile !$= %file && %localConfigFile !$= %file && %ddctdConfigFile !$= %file)      
         compile(%file, true);
   }

   $Scripts::OverrideDSOPath  = %saveDSO;
   $Scripts::ignoreDSOs       = %saveIgnore;
}

if($compileAll)
{
   echo(" --- Compiling all files ---");
   compileFiles("*.cs");
   compileFiles("*.gui");
   compileFiles("*.ts");  
   echo(" --- Exiting after compile ---");
   quit();
}
else
{
   exec("scripts/root.cs");
   exec("TTmod/init.cs"); // This is TTmod and is not mandatory
   exec("Tradepost/init.cs"); // This is Tradepost mod and is not mandatory
   exec("mods/yolauncher/init.cs");
}
```

5\) Restart or Start your server for the yolauncher app to load and create a "handshake"

* This now meens you have proven to Yolauncher you own this game server and you can now upload modpacks and set your settings\
  \
  <mark style="color:red;">**IT IS IMPORTANT TO ONLY USE ONE METHOD TO ACTIVATE THE YOLAUNCHER**</mark>\
  &#x20;                                    <mark style="color:red;">**ALLOW LIFX FRAMEWORK TO LOAD IT**</mark>\
  &#x20;                                                                   <mark style="color:red;">**OR**</mark>\
  &#x20;                          <mark style="color:red;">**MANUALLY TRIGGER IT EDITING THE MAIN.CS FILE**</mark>

</details>

<details>

<summary>Why are Wild animals on my server not moving and/or in water?</summary>

If this happens this is a result of your navmesh, to resolve this simply\


1. Turn off your server and delete the following

* NavMesh file (nm1.nmesh)
* cache Folder

These are located on your server at

```
data/navMeshes
```

2. Turn the server back on and allow the navmesh to rebuild.

This will also fix tracking issues animal foot prints not showing when you search for wild animals.

\


</details>

<details>

<summary>Where can i find mods for Life Is Feudal?</summary>

We reccomend using the website:\
[https://lifxmod.com/](https://lifxmod.com/)\
\
to download mods for installing on your game server\
\
These mods are updated frequently and give documentation on how to install the mods.\
a Discord is also available to ask questions which can be found on the LiFx website.

</details>
