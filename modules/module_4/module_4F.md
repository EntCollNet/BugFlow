# Module 4F: Slide Label/low-res Imaging

## Module Purpose: 
Use this module to image slide labels (and usually the associated slide-mounted specimen) at high enough resolution that the labels can be transcribed and read without difficulty, and the number of specimens can be counted.  

The workflow outlined for this module is designed for label imaging only. However, some institutions merge label imaging with collecting event record creation by creating an accompanying skeleton collecting event/locality record immediately following T8. Such records are created in a database or spreadsheet at the time of imaging and fully populated immediately or in [M3B](https://github.com/EntCollNet/BugFlow/blob/master/modules/module_3/module_3B.md). This facilitates bulk processing of images and associated database records, especially when using software systems such as Specify, Symbiota, EMu, or TaxonWorks that provide for importing spreadsheet data. In such cases, barcode values, determination data, collecting event data, and collecting event identifiers are pre-populated into the spreadsheet. As data from the spreadsheet are later imported into the database, specimen records can be associated with pre-existing (or newly created) collecting event records.

## Module Keywords: 
slide, imaging, low-resolution, labels


| TaskID | Task Name | Explanations and Comments | Resources |
|--------|-----------|---------------------------|-----------|
|T1|Select and transport containers (slide boxes/racks/drawers) to proximity of imaging/scanning station.|| Institutional imaging policy|
|T2|Set aside slides with damaged labels/specimens for conservation workflow.|Ensure slides are clean and/or in good enough condition for digitization. Remember, slides and labels are often old and fragile and should be handled with care. Re-route slide to conservation workflow per conservation policy. Whether to image labels before conservation depends upon the severity of the damage. |Institutional conservation policy|
|T3|Select and remove to work area (selected) specimen slide(s) from container.| Selected specimen slides are those for which label-imaging is intended. Exemplar specimens may also be selected at this step, if subsequent exemplar imaging is intended.| Institutional digitization policy|
|T4|Identify unique collecting event label(s), primary data label(s), and labels for collectors, host plants, or other habitat/ecological data from representative specimens.|Generally, slide labels can all be broken down into three classes: <ul><li>Collecting event label(s)</li><li>Determination label(s)</li><li>Unique Identifier label (aka Catalog Numbers)</li></ul> Collecting event labels are usually located on one side of the slide, while determination labels are usually on the opposite side of the slide. Determination labels may contain both specimen and host taxonomic information, or host information may be included on the collecting event label depending on the collector. Unique identifier labels may or may not be an additional smaller label.|Institutional imaging policy|
|T5|Decide if slides can be moved/rearranged to allow for more efficient digitization, and do so, if necessary.| This varies by institution and slide box curation. For example, if all slides are well labeled and without implied curation (e.g. an inserted "determination" slide stands in for determination labels on all slides), then they can be rearranged to have all collecting event labels together, so that when they are transcribed, the same information can be repeated or gathered more quickly, or in bulk. However, if slide condition and labeling practices do not allow for this, many curators take on an "image as is, maintain current order" policy. Best practice is to maintain consistency.||
|T6|Associate/attach the specimen catalog number and/or barcode value with each slide.|If specimens do not have the catalog number associated during an individual specimen handling process, it happens here. This may require creating a database record or row in a spreadsheet or database, as referenced in Module Purpose. This task is usually easier for brand new, unpopulated databases.|Best practices page for labeling slides|
|T7|Associate/attach slide(s) with any additional new label(s) added during digitization activities on stage or other apparatus.|Additional labels will include barcode or other unique identifier label and others, depending on imaging purpose, e.g. project designation, date image taken, etc.|Specimen or label stage or holding apparatus.|
|T8|Position slide(s) on imaging station/scanner bed. Maintain the sequence of slides as in box/tray/container, if necessary (see T5)|Best practice is to use a template of some kind so that slide(s) are placed in the same position and order every time. Examples include, but are not limited to: guide tape on the workbench marking slide positions, a clear projector film with numbered spaces, or a clear three dimensional rig that can be placed on a scanner bed to hold slide(s).|[Essig Museum Slide Jig](https://www.idigbio.org/wiki/images/3/30/Scanning_Microscope_Slides_Oboyski.pdf)<br> add TCN TPT example & doc...|
|T9|Record image of label(s) alongside specimen.|Adjustments may be required for specimens with text on both upper and lower surfaces of the slide(s). This might entail transcribing text from lower surface to a temporary label to be included within the image then discarded, or taking one image of the slide labels from one side and another with the double-sided slide flipped over.|For further information on imaging guidelines and standards, see [iDigBio Image File Format Guide](https://www.idigbio.org/content/idigbio-image-file-format-requirements-and-recommendations)|
|T10|Save/name image file in a standard, institutionally or project-specific determined format, if necessary. Best practices would use only alphanumeric identifiers and avoid putting any specific metadata like genus or species names in the file names because these data could change.|A best practice file-naming scheme would use only the number that comes form the camera, possibly concatenated using an underscore "`_`" with other numbers such as location in the collection or other identifier that would likely not change such as the relevant collecting event identifier. Examples might include: "camera number"`_` "location in collection" or what is needed to track these in your collection. This can also be done using batch renaming using programs like Adobe Bridge, IrfanView (free), or Inselect (free). Inselect can also parse out multiple slides in one image, read QR codes, and rename files based on the embedded information. Best practice avoids spaces in image file names. Note that using examples like: "country code"+"state code"+"verbatim directions"+"collector name"+"date"+"serial identifier" can work, but note that if any of those data change, then the file name will not help to understand what is in the image or help to find images.|Free software: [IrfanView](https://www.irfanview.com/), [Inselect](https://naturalhistorymuseum.github.io/inselect/). Institutional file-naming protocol|
|T11|Re-insert specimen slide into container and container into larger container (e.g. slide into slide box).|Repeat Steps T3-T11 until container(s) already removed from collection are finished.||
|T12|Return containers to collection and flag beginning point for next imaging session.|Returning slide boxes or trays to cabinets might occur in bulk at the end of an imaging session. It is recommended that all completed slide boxes, drawers, cabinets, etc. get a label, sticker, or other marking that indicates all specimen labels in that unit or container were imaged. This will save a great deal of time when trying to find specimens in the collection already imaged or ones that are still in need of imaging.||
|T13|Add unique identifier into database to create one or more provisional specimen records, or directly into image metadata, as appropriate. Or, add images directly and create stub records from images that can later be transcribed in house or via crowdsourcing.|Some institutions create provisional database records at this stage. However, this task might also be accomplished at data capture time.||


## Essential Training: 
Slide and label handling  
Label discrimination  
Imaging system  
File renaming program  

## Module Metrics, Costing, and Reporting: 
Accuracy of transcribed slides  
Number of slide images created per hour  
Amount of data bulk processed vs. done in verbatim transcription  

## Outreach Opportunities: 
Images of slides (T9) can be used in social media  
Transcription of slide images can be done via crowdsourcing (e.g. Notes from Nature, Zooniverse)  

## Exemplar Workflows: 
Essig Museum Slide Scanning [Workflow](https://www.idigbio.org/wiki/images/3/30/Scanning_Microscope_Slides_Oboyski.pdf)<br>
INHS Insect Collection Slide Scanning [Workflow](https://docs.google.com/document/d/1V_gCv9W5QG3p0rpUZtvssucrJ5I5ZjtmOD3jbFOfkEk/edit?usp=sharing)  
Allan E, Livermore L, Price B, Shchedrina O, Smith V (2019) **A Novel Automated Mass Digitisation Workflow for Natural History Microscope Slides**. Biodiversity Data Journal 7: e32342. https://doi.org/10.3897/BDJ.7.e32342

## Discussion:
No discussion yet. Open an issue and reference this module to start discussion. 

### [Module List](https://entcollnet.github.io/BugFlow/modules/)
### [See main page here](https://entcollnet.github.io/BugFlow/)
