---
icon: alarm-exclamation
---

# Restart Timer

{% stepper %}
{% step %}
Set a task 5 mins prior to restart

1. Select Schedules in the Configuration section (left menu)
2. Click Create Schedule
{% endstep %}

{% step %}
### Setting up tasks

Once the schedule is created you will see a schedule with no tasks

1. Click "New Task"
2. Use the Action "Edit Task"
3.  For Payload use the below for a 5 min warning timer as pictured below

    <figure><img src="../../.gitbook/assets/newtask.png" alt=""><figcaption></figcaption></figure>

    ```
    LiFxUtility::messageAll(2480, "<spop><spush><color:f8c72d>SERVER RESTART IN 5 MINUTES\n<color:00ff00>GET TO A SAFE PLACE!<spop><spush>");

    ```
{% endstep %}

{% step %}
*
*

###


{% endstep %}

{% step %}
###
{% endstep %}
{% endstepper %}

