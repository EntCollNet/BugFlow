# Module 4J: Image Processing

## Module Purpose: 
Image processing workflow for setting up and harmonizing edits before Z-stacking or storage.

## Module Keywords: 
image, metadata, adobe, postprocessing, editing, Z-stack, exposure, color

| TaskID | Task Name | Explanations and Comments | Resources |
|--------|-----------|---------------------------|-----------|
|T1| Transfer images from camera to immediate image processing storage.|This task varies by institution. Some institutions record images to a card within the camera, others download directly to the imaging computer or an external or network drive as images are recorded.  Transfer to the image processing storage should be periodic, at least daily.| Ample storage space with backup procedures (also see T8-T9).|
|T2|Adjust orientation and crop images, as necessary.|Images should be framed and recorded as precisely as possible to prevent the need for cropping. In cases where cropping is required, batch crop routines for processing multiple images to identical parameters are preferable. Where batch cropping is not possible due to random variation of exemplar image files, individual cropping may be required.  Institutions that use image stacking to enhance depth of field usually create stackable derivative images in jpg or tif format and apply stacking algorithms prior to adjustments in orientation or cropping. Image stacking, especially when applied only to selected images usually occurs in a distinct, batch-oriented workflow.|Image management or processing software (e.g., Photoshop, Lightroom, ImageMagick,Gimp, or similar).|
|T3|Post-process images for quality, color correction, sharpening, light levels, contrast, etc.|Post-processing should be non-destructive and parametric. For RAW image files, parametric edits are sometimes saved in sidecar files or in an image database manager (e.g., Adobe Lightroom).  See [HERE](http://dpbestflow.org/image-editing/parametric-image-editing)|Institutional policy to determine file types, etc.  For detailed image processing recommendations, see [iDigBio’s Image File Format Requirements and Recommendations](https://www.idigbio.org/sites/default/files/sites/default/files/Image_File_Format_Recommendations_and_Standards.pdf)  See chapter on file management in [GBIF’s digital imaging best practices manual](http://www.gbif.org/orc/?doc_id=2429)|
|T4|Create composite image with various views, scale, and color standard.|Some institutions use image processing software to create a composite image of two or more views (e.g., dorsal, ventral) with scale and color standard included.|E.g. ImageMagick, Photoshop|
|T5|Create database records for associated images.|A typical method for effecting this is to run locally developed cataloging or processing scripts e.g. [HERE](http://ecnweb.org/sites/default/files/12_Eastwood_2010.pdf) and [HERE](http://sourceforge.net/projects/datashot/)||
|T6|Perform quality control and quality assurance activities.|Flag quality control issues identified by the script referenced in T5 or by visual inspection of images. Record errors and report them to imaging technicians.||
|T7|Review error report and queue for reimaging as necessary.|||
|T8|Create derivatives| Subtasks involved here include:  Converting proprietary camera RAW formats (e.g. NEF, CR2, PEF,etc.) to DNG or TIFF format,  Creating JPG files from camera RAW, DNG, or TIFF,  Distributing JPG files to an image server,  Archiving DNG or unedited TIFF files in a permanent, redundant storage repository.  Some institutions also create a set of TIFF files as master, unedited files from which future on demand derivatives can be produced.  For detailed image processing recommendations, see [iDigBio’s Image File Format Requirementsand Recommendations](https://www.idigbio.org/sites/default/files/sites/default/files/Image_File_Format_Recommendations_and_Standards.pdf).  See chapter on file management in [GBIF’s digital imaging best practices manual](http://www.gbif.org/orc/?doc_id=2429).||
|T9|Upload archival and backup images|Periodic automatic archiving and backups should be scheduled at least once weekly to remote servers and preferably to a Digital Asset Management aystem (DAMs). Some institutions/DAMs delegate and rely on automated creation of derivatives (T8) to the DAM infrastructure itself.  Archival files should be converted to DNG or TIFF format.|See recommendations for archiving at [iDigBio](https://www.idigbio.org/sites/default/files/sites/default/files/Image_File_Format_Recommendations_and_Standards.pdf)|

## Essential Training: 
Define metrics that can be measured to assess success of workflows using this module

## Module Metrics, Costing, and Reporting: 
Define metrics that can be measured to assess success of workflows using this module (reference specific TaskIDs).

## Outreach Opportunities: 
List outreach opportunities that arise in workflows using this module (reference specific TaskIDs).

## Exemplar Workflows: 
List of examplar workflows organized by database type.

### [Module List](https://entcollnet.github.io/BugFlow/modules/)
### [See main page here](https://entcollnet.github.io/BugFlow/)
