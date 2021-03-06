# Application Backup

A schedule defines when and on which days application backups should be created. To define new schedule use the ![](../../.gitbook/assets/icon-createschedule%20%282%29%20%281%29.jpg)

![](../../.gitbook/assets/schedules-application-backups.jpg)

Now provide properties:

![](../../.gitbook/assets/schedules-application-backups-parameters.jpg)

* `Schedule Active` - enable or disable executing schedule
* `Name` - schedule name
* `Execution Type` - choose time or interval mode
* `Start Window` - defines for how long since task start time scheduled tasks are allowed to be executed
* `Choose time of day` - for time execution mode defines when the task should be added to the queue
* `Choose time of interval start` - for interval execution mode defines when tasks should start
* `Choose time of interval end` - for interval execution mode defines when tasks should end
* `Frequency` - defines how often the task will be executed during the interval
* `Choose days` - last required parameter, select days of the week on which the task will be performed

You can also use optional parameters to further personalize the backup time or select an application backup policy if it has been previously created.

