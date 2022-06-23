# GOOS BioEco portal documentation

This is the documentation for the GOOS BioEco
[portal](https://bioeco.goosocean.org/) and
[GeoNode](https://geonode.goosocean.org/). More general GeoNode
documentation is available at <https://docs.geonode.org/en/master/>. The source for this documentation is hosted at
<https://github.com/iobis/bioeco-docs>.

<p>&nbsp;</p>

## Navigating the GOOS BioEco Portal

The portal's main interface **(A)** consist of an interactive global map on which the locations of Biological and Ecosystem EOV observations can be seen. The panel on the left **(B)** shows the total number of programs currently in the portal as well as the total number of programs for specific EOVs. The results in the map can be filtered to show specific **(C)** EOVs, **(D)** EOV sub-variables and EBVs by selecting for them in the panel. Filtering can also be done according to the desired Readiness levels **(E)** of a program. Specific programs can also be filtered/ searched for by filtering for them by name **(F)** or by selecting from the list.

<p align="center; padding:30px">
  <img width="100%" height="100%" src="images/interface.png"></p>
  
<p>&nbsp;</p>

When selecting an individual program, a new panel will open containing all the available metadata for that program **(G)**, as entered and maintained by the metadata provider for that program. Clicking on <span style="color:gray;">**Zoom**</span> **(H)** will direct the interactive map to the location of where the monitoring is done, indicated on the map by red dots for individual locations or by a red polygon for areal locations.

<p align="center; padding:30px">
  <img width="80%" height="80%" src="images/demo.png">
</p>

<p>&nbsp;</p>

## How to contribute?

Contribute your program metadata or explore additional metadata of existing programs in the portal by navigating to  [GeoNode](https://geonode.goosocean.org/), where new program metadata is uploaded and existing program metadata accessed, managed and updated. This documentation and a direct link to the portal is provided on the main page of GeoNode. 
<p>&nbsp;</p>

<img src="images/homepage.png" width="100%" />
<p>&nbsp;</p>

### 1. Register your GeoNode account

If you would like to contribute a monitoring program(s) to the portal, register as a new user or metadata data provider at the top right hand corner of the GeoNode GOOS BioEco homepage. You will be prompted to provide basic details such as an email address, username and password. This personal information will be used solely for the purposes of maintaining a GeoNode account and gaining exclusive access to edit or maintain your program metadata. This information will not be used or distributed to third parties. 

<img src="images/register.png" width="100%" />
<p>&nbsp;</p>

<img src="images/dropdown_profile.png" width="60%" height="60%" style="float:right; padding:10px" />

#### User account and profile

After the details have been completed, you will be signed in and
redirected to the homepage with your username indicated on the top right
hand corner. An arrow next to the username provides a drop down menu
with basic user and account options. From the <span style="color:gray;">**Profile**</span> page, personal information and
options can be added, such as a user picture, your organisation, position, location. Interaction with other users is
possible by <span style="color:gray;">**Message User**</span> or <span style="color:gray;">**Invite Users**</span> 

<p>&nbsp;</p>

### 2. Add monitoring programs

GeoNode offers two ways in which new monitoring programs can be added, which depend on the format of the spatial information of the program:

<p>&nbsp;</p>

<img src="images/upload_new.png" width="60%" height="60%" style="float:right; padding:10px" />

#### 2.1 By uplaoding a shapefile (prefered)

If the spatial information for your program is in the format of a shapefile, navigate to the <span style="color:gray;">**Profile**</span> page. A few
options are available to upload specific data and data types. To create
and upload a new monitoring program, select <span
style="color:gray;">**Upload new layers**</span>. Alternatively, select
<span style="color:gray;">**Upload Layer**</span> from the <span
style="color:gray;">**Data**</span> drop down menu on the top toolbar.

Upload your shapefiles by dragging and dropping them to the upload area,
or upload them from your device by using the <span
style="color:gray;">**Choose Files**</span> option. Uploaded files should not exceed a maximum combined size of 100 MB.

Select the correct charset option for your documents and click <span
style="color:gray;">**Upload files**</span>.

The permissions panel can be used to set permissions for other GeoNode
users to view, download and edit your uploaded data.

The default options for viewing and downloading data is set as <span
style="color:gray;">**Everyone**</span>, meaning any GeoNode user. In order to protect your data, specific users or groups must be
specified to be able to change metadata, or edit and manage your data.
If no user/ group is specified, the default for these functions will
remain with the owner user only. 

The upload status will be visible at
the top of the Upload page along with a time stamp of when the layer was
created and the progress. Once the upload is complete, click on the
<span style="color:gray;">**Name**</span> of the layer, which will be
identical to the name of the files uploaded. The newly created layer and spatial metadata can be viewed by navigating to your layer and selecting <span style="color:gray;">**Metadata detail**</span>. 

<p align="center">
  <img width="60%" height="50%" src="images/upload_comp.png">
</p>
<p>&nbsp;</p>

#### 2.2 By creating an empty layer and using the GeoNode map tool

Alternatively, without a shapefile, navigate to the <span style="color:gray;">**Profile**</span> page. A few
options are available to upload specific data and data types. To create
and upload a new monitoring program, select <span
style="color:gray;">**Create a new layer**</span>. Alternatively, select
<span style="color:gray;">**Create Layer**</span> from the <span
style="color:gray;">**Data**</span> drop down menu on the top toolbar.

Provide the name of your monitoring program as <span style="color:gray;">**Layer name**</span> and <span style="color:gray;">**Layer title**</span>. Choose the preferred <span style="color:gray;">**Geometry type**</span> for the spatial data and click <span style="color:gray;">**Create**</span>.An empty layer has now been created to which you can add your spatial data. Navigate to <span style="color:gray;">**Editing tools**</span> and select <span style="color:gray;">**Edit data**</span> under <span style="color:gray;">**Layer**</span> which will open the map tool in GeoNode.

<p align="center">
  <img width="80%" height="80%" src="images/newmap.png">
</p>
<p>&nbsp;</p>

Begin by adding an attribute number in the space provided at **(A)** and select the <span style="color:gray;">**Edit mode**</span>. Select <span style="color:gray;">**Add New feature**</span> followed by <span style="color:gray;">**Draw feature**</span>. Using the mouse, navigate on the map and indicate the location. Alternatively, search for a specific location by name or enter your coordinates at the top right hand corner marked **(B)**. The coordinates of the mouse location can also be viewed by clicking on the mouse icon at the bottom right hand corner marked **(C)**. Save your selected location. 

<img src="images/mapfeature.png" width="100%" />


### 3. Editing program metadata

Registered users have exclusive access to edit and update the metadata of their assigned program. Regular updates of program metadata is essential to keep the BioEco portal current and representing the true current state and status of ocean observation. In order to do so, we encourage on our metadata providers to keep their program layer up to date as the program develops and progresses. 

By selecting <span style="color:gray;">**Editing Tools**</span> on the
right hand panel, the spatial- and metadata layer can be edited, removed or updated.  

Only the signed-in owner of a program and admin have access to edit the metadata of a program. If the editing tools are not available to the owner, it is likely due to the default setting of admin as owner. In this case, please contact admin at s.van-der-wal@unesco.org / helpdesk@obis.org to have the ownership changed and gain access to the editing tools.     

To edit, or add to the spatial layer select <span style="color:gray;">**Edit data**</span> under <span style="color:gray;">**Layer**</span>. Select <span style="color:gray;">**Advanced Edit**</span> under <span
style="color:gray;">**Metadata**</span> to provide necessary information
about the uploaded program. 

<p align="center">
  <img width="70%" height="70%" src="images/edit_layer.png">
</p>
<p>&nbsp;</p>

#### 3.1 Updating program spatial metadata

Newly contributed programs' spatial metadata should be kept up to date. Equally, existing programs that lack spatial metadata should not the following recommendations.

**Option 1:** In order to avoid frustrating errors when updating program spatial data on GeoNode, carefully consider the format and name of the file(s) you would like to upload. The file name, the name of the layer within the file, and the geometry type used in the file, have to be identical to that of the existing file that is being replaced. 

**Option 2:** Before updating the file, download the layer from GeoNode by selecting <span style="color:gray;">**Download Layer**</span>. The layer data can be downloaded in various formats under <span style="color:gray;">**Pick your download format**</span>, either as the complete original dataset or onyl spatial files. Make the changes to the downloaded files on your device and finally re-upload the file. 

**Option 3:** If all else fails, delete the existing layer and create a new layer all together. This option might be a bit more time consuming as it will require providng all the program metadata once again, but will ensure that there are no issues with file types.

**Option 4:** For layers with geometry type *LineString*, which might be more complicated to transform and will cause issues if the updated files do not have the same geometry type. In these cases, the geometry would most likely need to be changed in the database. If this is the case with your layer and you experience difficulty uploading updated files, please get in touch with admin either by sending an email to p.provoost@unesco.org / s.van-der-wal@unesco.org / or helpdesk@obis.org, or create an issue [here](https://github.com/iobis/bioeco-geonode/issues). 
<p>&nbsp;</p>

<img src="images/fields.png" width="50%" height="50%" style="float:left" />

#### 3.2 Program

Provide a <span style="color:gray;">**Title**</span> and an <span style="color:gray;">**Abstract**</span> with a short introduction to/ basic info on the monitoring program. The <span style="color:gray;">**Owner**</span> will be indicated as the metadata provider that uploaded the metadata indicated either by their email address or username. <span style="color:gray;">**Edition**</span> refers to the version of the cited resource, which could be useful when frequent updates to the metadata are made. 

The field for <span style="color:gray;">**DOI**</span> will be completed by admin and should be left open. <span style="color:gray;">**Maintenance frequency**</span> refer to the intervals in which data is collected/ observations are made. Choose from the drop-down selection. Note, for observations made continuously, select option 'sub-daily' and for once-off observations, select the option 'opportunistically/ highly irregular intervals'. A space is provided for <span style="color:gray;">**Free-text Keywords**</span> that are useful for user filtering options. Select the applicable <span style="color:gray;">**Regions**</span> where the monitoring is done, please refrain from selecting <span style="color:gray;">**Global**</span> as the region and provide more specific regions.

<p>&nbsp;</p>

#### 3.3 Data accessibility

Provide the <span style="color:gray;">**Licence**</span> licence applicable to the data/ metadata of the program. Choose from the drop-down selection. More info on creative commons licence types and descriptions can be found [here](https://creativecommons.org/licenses/). 

<span style="color:gray;">**temporal extent start**</span> and <span style="color:gray;">**temporal extent end**</span> indicate the dates at which the program was implemented or started, and when it ended, in the format dd.mm.yyyy. If it is currently still active, leave the field empty or provide a future date if the program is planned to end at a specific date in the future. 

The fields <span style="color:gray;">**Metadata uploaded preserve**</span>, <span style="color:gray;">**Featured**</span> and <span style="color:gray;">**Is Published**</span> will be completed by admin and can be left empty.

Provide a URL or link to the main <span style="color:gray;">**Project website**</span> of the monitoring project, a link to <span style="color:gray;">**SOPs**</span> used and/ or <span style="color:gray;">**Outputs**</span>, where available. 

Please indicate whether or not the program data is published on the OBIS database under <span style="color:gray;">**In OBIS**</span> and indicate if the data provider/ project managers are <span style="color:gray;">**Interested in publishing to OBIS**</span>. 

Indicate the funder/s of the monitoring program under <span style="color:gray;">**Funding**</span> and specify the <span style="color:gray;">**Funding sector **</span> of the funder/s by choosing from the drop-down selection. 

An email address for the <span style="color:gray;">**Point of contact**</span> for the responsible person providing the information is required as well as the full name of the <span style="color:gray;">**Metadata author**</span>. 

<p>&nbsp;</p>

#### 3.4 GOOS EOVs

Select all the Biology and Ecosystems Essential Ocean Variables (EOV) observed/ monitored. Choose from the drop-down selection under <span style="color:gray;">**GOOS Essential Ocean Variables (EOVs)**</span>. Multiple selection of EOV’s is possible. 

Provide the levels of readiness of <span style="color:gray;">**GOOS Readiness - Data management and information products**</span>, <span style="color:gray;">**GOOS Readiness - Coordination of observations elements**</span> and <span style="color:gray;">**GOOS Readiness - Requirement processes**</span> according to the options provided in the drop down menu.The readiness level system is the approach for evaluating new components for possible inclusion in the global ocean observing systems. For more info on the categorization and description of levels, see [A Framework for Ocean Observing](https://unesdoc.unesco.org/ark:/48223/pf0000211260) (specifically pages 8–13).

Additional measurements taken/ observations made of the main EOV (BioEco EOV sub-variables, as well as Physics, Biochemistry, and Cross-disciplinary EOVs) can be provided under <span style="color:gray;">**GOOS Essential Ocean Variable (EOV) subvariables**</span> and <span style="color:gray;">**GOOS Essential Ocean Variables (EOVs): Physics, Biochemistry, and Cross-disciplinary**</span>. Choose from the drop-down selection and add as many rows of sub-variables as needed. For information on, and descriptions of sub-variables, refer to the [GOOS specification sheet](https://www.goosocean.org/index.php?option=com_content&view=article&layout=edit&id=283&Itemid=441) of each respective EOV.

<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>
<p>&nbsp;</p>

### 4. GeoNode map tool and creating a new map

GeoNode's interactive map tool (©OpenStreetMap contributors) is a useful tool for creating maps with
new spatial data or by using data from an existing monitoring program on
GeoNode GOOS BioEco. It further enables the user to perform basic
functions such as measuring physical distances and browsing locations or
coordinates. Navigate to <span style="color:gray;">**Create a new map**</span> under
<span style="color:gray;">**Profile**</span>. Alternatively, select
<span style="color:gray;">**Create Map**</span> from the <span
style="color:gray;">**Maps**</span> drop down menu.

<img src="images/create_map.png" width="100%" />

**A.** Add <span style="color:gray;">**Layers**</span> to a map. Select
the monitoring program from which a layer should be imported onto the
map. Alternatively, see **C**.

**B.** Use the <span style="color:gray;">**Search tool**</span> to
navigate to specific locations or search for a location using
coordinates. The latter option will provide fields to input latitudinal
and longitudinal values. Click the <span
style="color:gray;">**Settings**</span> icon under <span
style="color:gray;">**Search by coordinates**</span> to select either
decimal or aeronautical coordinate input.

**C.** The <span style="color:gray;">**Options**</span> drop down menu
is used to print or save a newly created map. Select <span
style="color:gray;">**Catalog**</span> to browse and choose a monitoring
program to load onto the new map. <span
style="color:gray;">**Measure**</span> distances, areas or bearings on
the map in various units by selecting the desired options. Click and
drag the computer mouse to continue drawing a line or polygon. The
resulting measurements or polygons can be exported to GeoJSON or added
as a layer by selecting the icon.

**D.** <span style="color:gray;">**Map options**</span> allow for easy
navigation and zooming on the map. <span style="color:gray;">**Query
objects on map**</span> by selecting the destination/ location icon and
clicking on the object of interest on the map.

**E.** The bottom toolbar presents the scale of the map, which can be
selected from the drop down menu or by zooming in or out on the map. The
actual coordinates of the location at which the mouse point is
positioned, is showed. In this toolbar, the preferred Coordinate
reference system (CRS) can also be selected.

### 5. Report an issue

Please report any issues regarding GOOS BioEco GeoNode [here](https://github.com/iobis/bioeco-geonode/issues). 

Issues encountered in the GOOS BioEco portal can be reported [here](https://github.com/iobis/bioeco-app/issues).  
