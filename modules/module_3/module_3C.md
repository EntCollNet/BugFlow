# Module 3C: Label data parsing

## Module Purpose: 
This module is for taking data from a verbatim transcribed state into "parsed" label data, where individual text strings from verbatim label data are "parsed" into useful data concepts such as collector, date, locality, determiner, etc ...

## Module Keywords: 
labels, determination, collecting event, organization, locality, transcription


| TaskID | Task Name | Explanations and Comments | Resources |
|--------|-----------|---------------------------|-----------|
|T1|Retreive label data. This can be a block of verbatim text transcribed from a label, an image of label data, or a specimen with label data itself.|This workflow is designed to create a set of collecting event records representative of the collection and for subsequent use when entering specimen data records.| Links to resources  Links to workflows  Links to controlled vocabularies|
|T2|Start database.|||
|T3|Select a specimen with a unique set of collecting event label(s). Check the database to make sure this label has not already been parsed.|||
|T4|Construct a collecting event name for the unique collecting event with data from the label following a standardized naming convention.|Collecting event identifiers should be standardized for the collection. Examples might include: <country code>+<state code>+<verbatim directions>+<collectorname>+<date>+<serial identifier>, or a subset of these.|In general, collecting event names represent verbatim label data.|
|T5|Search database and network for existing instance of the collecting event referenced in T4.|||
|T6|If an existing collecting event is found in the local database, skip to end.|||
|T7|If an existing collecting event is found within the network, import the collecting event into the local database; skip to end.|Some software includes a duplicate check facility to search for related records across the network.||
|T8|Create record for the new collecting event/locality.|Institutions that create images of labels (M2C) might incorporate that process here [Module 3D](https://github.com/EntCollNet/BugFlow/blob/master/modules/module_3/module_3D.md)  If institutional protocols incorporate georeferencing as part of collecting event/locality record creation, technicians might search for locality data using Geolocate, Google Maps, fuzzy gazetteers, other GIS-related tools, etc. Data to enter include (but may not be limited to):  <li>latitude</li><li>longitude</li><li>higher geography</li><li>finite (atomized) geography as available</li><li>interpolated geography and/or related data from field notebooks, collection logs, etc.</li><li>verbatim description of site</li>  Some institutions also create specimen records during this process, usually storing them in a spreadsheet containing one row for each specimen, each associated with a collecting event and populated with:  <li>barcode</li><li>catalog number</li><li>collecting event identifier</li><li>determination data</li><li>determiner</li><li>date</li><li>sex</li><li>collection code</li><li>preparation type</li>| [MPM Georeferencing in EMu](https://github.com/EntCollNet/BugFlow/blob/master/workflows/MPM_GeoLocate_101_DRAFT.pdf); [UM georeferencing in Specify](https://github.com/EntCollNet/BugFlow/blob/master/workflows/UM%20-%20Georeferencing%20Specimens%20in%20Specify%20-%2022%20Oct%202019.pdf); [TPT data entry in EMu](https://github.com/EntCollNet/BugFlow/blob/master/workflows/TPT-MPM-EMu-Terrestrial%20Parasites%20Data%20Entry.pdf)|
|T9|Repeat T3-T9 until all unique collecting events in the drawer have been entered.|||
|T10|Return drawer to cabinet.|||
|T11|Perform QA.|||

[NOTE THIS MODULE WAS MIGRATED NEARLY VERBATIM, BUT IS REALLY ONLY FOR TRANSCRIBING COLLETING EVENTS. NEEDS UPDATED TO INCORPORATE MORE PARSING STEPS SUCH AS DETERMINATIONS, OTHER LABELS, ETC.]

## Essential Training: 
Define metrics that can be measured to assess success of workflows using this module

## Module Metrics, Costing, and Reporting: 
Define metrics that can be measured to assess success of workflows using this module (reference specific TaskIDs).

## Outreach Opportunities: 
List outreach opportunities that arise in workflows using this module (reference specific TaskIDs).

## Exemplar Workflows: 
MPM Geolocate Georeferencing [workflow](https://github.com/EntCollNet/BugFlow/blob/master/workflows/MPM_GeoLocate_101_DRAFT.pdf).   
Terrestrial Parasite Tracker/MPM data entry in EMU [workflow](https://github.com/EntCollNet/BugFlow/blob/master/workflows/TPT-MPM-EMu-Terrestrial%20Parasites%20Data%20Entry.pdf).   
UM Georeferencing [workflow](https://github.com/EntCollNet/BugFlow/blob/master/workflows/UM%20-%20Georeferencing%20Specimens%20in%20Specify%20-%2022%20Oct%202019.pdf). 

## Discussion:
No discussion yet. Open an issue and reference this module to start discussion.

### [Module List](https://entcollnet.github.io/BugFlow/modules/)
### [See main page here](https://entcollnet.github.io/BugFlow/)
