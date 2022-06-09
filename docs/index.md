# GOOS BioEco portal documentation

This is the documentation for the GOOS BioEco
[portal](https://bioeco.goosocean.org/) and
[GeoNode](https://geonode.goosocean.org/). More general GeoNode
documentation is available at <https://docs.geonode.org/en/master/>.

The source for this documentation is hosted at
<https://github.com/iobis/bioeco-docs>.

<img src="images/homepage.png" width="100%" />

## How to:

### 1. Register your GeoNode account

Register as a new user or data provider at the top right hand corner of
the GeoNode GOOS BioEco homepage. You will be prompted to complete basic
details such as an email address, username and password.

<img src="images/register.png" width="100%" />

#### User account and profile

<img src="images/dropdown_profile.png" width="60%" height="60%" style="float:right; padding:10px" />

After the details have been completed, you will be signed in and
redirected to the homepage with your username indicated on the top right
hand corner. An arrow next to the username provides a drop down menu
with basic user and account options. From the <span style="color:gray;">**Profile**</span> page, personal information and
options can be added and changed. Interaction with other users is
possible by <span style="color:gray;">**Message User**</span> or <span style="color:gray;">**Invite Users**</span> 


### 2. Add monitoring programs

<img src="images/upload_new.png" width="60%" height="60%" style="float:right; padding:10px" />

Navigate to the <span style="color:gray;">**Profile**</span> page. A few
options are available to upload specific data and data types. To create
and upload a new monitoring program, select <span
style="color:gray;">**Upload new layers**</span>. Alternatively, select
<span style="color:gray;">**Upload Layer**</span> from the <span
style="color:gray;">**Data**</span> drop down menu.

Upload your shapefiles by dragging and dropping them to the upload area,
or upload them from your device by using the <span
style="color:gray;">**Choose Files**</span> option. Uploaded files should not exceed a maximum combined size of 100 MB.

Select the correct charset option for your documents and click <span
style="color:gray;">**Upload files**</span>.

The permissions panel can be used to set permissions for other GeoNode
users to view, download and edit your uploaded data.

The default options for viewing and downloading data is set as <span
style="color:gray;">**Everyone**</span>, meaning any GeoNode user.

In order to protect your data, specific users or groups must be
specified to be able to change metadata, or edit and manage your data.
If no user/ group is specified, the default for these functions will
remain with the owner user only. The upload status will be visible at
the top of the Upload page along with a time stamp of when the layer was
created and the progress. Once the upload is complete, click on the
<span style="color:gray;">**Name**</span> of the layer, which will be
identical to the name of the files uploaded. The newly created layer and spatial metadata can be viewed by navigating to your layer and selecting <span style="color:gray;">**Metadata detail**</span>

<p align="center">
  <img width="60%" height="50%" src="images/upload_comp.png">
</p>

### 3. Editing metadata

By selecting <span style="color:gray;">**Editing Tools**</span> on the
right hand panel, the matadata, styles and the spacial data layer can be edited, removed and managed. 
Only the signed-in owner of a program and admin have access to edit the metadata of a program. If the editing tools are  not available to the owner, it is likely due to the default setting of admin as owner. In this case, please contact admin at s.van-der-wal@unesco.org / helpdesk@obis.org to have the ownership changed and gain access to the editing tools.      

To edit, or add to the spatial layer select <span style="color:gray;">**Edit data**</span> under <span style="color:gray;">**Layer**</span>. Select <span style="color:gray;">**Advanced Edit**</span> under <span
style="color:gray;">**Metadata**</span> to provide necessary information
about the uploaded program. 

<p align="center">
  <img width="70%" height="70%" src="images/edit_layer.png">
</p>

<img src="images/fields.png" width="50%" height="50%" style="float:left" />


#### Program

Provide a <span style="color:gray;">**Title**</span> and an <span style="color:gray;">**Abstract**</span> with a short introduction to/ basic info on the monitoring program. By default the <span style="color:gray;">**Owner**</span> will be indicated as the metadata provider that uploaded the metadata. <span style="color:gray;">**Edition**</span> refers to the version of the cited resource, which could be useful when frequent updates to the metadata are made. 

The field for <span style="color:gray;">**DOI**</span> will be completed by admin and should be left open. <span style="color:gray;">**Maintenance frequency**</span> refer to the intervals in which data is collected/ observations are made. Choose from the drop-down selection. Note, for observations made continuously, select option 'sub-daily' and for once-off observations, select the option 'opportunistically/ highly irregular intervals'. A space is provided for <span style="color:gray;">**Free-text Keywords**</span> that are useful for user filtering options. Select the applicable <span style="color:gray;">**Regions**</span> where the monitoring is done.


#### Data accessibility

Provide the <span style="color:gray;">**Licence**</span> licence applicable to the data/ metadata of the program. Choose from the drop-down selection. More info on creative commons licence types and descriptions can be found [here](https://creativecommons.org/licenses/). 

<span style="color:gray;">**temporal extent start**</span> and <span style="color:gray;">**temporal extent end**</span> indicate the dates at which the program was implemented or started, and when it ended, in the format dd.mm.yyyy. If it is currently still active, leave the field empty or provide a future date if the program is planned to end at a specific date in the future. 

The fields <span style="color:gray;">**Metadata uploaded preserve**</span>, <span style="color:gray;">**Featured**</span> and <span style="color:gray;">**Is Published**</span> will be completed by admin and can be left empty.


Provide a URL or link to the main <span style="color:gray;">**Project website**</span> of the monitoring project, a link to <span style="color:gray;">**SOPs**</span> used and/ or <span style="color:gray;">**Outputs**</span>, where available. 

Please indicate whether or not the program data is published on the OBIS database under <span style="color:gray;">**In OBIS**</span> and indicate if the data provider/ project managers are <span style="color:gray;">**Interested in publishing to OBIS**</span>. 

Indicate the funder/s of the monitoring program under <span style="color:gray;">**Funding**</span> and specify the <span style="color:gray;">**Funding sector **</span> of the funder/s by choosing from the drop-down selection. 

An email address for the <span style="color:gray;">**Point of contact**</span> for the responsible person providing the information is required as well as the full name of the <span style="color:gray;">**Metadata author**</span>. 


#### GOOS EOVs

Select all the Biology and Ecosystems Essential Ocean Variables (EOV) observed/ monitored. Choose from the drop-down selection under <span style="color:gray;">**GOOS Essential Ocean Variables (EOVs)**</span>. Multiple selection of EOV’s is possible. 

Provide the levels of readiness of <span style="color:gray;">**GOOS Readiness - Data management and information products**</span>, <span style="color:gray;">**GOOS Readiness - Coordination of observations elements**</span> and <span style="color:gray;">**GOOS Readiness - Requirement processes**</span> according to the options provided in the drop down menu.The readiness level system is the approach for evaluating new components for possible inclusion in the global ocean observing systems. For more info on the categorization and description of levels, see [A Framework for Ocean Observing](https://unesdoc.unesco.org/ark:/48223/pf0000211260) (specifically pages 8–13).

Additional measurements taken/ observations made of the main EOV (BioEco EOV sub-variables, as well as Physics, Biochemistry, and Cross-disciplinary EOVs) can be provided under <span style="color:gray;">**GOOS Essential Ocean Variable (EOV) subvariables**</span> and <span style="color:gray;">**GOOS Essential Ocean Variables (EOVs): Physics, Biochemistry, and Cross-disciplinary**</span>. Choose from the drop-down selection and add as many rows of sub-variables as needed. For information on, and descriptions of sub-variables, refer to the [GOOS specification sheet](https://www.goosocean.org/index.php?option=com_content&view=article&layout=edit&id=283&Itemid=441) of each respective EOV.


### 4. Add additional Attributes

Navigate to <span style="color:gray;">**Create a new layer**</span>
under <span style="color:gray;">**Profile**</span>. Provide a name and
title for the new or edited attributes, as well as the <span
style="color:gray;">**Geometry type**</span> used. Click <span
style="color:gray;">**Create**</span>. Alternatively, select <span
style="color:gray;">**Create Layer**</span> from the <span
style="color:gray;">**Data**</span> drop down menu.

<img src="images/create_layer.png" width="50%" height="50%" />

### 5. Upload additional documents and files

Navigate to <span style="color:gray;">**Upload new documents**</span>
under <span style="color:gray;">**Profile**</span>. Provide a <span
style="color:gray;">**Title**</span> for the document to be uploaded.
Alternatively, select <span style="color:gray;">**Upload
Document**</span> from the <span style="color:gray;">**Data**</span>
drop down menu.

<img src="images/upload_doc.png" width="90%" height="90%" />

Upload the file from your device and provide a URL for the where
possible. Select the monitoring program that the newly uploaded document
should be associated with by navigating to the program title under <span
style="color:gray;">**Link to**</span>. Click <span
style="color:gray;">**Upload**</span>.

### 6. Create a new map

Navigate to <span style="color:gray;">**Create a new map**</span> under
<span style="color:gray;">**Profile**</span>. Alternatively, select
<span style="color:gray;">**Create Map**</span> from the <span
style="color:gray;">**Maps**</span> drop down menu.The interactive map
(©OpenStreetMap contributors) is a useful tool for creating maps with
new spacial data or by using data from an existing monitoring program on
GeoNode GOOS BioEco. It further enables the user to perform basic
functions such as measuring physical distances and browsing locations or
coordinates.

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

### 7. Report an issue

Please report any issues regarding GOOS BioEco GeoNode [here](https://github.com/iobis/bioeco-geonode/issues). 

Issues encountered in the GOOS BioEco portal can be reported [here](https://github.com/iobis/bioeco-app/issues).  
