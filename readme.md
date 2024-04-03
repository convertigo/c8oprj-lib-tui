


# lib_TuiPlanner

This is the Planning component for the Convertigo Low Code Platform. This component will enable your apps to have a complete agenda like display and display several calendars. Each calendar will display their schedules on a day,week or month planning. You will be able to add, delete or move calendar schedules.

The Planning component will automatically persist in a FullSync database and free you from all database management.



For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Library](#mobile-library)
    - [Shared Actions](#shared-actions)
        - [changeView](#changeview)
        - [clear](#clear)
        - [createSchedules](#createschedules)
        - [deleteSchedule](#deleteschedule)
        - [getDateRangeEnd](#getdaterangeend)
        - [getDateRangeStart](#getdaterangestart)
        - [moveNext](#movenext)
        - [movePrev](#moveprev)
        - [scrollToNow](#scrolltonow)
        - [setCalendars](#setcalendars)
        - [setOptions](#setoptions)
        - [today](#today)
        - [toggleSchedules](#toggleschedules)
        - [updateSchedule](#updateschedule)
    - [Shared Components](#shared-components)
        - [tui_calendar](#tui_calendar)


## Installation

1. In your Convertigo Studio use `File->Import->Convertigo->Convertigo Project` and hit the `Next` button
2. In the dialog `Project remote URL` field, paste the text below:
   <table>
     <tr><td>Usage</td><td>Click the copy button</td></tr>
     <tr><td>To contribute</td><td>

     ```
     lib_TuiPlanner=https://github.com/convertigo/c8oprj-lib-tui.git:branch=main
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     lib_TuiPlanner=https://github.com/convertigo/c8oprj-lib-tui/archive/main.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __lib_TuiPlanner__ project


## Mobile Library

Describes the mobile application global properties

### Shared Actions

#### changeView

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>force</td><td></td>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
<tr>
<td>newViewName</td><td></td>
</tr>
</table>

#### clear

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
<tr>
<td>immediately</td><td></td>
</tr>
</table>

#### createSchedules

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
<tr>
<td>schedules</td><td>array of object</td>
</tr>
<tr>
<td>silent</td><td></td>
</tr>
</table>

#### deleteSchedule

Delete a schedule.

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>calendarId</td><td>(string) The CalendarId of the schedule to delete</td>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
<tr>
<td>scheduleId</td><td>(string) ID of schedule to delete</td>
</tr>
<tr>
<td>silent</td><td>(boolean) No auto render after creation when set true</td>
</tr>
</table>

#### getDateRangeEnd

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
</table>

#### getDateRangeStart

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
</table>

#### moveNext

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
</table>

#### movePrev

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
</table>

#### scrollToNow

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
</table>

#### setCalendars

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>calendars</td><td>Array of objects</td>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
</table>

#### setOptions

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
<tr>
<td>options</td><td></td>
</tr>
<tr>
<td>silent</td><td></td>
</tr>
</table>

#### today

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
</table>

#### toggleSchedules

Toggle schedules' visibility by calendar ID

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>calendarId</td><td>(string) The calendar id value</td>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
<tr>
<td>render</td><td>(boolean) set true then render after change visible property each models</td>
</tr>
<tr>
<td>toHide</td><td>(boolean) Set true to hide schedules</td>
</tr>
</table>

#### updateSchedule

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>calendarId</td><td></td>
</tr>
<tr>
<td>changes</td><td>object of changes</td>
</tr>
<tr>
<td>identifier</td><td></td>
</tr>
<tr>
<td>scheduleId</td><td></td>
</tr>
<tr>
<td>silent</td><td></td>
</tr>
</table>

### Shared Components

#### tui_calendar

The Calendar / Agenda component

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>calendars</td><td>Array of objects, list of calendars</td>
</tr>
<tr>
<td>containerId</td><td>This ID of the DIV where the agenda will be displayed</td>
</tr>
<tr>
<td>hourEnd</td><td>Number between 0 and 24, can limit of render hour end in daily / weekly view</td>
</tr>
<tr>
<td>hourStart</td><td>Number between 0 and 24, can limit of render hour start in daily / weekly view</td>
</tr>
<tr>
<td>locale</td><td>use for week days. For example get the locale from the navigator (fr, en, es, ...)</td>
</tr>
<tr>
<td>startDayOfWeek</td><td>Number between 0 and 7, 0 = Sunday. The start day of week in week / month view</td>
</tr>
<tr>
<td>useCreationPopup</td><td>(boolean) Whether use default creation popup or not. The default value is false.</td>
</tr>
<tr>
<td>useDetailPopup</td><td>(boolean) Whether use default detail popup or not. The default value is false.</td>
</tr>
<tr>
<td>view</td><td>'day', 'week', 'month'</td>
</tr>
<tr>
<td>workWeek</td><td>true or false, show only 5 days except for weekend</td>
</tr>
</table>

**events**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>afterRenderSchedule</td><td></td>
</tr>
<tr>
<td>beforeCreateSchedule</td><td></td>
</tr>
<tr>
<td>beforeDeleteSchedule</td><td></td>
</tr>
<tr>
<td>beforeUpdateSchedule</td><td></td>
</tr>
<tr>
<td>clickDayname</td><td></td>
</tr>
<tr>
<td>clickMore</td><td></td>
</tr>
<tr>
<td>clickSchedule</td><td></td>
</tr>
<tr>
<td>clickTimezonesCollapseBtn</td><td></td>
</tr>
</table>



