# Project Server REST API Endpoints

**Source**<br>
[JavaScript library and REST reference for Project Server 2013](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712612(v=office.15))

**Base URL**<br>
`http://<sitecollection>/<site>/_api/ProjectServer`

## Calendars

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Calendars`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668937(v=office.15)) |
| POST   | [`/Calendars`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668937(v=office.15)) |
| POST   | [`/Calendars/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669411(v=office.15)) |
| GET    | [`/Calendars/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712889(v=office.15)) |
| GET    | [`/Calendars/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668564(v=office.15)) |
| POST   | [`/Calendars/remove(calendar)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668486(v=office.15)) |
| POST   | [`/Calendars/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668288(v=office.15)) |
| DELETE | [`/Calendars('calendarid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669502(v=office.15)) |
| MERGE  | [`/Calendars('calendarid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669502(v=office.15)) |
| PUT    | [`/Calendars('calendarid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669502(v=office.15)) |
| POST   | [`/Calendars('calendarid')/copyTo(name)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712906(v=office.15)) |
| POST   | [`/Calendars('calendarid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669211(v=office.15)) |

## CustomFields

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/CustomFields`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj713018(v=office.15)) |
| POST   | [`/CustomFields`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj713018(v=office.15)) |
| POST   | [`/CustomFields/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668917(v=office.15)) |
| GET    | [`/CustomFields/getByAppAlternateId(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669220(v=office.15)) |
| GET    | [`/CustomFields/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668485(v=office.15)) |
| GET    | [`/CustomFields/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668234(v=office.15)) |
| POST   | [`/CustomFields/remove(field)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668663(v=office.15)) |
| POST   | [`/CustomFields/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669728(v=office.15)) |
| DELETE | [`/CustomFields('fieldid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668163(v=office.15)) |
| MERGE  | [`/CustomFields('fieldid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668163(v=office.15)) |
| PUT    | [`/CustomFields('fieldid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668163(v=office.15)) |
| POST   | [`/CustomFields('fieldid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668345(v=office.15)) |

## EnterpriseProjectTypes

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/EnterpriseProjectTypes`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669814(v=office.15)) |
| POST   | [`/EnterpriseProjectTypes`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669814(v=office.15)) |
| POST   | [`/EnterpriseProjectTypes/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668381(v=office.15)) |
| GET    | [`/EnterpriseProjectTypes/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669813(v=office.15)) |
| GET    | [`/EnterpriseProjectTypes/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669446(v=office.15)) |
| POST   | [`/EnterpriseProjectTypes/remove(ept)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668566(v=office.15)) |
| POST   | [`/EnterpriseProjectTypes/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668794(v=office.15)) |
| DELETE | [`/EnterpriseProjectTypes('projecttypeid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669503(v=office.15)) |
| MERGE  | [`/EnterpriseProjectTypes('projecttypeid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669503(v=office.15)) |
| PUT    | [`/EnterpriseProjectTypes('projecttypeid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669503(v=office.15)) |
| POST   | [`/EnterpriseProjectTypes('projecttypeid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669026(v=office.15)) |

## EnterpriseResources

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/EnterpriseResources`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668774(v=office.15)) |
| POST   | [`/EnterpriseResources`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668774(v=office.15)) |
| POST   | [`/EnterpriseResources/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669437(v=office.15)) |
| GET    | [`/EnterpriseResources/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668046(v=office.15)) |
| GET    | [`/EnterpriseResources/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712872(v=office.15)) |
| GET    | [`/EnterpriseResources/getByUser(user)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668638(v=office.15)) |
| POST   | [`/EnterpriseResources/remove(resource)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668425(v=office.15)) |
| POST   | [`/EnterpriseResources/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668897(v=office.15)) |

### EnterpriseResources/Assignments

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/EnterpriseResources('resourceid')/Assignments`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668191(v=office.15)) |
| POST   | [`/EnterpriseResources('resourceid')/Assignments`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668191(v=office.15)) |
| POST   | [`/EnterpriseResources('resourceid')/Assignments/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668350(v=office.15)) |
| GET    | [`/EnterpriseResources('resourceid')/Assignments/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668190(v=office.15)) |
| GET    | [`/EnterpriseResources('resourceid')/Assignments/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668948(v=office.15)) |
| POST   | [`/EnterpriseResources('resourceid')/Assignments/remove(assignment)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668201(v=office.15)) |
| POST   | [`/EnterpriseResources('resourceid')/Assignments/submitAllStatusUpdates(comment)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669518(v=office.15)) |
| POST   | [`/EnterpriseResources('resourceid')/Assignments/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668625(v=office.15)) |
| DELETE | [`/EnterpriseResources('resourceid')/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669912(v=office.15)) |
| MERGE  | [`/EnterpriseResources('resourceid')/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669912(v=office.15)) |
| PUT    | [`/EnterpriseResources('resourceid')/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669912(v=office.15)) |
| POST   | [`/EnterpriseResources('resourceid')/Assignments('assignmentid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669246(v=office.15)) |
| POST   | [`/EnterpriseResources('resourceid')/Assignments('assignmentid')/submitStatusUpdates(comment)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669466(v=office.15)) |

### EnterpriseResources/Assignments/GetTimePhaseByUrl

| Method | Endpoint |
| ------ | -------- |
| POST   | [`/EnterpriseResources('resourceid')/Assignments/GetTimePhaseByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669477(v=office.15)) |

### EnterpriseResources/Assignments/Task

| Method | Endpoint |
| ------ | -------- |
| POST   | [`/EnterpriseResources('resourceid')/Assignments('assignmentid')/Task`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669682(v=office.15)) |

## Events

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Events`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669349(v=office.15)) |
| POST   | [`/Events(id)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669131(v=office.15)) |

## EventHandlers

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/EventHandlers`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668142(v=office.15)) |
| POST   | [`/EventHandlers`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668142(v=office.15)) |
| POST   | [`/EventHandlers/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669353(v=office.15)) |
| GET    | [`/EventHandlers/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669770(v=office.15)) |
| GET    | [`/EventHandlers/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668081(v=office.15)) |
| POST   | [`/EventHandlers/remove(resource)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj670040(v=office.15)) |
| POST   | [`/EventHandlers/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj713022(v=office.15)) |
| DELETE | [`/EventHandlers('handlerid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669940(v=office.15)) |
| MERGE  | [`/EventHandlers('handlerid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669940(v=office.15)) |
| PUT    | [`/EventHandlers('handlerid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669940(v=office.15)) |
| POST   | [`/EventHandlers('handlerid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669433(v=office.15)) |

## LookupTables

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/LookupTables`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669556(v=office.15)) |
| POST   | [`/LookupTables`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669556(v=office.15)) |
| POST   | [`/LookupTables/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668868(v=office.15)) |
| GET    | [`/LookupTables/getByAppAlternateId(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668782(v=office.15)) |
| GET    | [`/LookupTables/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668716(v=office.15)) |
| GET    | [`/LookupTables/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669847(v=office.15)) |
| POST   | [`/LookupTables/remove(table)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669823(v=office.15)) |
| POST   | [`/LookupTables/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668495(v=office.15)) |
| DELETE | [`/LookupTables('tableid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668743(v=office.15)) |
| MERGE  | [`/LookupTables('tableid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668743(v=office.15)) |
| PUT    | [`/LookupTables('tableid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668743(v=office.15)) |
| POST   | [`/LookupTables('tableid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712819(v=office.15)) |

### LookupTables/Entries

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/LookupTables('tableid')/Entries`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712827(v=office.15)) |
| POST   | [`/LookupTables('tableid')/Entries`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712827(v=office.15)) |
| POST   | [`/LookupTables('tableid')/Entries/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668218(v=office.15)) |
| GET    | [`/LookupTables('tableid')/Entries/getByAppAlternateId(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669081(v=office.15)) |
| GET    | [`/LookupTables('tableid')/Entries/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj670071(v=office.15)) |
| GET    | [`/LookupTables('tableid')/Entries/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669394(v=office.15)) |
| POST   | [`/LookupTables('tableid')/Entries/remove(entry)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669380(v=office.15)) |
| DELETE | /LookupTables('tableid')/Entries('entryid') |
| MERGE  | /LookupTables('tableid')/Entries('entryid') |
| PUT    | /LookupTables('tableid')/Entries('entryid') |

## Phases

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Phases`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669151(v=office.15)) |
| POST   | [`/Phases`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669151(v=office.15)) |
| POST   | [`/Phases/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669761(v=office.15)) |
| GET    | [`/Phases/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669078(v=office.15)) |
| GET    | [`/Phases/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669650(v=office.15)) |
| POST   | [`/Phases/remove(phase)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669311(v=office.15)) |
| POST   | [`/Phases/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668909(v=office.15)) |
| DELETE | [`/Phases('phaseid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668225(v=office.15)) |
| MERGE  | [`/Phases('phaseid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668225(v=office.15)) |
| PUT    | [`/Phases('phaseid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668225(v=office.15)) |
| POST   | [`/Phases('phaseid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668136(v=office.15)) |

## ProjectDetailPages

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/ProjectDetailPages`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668957(v=office.15)) |
| GET    | [`/ProjectDetailPages/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669006(v=office.15)) |
| GET    | [`/ProjectDetailPages/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668367(v=office.15)) |
| POST   | [`/ProjectDetailPages('pageid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669736(v=office.15)) |

## Projects

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669022(v=office.15)) |
| POST   | [`/Projects`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669022(v=office.15)) |
| POST   | [`/Projects/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668478(v=office.15)) |
| GET    | [`/Projects/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712972(v=office.15)) |
| GET    | [`/Projects/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668588(v=office.15)) |
| POST   | [`/Projects/remove(project)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668384(v=office.15)) |
| POST   | [`/Projects/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669202(v=office.15)) |
| POST   | [`/Projects/validate()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668243(v=office.15)) |
| GET    | [`/Projects('projectid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669228(v=office.15)) |
| DELETE | [`/Projects('projectid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669228(v=office.15)) |
| POST   | [`/Projects('projectid')/checkOut()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669573(v=office.15)) |
| POST   | [`/Projects('projectid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669283(v=office.15)) |
| POST   | [`/Projects('projectid')/submitToWorkflow()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669295(v=office.15)) |
| POST   | [`/Projects('projectid')/updateVisibilityCustomFields()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669429(v=office.15)) |

### Projects/Assignments

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/Assignments`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668279(v=office.15)) |
| GET    | [`/Projects('projectid')/Assignments/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668488(v=office.15)) |
| GET    | [`/Projects('projectid')/Assignments/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669201(v=office.15)) |
| GET    | [`/Projects('projectid')/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668069(v=office.15)) |

### Projects/Draft

| Method | Endpoint |
| ------ | -------- |
| POST   | [`/Projects('projectid')/Draft/checkIn(force)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668592(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/publish(checkIn)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668989(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669882(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/validate()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669040(v=office.15)) |

### Projects/Draft/Assignments

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/Draft/Assignments`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669398(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/Assignments`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669398(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/Assignments/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668198(v=office.15)) |
| GET    | [`/Projects('projectid')/Draft/Assignments/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668286(v=office.15)) |
| GET    | [`/Projects('projectid')/Draft/Assignments/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668914(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/Assignments/remove(assignment)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668049(v=office.15)) |
| DELETE | [`/Projects('projectid')/Draft/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668054(v=office.15)) |
| MERGE  | [`/Projects('projectid')/Draft/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668054(v=office.15)) |
| PUT    | [`/Projects('projectid')/Draft/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668054(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/Assignments('assignmentid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668184(v=office.15)) |

### Projects/Draft/ProjectResources

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/Draft/ProjectResources`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668983(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/ProjectResources`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668983(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/ProjectResources/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669968(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/ProjectResources/addEnterpriseResource(resource)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668301(v=office.15)) |
| GET    | [`/Projects('projectid')/Draft/ProjectResources/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668398(v=office.15)) |
| GET    | [`/Projects('projectid')/Draft/ProjectResources/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668426(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/ProjectResources/remove(resource)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669079(v=office.15)) |
| DELETE | [`/Projects('projectid')/Draft/ProjectResources('resourceid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668633(v=office.15)) |
| MERGE  | [`/Projects('projectid')/Draft/ProjectResources('resourceid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668633(v=office.15)) |
| PUT    | [`/Projects('projectid')/Draft/ProjectResources('resourceid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668633(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/ProjectResources('resourceid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669431(v=office.15)) |

### Projects/Draft/TaskLinks

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/Draft/TaskLinks`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668602(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/TaskLinks`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668602(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/TaskLinks/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668693(v=office.15)) |
| GET    | [`/Projects('projectid')/Draft/TaskLinks/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669234(v=office.15)) |
| GET    | [`/Projects('projectid')/Draft/TaskLinks/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668549(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/TaskLinks/remove(TaskLink)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669127(v=office.15)) |
| DELETE | [`/Projects('projectid')/Draft/TaskLinks('linkid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668034(v=office.15)) |
| MERGE  | [`/Projects('projectid')/Draft/TaskLinks('linkid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668034(v=office.15)) |
| PUT    | [`/Projects('projectid')/Draft/TaskLinks('linkid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668034(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/TaskLinks('linkid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668320(v=office.15)) |

### Projects/Draft/Tasks

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/Draft/Tasks`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668254(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/Tasks`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668254(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/Tasks/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712793(v=office.15)) |
| GET    | [`/Projects('projectid')/Draft/Tasks/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669670(v=office.15)) |
| GET    | [`/Projects('projectid')/Draft/Tasks/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669951(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/Tasks/remove(task)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669157(v=office.15)) |
| DELETE | [`/Projects('projectid')/Draft/Tasks('taskid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669340(v=office.15)) |
| MERGE  | [`/Projects('projectid')/Draft/Tasks('taskid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669340(v=office.15)) |
| PUT    | [`/Projects('projectid')/Draft/Tasks('taskid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669340(v=office.15)) |
| POST   | [`/Projects('projectid')/Draft/Tasks('taskid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668556(v=office.15)) |

### Projects/GetResourcePlanByUrl

| Method | Endpoint |
| ------ | -------- |
| DELETE | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669121(v=office.15)) |
| MERGE  | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669121(v=office.15)) |
| PUT    | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669121(v=office.15)) |
| POST   | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/deleteObject`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669978(v=office.15)) |
| POST   | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/forceCheckIn`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712945(v=office.15)) |
| POST   | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/publish`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669173(v=office.15)) |
| POST   | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/update`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668480(v=office.15)) |

### Projects/GetResourcePlanByUrl/Assignments

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669818(v=office.15)) |
| POST   | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669818(v=office.15)) |
| POST   | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669344(v=office.15)) |
| GET    | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668982(v=office.15)) |
| GET    | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669914(v=office.15)) |
| POST   | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments/remove(assignment)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669486(v=office.15)) |
| DELETE | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668626(v=office.15)) |
| MERGE  | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668626(v=office.15)) |
| PUT    | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668626(v=office.15)) |
| POST   | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')/deleteObject`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668553(v=office.15)) |

### Projects/GetResourcePlanByUrl/Assignments/Intervals

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')/Intervals`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668403(v=office.15)) |
| POST   | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')/Intervals`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668403(v=office.15)) |
| GET    | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')/Intervals/getById(id)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669248(v=office.15)) |
| GET    | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')/Intervals/getByStart(start)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669722(v=office.15)) |
| MERGE  | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')/Intervals('yyyy-MM-dd')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668371(v=office.15)) |
| PUT    | [`/Projects('projectid')/GetResourcePlanByUrl(start='yyyy-MM-dd',end='yyyy-MM-dd',scale='timescale')/Assignments('assignmentid')/Intervals('yyyy-MM-dd')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668371(v=office.15)) |

### Projects/ProjectResources

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/ProjectResources`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669633(v=office.15)) |
| GET    | [`/Projects('projectid')/ProjectResources/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668493(v=office.15)) |
| GET    | [`/Projects('projectid')/ProjectResources/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668741(v=office.15)) |
| POST   | [`/Projects('projectid')/ProjectResources('resourceid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668395(v=office.15)) |

### Projects/TaskLinks

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/TaskLinks`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668642(v=office.15)) |
| GET    | [`/Projects('projectid')/TaskLinks/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668358(v=office.15)) |
| GET    | [`/Projects('projectid')/TaskLinks/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669343(v=office.15)) |
| GET    | [`/Projects('projectid')/TaskLinks('linkid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669920(v=office.15)) |

### Projects/Tasks

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/Tasks`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668255(v=office.15)) |
| GET    | [`/Projects('projectid')/Tasks/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668860(v=office.15)) |
| GET    | [`/Projects('projectid')/Tasks/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669347(v=office.15)) |
| GET    | [`/Projects('projectid')/Tasks('taskid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668612(v=office.15)) |

### Projects/QueueJobs

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Projects('projectid')/QueueJobs`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj670013(v=office.15)) |
| GET    | [`/Projects('projectid')/QueueJobs/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668950(v=office.15)) |
| GET    | [`/Projects('projectid')/QueueJobs/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668093(v=office.15)) |
| POST   | [`/Projects('projectid')/QueueJobs('jobid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668379(v=office.15)) |
| POST   | [`/Projects('projectid')/QueueJobs('jobid')/cancel()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669270(v=office.15)) |

## Stages

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Stages`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669261(v=office.15)) |
| POST   | [`/Stages`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669261(v=office.15)) |
| POST   | [`/Stages/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj670076(v=office.15)) |
| GET    | [`/Stages/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj670011(v=office.15)) |
| GET    | [`/Stages/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668805(v=office.15)) |
| POST   | [`/Stages/remove(stage)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669369(v=office.15)) |
| POST   | [`/Stages/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668195(v=office.15)) |
| DELETE | [`/Stages('stageid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712851(v=office.15)) |
| MERGE  | [`/Stages('stageid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712851(v=office.15)) |
| PUT    | [`/Stages('stageid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712851(v=office.15)) |
| POST   | [`/Stages('stageid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712830(v=office.15)) |

### Stages/CustomFields

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Stages('stageid')/CustomFields`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668415(v=office.15)) |
| POST   | [`/Stages('stageid')/CustomFields/add(creationInfo)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj670045(v=office.15)) |
| GET    | [`/Stages('stageid')/CustomFields/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668664(v=office.15)) |
| GET    | [`/Stages('stageid')/CustomFields/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668709(v=office.15)) |
| POST   | [`/Stages('stageid')/CustomFields/remove(field)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668596(v=office.15)) |
| POST   | [`/Stages('stageid')/CustomFields('fieldid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668078(v=office.15)) |
| POST   | [`/Stages('stageid')/CustomFields('fieldid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669544(v=office.15)) |

### Stages/ProjectDetailPages

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/Stages('stageid')/ProjectDetailPages`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668817(v=office.15)) |
| POST   | [`/Stages('stageid')/ProjectDetailPages/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669412(v=office.15)) |
| GET    | [`/Stages('stageid')/ProjectDetailPages/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669876(v=office.15)) |
| GET    | [`/Stages('stageid')/ProjectDetailPages/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712787(v=office.15)) |
| POST   | [`/Stages('stageid')/ProjectDetailPages/remove(pdp)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668848(v=office.15)) |
| POST   | [`/Stages('stageid')/ProjectDetailPages('pageid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668795(v=office.15)) |
| POST   | [`/Stages('stageid')/ProjectDetailPages('pageid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669023(v=office.15)) |

## TimeSheetPeriods

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/TimeSheetPeriods`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668717(v=office.15)) |
| GET    | [`/TimeSheetPeriods/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj713031(v=office.15)) |
| GET    | [`/TimeSheetPeriods/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712823(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669287(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/createTimeSheet()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669182(v=office.15)) |

### TimeSheetPeriods/TimeSheet

| Method | Endpoint |
| ------ | -------- |
| DELETE | [`/TimeSheetPeriods('periodid')/TimeSheet`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668309(v=office.15)) |
| MERGE  | [`/TimeSheetPeriods('periodid')/TimeSheet`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668309(v=office.15)) |
| PUT    | [`/TimeSheetPeriods('periodid')/TimeSheet`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668309(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669987(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/recall()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712922(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/submit(comment)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668473(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/update()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668182(v=office.15)) |

### TimeSheetPeriods/TimeSheet/Lines

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668600(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668600(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj670035(v=office.15)) |
| GET    | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines/getByGuid(uid)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669525(v=office.15)) |
| GET    | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj712828(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines/remove(line)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668846(v=office.15)) |
| DELETE | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669242(v=office.15)) |
| MERGE  | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669242(v=office.15)) |
| PUT    | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669242(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/deleteObject()`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668489(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/submit(comment)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668563(v=office.15)) |

### TimeSheetPeriods/TimeSheet/Lines/Work

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669471(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669471(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work/add(parameters)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668382(v=office.15)) |
| GET    | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work/getById(objectId)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669408(v=office.15)) |
| GET    | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work/getByStartDate(start)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668505(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work/remove(work)`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669251(v=office.15)) |
| DELETE | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work('yyyy-MM-dd')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668895(v=office.15)) |
| MERGE  | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work('yyyy-MM-dd')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668895(v=office.15)) |
| PUT    | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work('yyyy-MM-dd')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668895(v=office.15)) |
| POST   | [`/TimeSheetPeriods('periodid')/TimeSheet/Lines('lineid')/Work('yyyy-MM-dd')/deleteObject`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668088(v=office.15)) |

## WorkflowActivities

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/WorkflowActivities`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668932(v=office.15)) |
| POST   | [`/WorkflowActivities`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668932(v=office.15)) |

## WorkflowDesigner

| Method | Endpoint |
| ------ | -------- |
| GET    | [`/WorkflowDesigner`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669514(v=office.15)) |
| GET    | [`/WorkflowDesigner/Fields`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj669897(v=office.15)) |
| GET    | [`/WorkflowDesigner/Fields/GetById('objectId')`](https://docs.microsoft.com/en-us/previous-versions/office/project-javascript-api/jj668372(v=office.15)) |