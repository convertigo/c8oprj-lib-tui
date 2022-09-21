
# ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/project_color_16x16.png?raw=true "Project") c8oprj_lib_tui

This is the Planning component for the Convertigo Low Code Platform. This component will enable your apps to have a complete agenda like display and display several calendars. Each calendar will display their schedules on a day,week or month planning. You will be able to add, delete or move calendar schedules.

The Planning component will automatically persist in a FullSync database and free you from all database management.


<details><summary><span style="color:DarkGoldenRod"><i>References</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/references/images/XsdSchemaReference_16x16.png?raw=true "ImportXsdSchemaReference") CouchDb_schema


see [documentation](http://localhost:18080/convertigo/xsd/couchdb/CouchDb.xsd)
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Connectors</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/connectors/images/sqlconnector_color_16x16.png?raw=true "SqlConnector") void

void connector, replace or don't use it

<details><summary><span style="color:DarkGoldenRod"><i>Transactions</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/transactions/images/sqltransaction_color_16x16.png?raw=true "SqlTransaction") void

does nothing
</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Mobile Application</i></span></summary><blockquote><p>


## ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/core/images/mobileapplication_color_16x16.png?raw=true "MobileApplication") Application

Describes the mobile application global properties

<details><summary><span style="color:DarkGoldenRod"><i>Pages</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/pagecomponent_color_16x16.png?raw=true "PageComponent") Sample

My First Page as root page
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Shared Actions</i></span></summary><blockquote><p>


<details><summary><b>changeView</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") changeView



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;force
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;newViewName
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>clear</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") clear



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;immediately
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>createSchedules</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") createSchedules



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;schedules
</td>
<td>
array of object
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;silent
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>getDateRangeEnd</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") getDateRangeEnd



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>getDateRangeStart</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") getDateRangeStart



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>moveNext</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") moveNext



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>movePrev</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") movePrev



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>setCalendars</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") setCalendars



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;calendars
</td>
<td>
Array of objects
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>setOptions</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") setOptions



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;options
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;silent
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>today</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") today



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>

<details><summary><b>updateSchedule</b></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uiactionstack_color_16x16.png?raw=true "UIActionStack") updateSchedule



<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;calendarId
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;changes
</td>
<td>
object of changes
</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;identifier
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;scheduleId
</td>
<td>

</td>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uistackvariable_color_16x16.png?raw=true "  alt="UIStackVariable" >&nbsp;silent
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>
</p></blockquote></details>

<details><summary><span style="color:DarkGoldenRod"><i>Shared Components</i></span></summary><blockquote><p>


### ![](https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uisharedregular_color_16x16.png?raw=true "UISharedRegularComponent") tui_calendar

The Calendar / Agenda component

<span style="color:DarkGoldenRod">Variables</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompvariable_color_16x16.png?raw=true "  alt="UICompVariable" >&nbsp;containerId
</td>
<td>

</td>
</tr>
</table>


<span style="color:DarkGoldenRod">Events</span>

<table>
<tr>
<th>
name
</th>
<th>
comment
</th>
</tr>
<tr>
<td>
<img src="https://github.com/convertigo/convertigo/blob/develop/engine/src/com/twinsoft/convertigo/beans/ngx/components/images/uicompevent_color_16x16.png?raw=true "  alt="UICompEvent" >&nbsp;beforeCreateSchedule
</td>
<td>

</td>
</tr>
</table>

</p></blockquote></details>
</p></blockquote></details>
