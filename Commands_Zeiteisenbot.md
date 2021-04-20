## Zeiteisenbot

| Common-Commands        | Description | Parameter  |
| :------------- |:-------------|:-----|
| ++addMe \<ICS-ZPA-URL>   | Adds you to the userlist | \<ICS-ZPA-URL>: URL to your ICS-Feed (https://zpa.cs.hm.edu/student/) from ZPA |
| ++addMe \<ICS-ZPA-URL> \<ICS-MOODLE-URL>    | Adds you to the userlist | \<ICS-ZPA-URL>: URL to your ICS-Feed (https://zpa.cs.hm.edu/student/) from ZPA \<ICS-MOODLE-URL>: URL to your ICS-Feed from MOODLE|
| ++deleteMe      | Deletes you from the userlist      |    |
| ++updateName | updates your name according to your current discordname      |     |
| ++updateZPAURL \<ICS-ZPA-URL> | updates the ics-URL for zpa-calendar     |    \<ICS-ZPA-URL>: URL to your ICS-Feed (https://zpa.cs.hm.edu/student/) from ZPA |
| ++updateMOODLEURL \<ICS-MOODLE-URL> | updates the ics-URL for zpa-calendar     |    \<ICS-MOODLE-URL>: URL to your ICS-Feed from MOODLE |
| ++getTasks <-all>| If \<ICS-MOODLE-URL> for User is set, reply with Tasks within next 7 days      | -all: Get the whole description to the tasks   |
| ++on/off | Turns the notifications on or off     |     |
| ++petTheBot | Pay deep respect to the Bot      |     |

| Admin-Commands        | Description | 
| :------------- |:-------------|
| ++updateCourseInfo\<>(v/p<>)coursename\<>key\<>value    | update the info to the course, v for lesson, p for praktikum| 
| ++deleteCourseInfo\<>coursename\<>key      | deletes the corresponding info      |
| ++deleteCourse\<>coursename | deletes the course      | 
| ++updateMessage\<>message\<>field<>value | updates the a message    | 
| ++listCoursedata | for Debugging and Errorhandling     | 
| ++listUserdata | for Debugging and Errorhandling      | 
| ++listMessagedata | for Debugging and Errorhandling      |
