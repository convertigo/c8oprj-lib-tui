


# c8oprj_lib_tui

This is the Planning component for the Convertigo Low Code Platform. This component will enable your apps to have a complete agenda like display and display several calendars. Each calendar will display their schedules on a day,week or month planning. You will be able to add, delete or move calendar schedules.

The Planning component will automatically persist in a FullSync database and free you from all database management.



For more technical informations : [documentation](./project.md)

- [Installation](#installation)
- [Mobile Application](#mobile-application)
    - [Pages](#pages)
        - [Sample](#sample)
    - [Shared Actions](#shared-actions)
        - [changeView](#changeview)
        - [clear](#clear)
        - [createSchedules](#createschedules)
        - [getDateRangeEnd](#getdaterangeend)
        - [getDateRangeStart](#getdaterangestart)
        - [moveNext](#movenext)
        - [movePrev](#moveprev)
        - [setCalendars](#setcalendars)
        - [setOptions](#setoptions)
        - [today](#today)
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
     c8oprj_lib_tui=https://github.com/convertigo/c8oprj-lib-tui.git:branch=main
     ```
     </td></tr>
     <tr><td>To simply use</td><td>

     ```
     c8oprj_lib_tui=https://github.com/convertigo/c8oprj-lib-tui/archive/main.zip
     ```
     </td></tr>
    </table>
3. Click the `Finish` button. This will automatically import the __c8oprj_lib_tui__ project


## Mobile Application

Describes the mobile application global properties

### Pages

#### Sample

My First Page as root page

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

**variables**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>containerId</td><td></td>
</tr>
</table>

**events**

<table>
<tr>
<th>name</th><th>comment</th>
</tr>
<tr>
<td>beforeCreateSchedule</td><td></td>
</tr>
</table>



