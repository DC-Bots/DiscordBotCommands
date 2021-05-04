## Zeiteisenbot
---
### First steps (command description below)
- to get coursenotifications: run ``++addMe`` (description below)
- turn  coursenotifications off: run ``++deleteMe``  or ``++off``
- get tasknotifications: run ``++getTasks <-all>`` (Moodlecalender-Link needed: https://moodle.hm.edu/calendar/export.php?course=6150)


### Behavior
- 10 minutes before an event, the bot will send you a notification (if there are additional information you want to show, text me)
- everday at 8 am, the bot will send you a notification with tasks within the next 24 hours (don´t work reliable until now)
- at 12 am, the bot will send a noonreminder

### Features
- you can add addtional events (like teammeetings) -> text me
- you can add addtional tasks (like issues) -> text me

### Commands
| Common-Commands                              | Description                                                                | Parameter                                                                                                                                                                                  |
| :------------------------------------------- | :------------------------------------------------------------------------- | :----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| ++addMe<>``ICS_ZPA_URL``                     | Adds you to the userlist                                                   | ``ICS_ZPA_URL``: URL to your ICS-Feed (https://zpa.cs.hm.edu/student/) from ZPA                                                                                                            |
| ++addMe<>``ICS_ZPA_URL``<>``ICS_MOODLE_URL`` | Adds you to the userlist                                                   | ``ICS_ZPA_URL``: URL to your ICS-Feed (https://zpa.cs.hm.edu/student/) from ZPA ``ICS_MOODLE_URL``: URL to your ICS-Feed from MOODLE https://moodle.hm.edu/calendar/export.php?course=6150 |
| ++deleteMe                                   | Deletes you from the userlist                                              |                                                                                                                                                                                            |
| ++updateMoodle<>``ICS_MOODLE_URL``           | updates the ics-URL for zpa-calendar                                       | ``ICS_ZPA_URL``: URL to your ICS-Feed (https://zpa.cs.hm.edu/student/) from ZPA                                                                                                            |
| ++updateZpa<>``ICS_ZPA_URL``                 | updates the ics-URL for zpa-calendar                                       | ``ICS_MOODLE_URL``: URL to your ICS-Feed from MOODLE                                                                                                                                       |
| ++getTasks[<>full]                           | If ``ICS_MOODLE_URL`` for User is set, reply with Tasks within next 7 days | -all: Get the whole description to the tasks                                                                                                                                               |
| ++on/off                                     | Turns the notifications on or off                                          |                                                                                                                                                                                            |
| ++petTheBot                                  | Pay deep respect to the Bot                                                |                                                                                                                                                                                            |

| Admin-Commands                                                                     | Description                        |
| :--------------------------------------------------------------------------------- | :--------------------------------- |
| ++get<>users/courses/messages                                                      | return all users/courses/messages  |
| ++update<>courses<>``coursename``<>general/praktikum/vorlesung<>``key``<>``value`` | update the infos from a course     |
| ++delete<>courses<>``coursename``                                                  | deletes the course                 |
| ++delete<>courses<>``coursename``<>general/praktikum/vorlesung<>``key``            | deltes the infofield from a course |
| ++update<>messages<>``messagename``<>title/description/image/type/color<>``value`` | updates the message                |
