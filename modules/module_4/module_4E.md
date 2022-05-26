# Module 4E: Slide 2D photo-stacked specimen imaging

## Module Purpose: 
This module shows how to create a high-resolution image of a slide-mounted specimen using focus-stacking or other high-resolution technology that creates a crisp, clear image of the specimen(s) mounted on that slide at a resolution high enough to see the majority of the deatures needed for identification. 

The workflow outlined for this module is designed for slide imaging in high resolution only. However, some institutions merge slide imaging with collecting event record creation by creating an accompanying skeleton collecting event/locality record immediately following T8. Such records are created in a database or spreadsheet at the time of imaging and fully populated immediately or in [M3B](https://github.com/EntCollNet/BugFlow/blob/master/modules/module_3/module_3B.md). This facilitates bulk processing of images and associated database records, especially when using software systems such as Specify, Symbiota, EMu, or TaxonWorks that provide for importing spreadsheet data. In such cases, barcode values, determination data, collecting event data, and collecting event identifiers are pre-populated into the spreadsheet. As data from the spreadsheet are later imported into the database, specimen records can be associated with pre-existing (or newly created) collecting event records.

## Module Keywords: 
imaging, focus-stacking, high-resolution, slides

| TaskID | Task Name | Explanations and Comments | Resources |
|--------|-----------|---------------------------|-----------|
|T1| Select and transport containers (slide boxes/slide racks/slide drawers) to proximity of imaging/scanning station.|Pick specimens to be digitized depending on project or priority.| Institutional imaging policy|
|T2| Set aside slides with damaged labels/specimens for conservation workflow. |Re-route slide to conservation workflow per conservation policy. Whether to image specimens before conservation depends upon the severity of the damage.|Institutional conservation policy|
|T3| If specimens are not catalogued, transcribed, or databased, decide on whether to do so before or after imaging. Regardless, imaged specimens should be associated with a unique identifier such as a catalog number.|Exemplar high resolution imaging can be done before or after typical databasing of a slide specimen. Generally, digitization of specimens is a different workflow than imaging specimens in high resolution, and should be thought about separately, although associating images with specimens is much easier if they already at least have an database record created with an associated unique identifier.Add unique identifiers (if needed) and a label indicating that the specimen has been imaged.|Institutional guidelines for labels.|
|T4| Select and remove (exemplar) specimens for high resolution imaging to work area from container.|Exemplar specimens may be selected here or during pre-digitization curation. Slides to be imaged may come from [Module 4FT3](https://github.com/EntCollNet/BugFlow/blob/master/modules/module_4/module_4F.md)| Institutional digitization policy|
|T5| Clean specimen in preparation for imaging.| As necessary. It is very important to make sure any dust, tiny particles, or other possible obstructions are removed as there is inherently much greater magnification of slide mounted specimens than larger pinned specimens when imaging. | Cleaning tools, Institutional guidelines.| 
|T6| Associate the catalog number barcode label with the specimen, if not already completed. |If specimens have the catalog number associated during an individual specimen handling and imaging process, it happens here.| 
|T7| Arrange specimen(s) on photographic jig.| Lighting, backlighting, positioning, and magnification of specimens is all dependent on the specimen on slide. Check if filters, such as polarization or phase contrast, are necessary to view diagnostic features.|Specimen or label stage or holding apparatus. Institutional digitization policy| 
|T8| Auto- or manually focus camera and record image of specimen(s) on slide. | Workflows in which focus stacking is used require recording multiple images at various focal points, the set of images to be stacked may be processed immediately, or in a subsequent task, depending on the imaging system used. Some institutions record independent images of dorsal, ventral, and label views, and then construct a single composite image from them.|Institutional Imaging Policy  
|T9| Repeat T8 for as many views as are necessary for the project in question.| During Module 1A it is best to decide on what views are necessary for the digitization imaging project. This typically includes dorsal, ventral, and/or close up views of specific morphological features of the specimen, but varies by taxon and project scope.|Institutional Imaging Policy
|T10| Add additional labels, including a unique identifier label, as necessary.|The addition of unique identifier labels might also occur in Pre-digitization curation, or T5. |Institutional Imaging Policy
|T11|Save/name image file in a standard, institutionally or project-specific determined format, if necessary. Best practices would use only alphanumeric identifiers and avoid putting any specific metadata like genus or species names in the file names because these data could change.|A best practice file-naming scheme would use only the number that comes form the camera, possibly concatenated using an underscore "_" with other numbers such as location in the collection or other identifier that would likely not change such as the relevant collecting event identifier. Examples might include: "camera number"_ "location in collection" or what is needed to track these in your collection. This can also be done using batch renaming using programs like Adobe Bridge, IrfanView (free), or Inselect (free). Inselect can also parse out multiple slides in one image, read QR codes, and rename files based on the embedded information. Best practice avoids spaces in image file names. Note that using examples like: "country code"+"state code"+"verbatim directions"+"collector name"+"date"+"serial identifier" can work, but note that if any of those data change, then the file name will not help to understand what is in the image or help to find images.|Institutional Imaging Policy
|T12|Re-insert specimen slide into container and container into larger container (e.g. slide into slide box).|Repeat Steps T3-T11 until container(s) already removed from collection are finished.||
|T13|Add unique identifier into database to create one or more provisional specimen records, or directly into image metadata, as appropriate. Or, add images directly and create stub records from images that can later be transcribed in house or via crowdsourcing.|Some institutions create provisional database records at this stage. However, this task might also be accomplished at data capture time.||
|T14|Return containers to collection and flag beginning point for next imaging session.|Returning slide boxes or trays to cabinets might occur in bulk at the end of an imaging session. It is recommended that all completed slide boxes, drawers, cabinets, etc. get a label, sticker, or other marking that indicates all specimen labels in that unit or container were imaged. This will save a great deal of time when trying to find specimens in the collection already imaged or ones that are still in need of imaging.||

## Essential Training: 
#### Specimen Handling   
- Slide handling  
- Specimen repair and damaged specimen handling  
- Sorting 
#### Labels
- Label discrimination 
- Label handling 
- Label data interpretation, parsing, and transcription 
- Label making and labeling standards 
- Container labels 
- Unique identifiers and barcodes 
#### Imaging
- Image processing software (including image editing)
- Imaging system
- File naming (software and standards)
- Digital Asset Management System
- Specimen cleaning
#### Digital Data Management
- General data entry (into Collections Management Software or spreadsheet)
- Darwin Core
- Dublin Core
- Localities and Georeferencing
- Data recording best practices
#### General
- General Collections Organization
- IPM protocols
- Safety
- Collection-specific historical & legacy organization system(s)
- Collection Oddities, Quirks
- Good Housekeeping
- Curatorial materials and supplies
#### Taxonomy
- Types of Types
- Taxonomic Hierarchy (including name endings)
- Nomenclature and Authorship 

## Module Metrics, Costing, and Reporting: 
Number of images per hour

## Outreach Opportunities: 
Images of slides (T6) can be used in social media. Images can be used to count specimens on a slide or derive other helpful specimen information (e.g., [Penguin Watch](https://www.zooniverse.org/projects/penguintom79/penguin-watch)), identify specimens (e.g., [Drones for Ducks](https://www.zooniverse.org/projects/rowan-aspire/drones-for-ducks?utm_source=Newsletter&utm_medium=Email&utm_campaign=announce11may2021), [Serengeti Wildebeest Count](https://www.zooniverse.org/projects/dl-j/serengeti-wildebeest-count), [Weddell Seal Count](https://www.zooniverse.org/projects/slg0808/weddell-seal-count)), or used for machine learning and computer vision ([Zooniverse example](https://www.zooniverse.org/talk/449/56113)).

## Exemplar Workflows: 
- Tutorials on photo stacking using the MacropodPro system and compound scope lenses can be found [here](https://macroscopicsolutions.com/video-tutorial-macropod-micro-kit/)   
- Video tutorial on high res images of slides using a Leica compound microscope [here](https://youtu.be/6wDZeBFj8Ho)

## Discussion:
No discussion yet. Open an issue and reference this module to start discussion. 

## Best Practices & Standards:
See BugFlow page [here](https://github.com/EntCollNet/BugFlow/tree/master/bestpractices).

### [Module List](https://entcollnet.github.io/BugFlow/modules/)
### [See main page here](https://entcollnet.github.io/BugFlow/)
