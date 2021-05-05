# Module 4I: Wet Soup Low-res Imaging 

## Module Purpose: 
This module will look at imaging workflow for bulk entomology samples (referred to as 'wet insect soups').
Wet insect soups are bulk samples of insects collected at a single location over a period time. Collecting methods vary but include pitfall, malaise, litter etc. Such soups are often collected as part of a study of a particular taxonomic group and/or the insect diversity and abundance of a geographic area. Some are sorted to order, others have some specimens removed, some are totally unsorted.

## Module Keywords: 
Wet insect soup, bulk samples, malaise traps, pan traps, yellow pan, pitfall, imaging, ethanol


| TaskID | Task Name | Explanations and Comments | Resources |
|--------|-----------|---------------------------|-----------|
|T1|Affix labels to rows, cabinets, and/or drawers to facilitate progress tracking.||Specimen handling  Labeling  Container|
|T2|Move specimens from collection to imaging area |Select and transport containers (jars, racks, boxes) to proximity of imaging/scanning station.| Institutional imaging policy|
|T2|Pre-image curation tasks - clean soup - sort soup| Decide on level of cleaning to remove contaminants (ie. Lepidoptera scales.). Is ethanol dirty and need to change? Is the sample clean enough to produce reasonable images? Should you sort the raw soup or not?|Sorting  Cleaning|
|T3| Assign "eventID" to the bulk sample | Assign an [eventID](https://terms.tdwg.org/wiki/dwc:eventID) to the bulk sample (if not already?)Links between core and extension records are made using an event identifier (eventID) data element in the database.| [sampling-event extension of the Darwin Core standard]( https://github.com/gbif/ipt/wiki/BestPracticesSamplingEventData) |
|T4|Attach label(s) to subsamples|Add labels & unique identifiers to any subsamples. Re-organise any storage for subsamples||
|T5|Define outcome of image|Decide on any characteristics of soup that may determine workflow of capturing images ie. image all large specimens soups with larger lens vs smaller specimen sized soups with different lens.||
|T6|Remove soup sample from container.|Spoon, tip, or pipette soup sample out of vials or jar into stage, tray, petri dish, etc ... for holding the soup and ethanol.| Specimen handling|
|T7|Add metadata label to soup for imaging|Add any information to be captured with the image to a label that will be imaged alongside the soup itself. This aids in further image tagging. Examples include: project name, photographer, date photographed, location in collection, etc ...||
|T8|Arrange soup for imaging| Place soup labels and scale bar and/or color calibration card in image. As much as possible, separate individual specimens so that as many are visible as possible. Best practices is to always place labels and calibration standards in the same designated place. |Imaging system  Link to color calibration cards  |
|T9|Capture image| Take photo of soup sample. Make sure lighting artifacts do not obscure specimens or metadata. A glass slide can be used to hold soup labels in a flat position so that they are not affected by lighting artifacts, sepcially if they have "curled" while stored in ethanol. ||
|T10|Save/name image file| Save image in a standard, institutionally or project-specific determined format, if necessary. Best practices would use only alphanumeric identifiers and avoid putting any specific metadata like genus or species names in the file names because these data could change. A best practice file-naming scheme would use only the number that comes form the camera, possibly concatenated using an underscore "`_`" with other numbers such as location in the collection or other identifier that would likely not change such as the relevant collecting event identifier. Examples might include: "camera number"`_` "location in collection" or what is needed to track these in your collection. This can also be done using batch renaming using programs like Adobe Bridge, IrfanView (free), or Inselect (free). Inselect can also parse out multiple slides in one image, read QR codes, and rename files based on the embedded information. Best practice avoids spaces in image file names. Note that using examples like: "country code"+"state code"+"verbatim directions"+"collector name"+"date"+"serial identifier" can work, but note that if any of those data change, then the file name will not help to understand what is in the image or help to find images.|Free software: [IrfanView](https://www.irfanview.com/), [Inselect](https://naturalhistorymuseum.github.io/inselect/). Institutional file-naming protocol|
|T11|Re-assemble soup sample into container|Spoon, pipette, or funnel soup sample back into vials or jar. Include soup sample labels, potentially including an "imaged" label. ||
|T12|Re-insert jar/vial into container and container into larger container (e.g. vial into vial rack).|Repeat Steps T2-T11 until container(s) already removed from collection are finished.||
|T13|Return containers to collection and flag beginning point for next imaging session.|Returning slide boxes or trays to cabinets might occur in bulk at the end of an imaging session. It is recommended that all completed slide boxes, drawers, cabinets, etc. get a label, sticker, or other marking that indicates all specimen labels in that unit or container were imaged. This will save a great deal of time when trying to find specimens in the collection already imaged or ones that are still in need of imaging.||
|T14|Add unique identifier into database to create one or more provisional specimen records, or directly into image metadata, as appropriate. Or, add images directly and create stub records from images that can later be transcribed in house or via crowdsourcing.|Some institutions create provisional database records at this stage. However, this task might also be accomplished at data capture time.||
|T15|Update data of record as specimens are later removed or requested.|Potentially re-image soups as specimens are requested on loan or identified.|

## Essential Training: 
•	Handling of wet specimens
•	Specimen and label handling
•	Imaging system
•	Add more, there are lots here


## Module Metrics, Costing, and Reporting: 
Collection Management costings:

Imaging of soups is potentially resource hungry activity which can impact significantly on collection management practices. There are a number of issues that should be considered before proceeding with an imaging program regardless of how big or small such a program may be. The collection management overheads of imaging raw soups makes it impractical but not impossible.
Each collection will have its own resource limitations and priorities for collection management which will determine how they approach imaging soups, if at all.
Handling of soups pre and post imaging are the most time-consuming steps. However, both have considerable scope for fine tuning to make them more efficient within the boundaries set by collection management priorities. 
Where resources allow, sorting soups to ordinal level before imaging has significant benefits for both collection management and image capture and management. Nevertheless, imaging of raw soups is still feasible and worth doing.


## Outreach Opportunities: 
Soups represent a largely untapped resource for ecological and taxanomic studies because they are generally only accessed by taxonomic specialists who visit an institution. By imaging the contents of these soups, and any future plans to make them available on the web with appropriate tools, will enable taxonomic researchers to access a searchable library of tagged insect images.
Online volunteers can identify ordinal diversity and abundance and clip out and tag images of individual specimens for inclusion in a tagged image based search engine for taxon discovery (see publication, Automated Image Analysis on Insect Soups https://doi.org/10.1109/DICTA.2016.7797010). One such site for outreach opportunities using crowdsourcing is: https://insectsoup.australian.museum/


## Exemplar Workflows: 
Examplar workflow of post-processing of images to tag, sort, classify insects (an automated algorithm for insect soup image segmentation and measurements) : Automated Image Analysis on Insect Soups https://doi.org/10.1109/DICTA.2016.7797010

Examplar workflow on using Inselect desktop software for placing bounding boxes around each insect in an image and exporting each image crop to its own JPG file. Inselect SYNTHESYS3 and iDigBio joint workshop (naturalhistorymuseum.github.io) https://naturalhistorymuseum.github.io/inselect-SPNHC2016/worksheet.html#worked-example-1---insect-soup

## Discussion:
No discussion yet. Open an issue and reference this module to start discussion. 

### [Module List](https://entcollnet.github.io/BugFlow/modules/)
### [See main page here](https://entcollnet.github.io/BugFlow/)
