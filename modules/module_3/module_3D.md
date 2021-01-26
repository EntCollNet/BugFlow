# Module 3D: Label Imaging

## Module Purpose: 
This module is for imaging labels attached to specimens that can be detached from the specimen (e.g. wet, pinned, envelope, but not slide labels)

## Module Keywords: 
image, images, imaging, metadata, label data, labels, labeling, low-resolution, flat


| TaskID | Task Name | Explanations and Comments | Resources |
|--------|-----------|---------------------------|-----------|
|T1|Select and transport containers (drawers/vial racks/envelopes) to proximity of imaging station.|The workflow outlined for this module is designed for label imaging only.  However, some institutions merge label imaging with collecting event record creation by creating an accompanying skeleton collecting event/locality record immediately following T8. Such records are created in a database or spreadsheet at the time of imaging and fully populated immediately or in M4C. This facilitates bulk processing of images and associated database records, especially when using software systems such as Specify, Symbiota, EMu, or TaxonWorks that provide for importing spreadsheet data. In such cases, barcode values, determination data, collecting event data, and collecting event identifiers are pre-populated into the spreadsheet. As data from the spreadsheet are later imported into the database, specimen records can be associated with pre-existing (or newly created) collecting event records.|Institutional imaging policy|
|T2|Set aside containers with damaged specimens for conservation workflow.|Re-route specimen to conservation workflow per conservation policy, Whether to image labels before conservation depends upon the severity of the damage.|Institutional conservation policy|
|T3|Select and remove to work area (selected) specimen(s) from container.|Selected specimens are those for which label-imaging is intended.  Exemplar specimens may also be selected at this step, if subsequent exemplar imaging is intended.|Institutional digitization policy|
|T4|Remove label(s) from specimen or specimen container. Maintain the sequence of labels for pinned specimens.|Best practice is to keep labels and collection object associated in some way, such as keeping labels and specimen in the same unit tray, stage, or petri dish.  Remember, labels are often **old** and **fragile** and should be handled with care. Use of forceps greatly facilities the care in which this task can be conducted and provides stability for dry labels while reducing transfer of corrosive skin oils to labels.|Forceps for removing labels. See [SPNHC newsletter 26(2):18](http://www.spnhc.org/media/assets/September2012final.pdf)  Long forceps for removing labels from vials [Bioquip](https://www.bioquip.com/Search/DispProduct.asp?pid=4533)|
|T5|Identify unique collecting event label(s), primary data label(s), and labels for collectors, host plants, or other habitat/ecological data from representative specimens.|Generally, labels can all be broken down into four classes:<li>Collecting event label(s)</li><li>Determination label(s)</li><li>Unique Identifiers (aka Catalog Numbers) <li>Other Label(s)</li>  Arranging labels in a regular fashion according to these four categories can greatly streamline later image and label processing.|Institutional imaging policy.|
|T6|Associate the specimen catalog number and/or barcode value with the collecting event labels, if not otherwise completed.|If specimens do not have the catalog number associated during an individual specimen handling process, it happens here.  This may require creating a database record or row in a spreadsheet or database, as referenced in T1 comments and explanations. This task is usually easier for brand new, unpopulated databases.||
|T7|Arrange removed label(s) (and any additional new label(s) added during digitization activities) on stage or other apparatus.|Additional labels will include barcode or other unique identifier label and others, depending on imaging purpose, e.g. project designation, date image taken, etc... Labels should be flattened as much as possible to minimize text distortion for downstream OCR or other automated methods. Pinned specimen labels can have pin holes smoothed carefully from the other side to minimize text distortion. Transparent microscope slides can be used to hold down curled labels that have been sitting in alcohol. Watch out for labels that are on shiny paper or plastic. These labels may require additional light diffusion or stage/lens angling to avoid reflections that obscure text. |Specimen or label stage or holding apparatus.|
|T8|Record image of label(s) alongside specimen. |Adjustments may be required for specimens with text on both upper and lower surfaces of the label(s). This might entail transcribing text from lower surface to a temporary label to be included within the image then discarded, or taking one image of the labels from one side and another with the double-sided label flipped over.|For further information on imaging guidelines and standards, see [iDigBio Image File Format Guide](https://www.idigbio.org/content/idigbio-image-file-format-requirements-and-recommendations)|
|T9|Save/name image file in a standard, institutionally determined format.|A file-naming scheme that mirrors the collecting event identifier is sometimes used. Examples might include: "country code"+"state code"+"verbatim directions"+"collector name"+"date"+"serial identifier", or a subset of these. This can also be done using batch renaming using programs like Adobe Bridge, IrfanView (free), or Inselect (free). Inselect can also read QR codes and rename files based on the embedded information. |Free software: [IrfanView](https://www.irfanview.com/), [Inselect](https://naturalhistorymuseum.github.io/inselect/). Institutional file-naming protocol|
|T10|Re-associate labels in original sequence (pinned specimens), adding any additional labels created as part of the imaging process, including a unique identifier label as necessary.|Reusing the original pin-holes is a recommended best practive. The insertion of unique identifier labels might also occur during Pre-digitization curation (M1).|Institutional imaging policy  Slide glue best practice LINK HERE|
|T11|Re-insert specimen into container and container into larger container (e.g. pin into unit tray or vial into vial rack).|Repeat Steps T3-T11 until container(s) already removed from collection are finished.||
|T12|Add unique identifier into database to create one or more provisional specimen records, or directly into image metadata, as appropriate. Or, add images directly and create stub records from images that can later be transcribed.|Some institutions create provisional database records at this stage. However, this task might also be accomplished at data capture time.||
|T13|Return containers to collection and flag beginning point for next imaging session.|Returning drawers or vial racks to cabinets might occur in bulk at the end of an imaging session. It is recommended that all completed drawers, vial racks, slide boxes, cabinets, etc. get a label, sticker, or other marking that indicates all specimen labels in that unit or container were imaged. This will save a great deal of time when trying to find specimens in the collection already imaged or ones that are still in need of imaging. ||

## Essential Training: 
* Specimen and label handling
* Label discrimination
* Imaging system

## Module Metrics, Costing, and Reporting: 
* Specimens should be able to be fully transcribed and databased from *just* the images of labels and specimens
* In bulk, it is often quicker to capture a low-resolution image of labels and specimen than it is to pay someone to database and parse the same specimen. If combined with community transcription, it can be much cheaper than transcribing specimens one-by-one from the specimen itself.
* "Cost" of specimen handling should be taken into account. The less often labels and specimens are handled, the better the long term conservation of that object and the labels. 

## Outreach Opportunities: 
* T8: Images can be used for community transcription outreach efforts. E.g. [TPT Notes from Nature](https://www.zooniverse.org/projects/md68135/notes-from-nature-terrestrial-parasite-tracker) [DigiVol] (https://volunteer.ala.org.au/) [Smithsonian Digital Volunteers ] (https://transcription.si.edu/)
* T8: Images can be used for various social media campaigns highlighting interesting and unique specimens in the museum

## Exemplar Workflows: 
* TaxonWorks: [Label and low-res staged image photography workflow](https://docs.google.com/document/d/1jeB0PCmy81aiDRrIMJX-HETB8nngbZRhfd0RDLTEr9Q/edit?usp=sharing)

## Discussion:
Label imaging is often overlooked, either because it is simple, or not deemed as important as images of the specimens themselves. But label data are often just as, if not more important, than an image of the specimen. Properly documenting the label data via images can allow for decreased handling time, increased use of specimens, and opportunities for outreach. 

### [Module List](https://entcollnet.github.io/BugFlow/modules/)
### [See main page here](https://entcollnet.github.io/BugFlow/)
