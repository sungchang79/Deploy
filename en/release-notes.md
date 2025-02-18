## Dev Tools > Deploy > Release Notes

### 2021. 07. 27.
#### Feature Improvements
* Improved feature to extract distribution history inquiry
    * Modified so it includes distribution history where only pre-run tasks exist
* Links with the instance disposal feature when Auto Scale service-integrated deployment fails
    * Scaled-out instances are disposed when deployment fails while scaling out in the Auto Scale service
    * The scale-out feature stops working when scale-out deployment fails three times or more
* Security Vulnerability Patch



### 2021. 06. 29.
#### Feature Updates
* Changed the **Distribution History** tab search conditions
    * Search distribution history by the server group and date of execution (starting date and ending date)
    * Limited the total search duration of date of execution to 1 year
* Added a feature to be used to download the distribution history result in an Excel file
    * Added an option to be used to download distribution histories except the ones without binary file
    * 
### March 23, 2021
#### Bug Fixes
* Fixed an issue where every member of a project would not be exposed on the client binary transfer target list

### February 23, 2021
#### Feature Updates
- Added Japanese translation to autoscale related features

#### Bug Fixes
* Fixed an error where autoscale deployment intermittently fails

### January 26, 2021
#### Bug Fixes
* Fixed 2020 data check errors of deployment records tab
* 
### August 25, 2020
#### Feature Updates
* Shows time data at the start and end stamp of a log monitoring task 
* Control is available for each TOAST service role 

### April 28, 2020
#### Feature Updates
* Removed reference of http resources within https page 

### March 24, 2020
#### Feature Updates
* Health Check Task Updates
    * Allows the health check feature for individual servers 
* Service Integration with TOAST Trail 
    * TOAST Trail can check user events that occur on Deploy console  

### Feb. 25, 2020
#### Feature Updates
* Added the feature of default region setting for binary groups, when an artifact is created
    * Region (KR1/JP1) can be specified for binary groups when an artifact is created
* Added the feature of specifying default binary group for an artifact setting
    * Select from binary groups within artifact
#### Bug Fixes
* Fixed invalid binary group key setting for a binary task, when a scenario is uploaded

### Dec. 24, 2019
#### Feature Updates
* Added Region for Binary Groups
    * To be specified when a binary is created 
    * Download from the storage of an integrated region when downloading and deploying a binary
* Apply expiration time for clients' downloading pages 

### Sept. 24, 2019 
#### Feature Updates 
* Added message that binary deployment fails due to inaccessible network 

### July 23, 2019. 
#### Feature Updates
* Guides provided on Binary > iOS File Uploads > Failure of Plist Parsing
#### Feature Modification
* Adjusted that the number of characters for sms delivery does not exceed specified size.

### June 25, 2019
#### Error Fixes
* Fixed error in deployment when binary version exceeds 100 characters along with binary uploads
* Fixed error in the access to download link for deleted binary, on the download page of binaries

### May 28, 2019
#### Service Improvement 
* Search of artifacts has been added.  

#### Error Fixed 
* Fixed page error which occurs when Deployment History > Window for Results > User Command includes a script

### 2019.04.23
#### Function Improvement
* Deployment History tab > View Result popup > Update progress of distribution in real time

#### Error Correction
* Fixed an error that the task progress is not shown when deploying

### 2010.03.26
#### Function change
* Resource file upload capacity limit (1GB)

### 2017.02.26
#### Function Improvement / Change
* Editable resource size and content limit
    * Existing: Unlimited size, all editable files
    * Change: 1MB size limit, only unicode editable format is editable
* Increase task timeout time limit
    * Existing: Up to 30 minutes
    * Change: Up to 2 hours

#### Error Correction
* Select whole server group when changing server group Check box malfunction symptom correction

### 2010.01.15
#### Function Improvement / Change
* Add User Console Org Authentication

### 2018.10.23
#### Add Features
* Enable distribution termination function after distribution reentry (Distributor only)

#### Error Correction
* Resources tab > Add File > Correct the phenomenon that the file is generated even without the content of the file

### 2012.08.28
#### Add Features
* Distribution re-entry function
* Add a layer to guide page loading
* Binary upload API Ver1.0 update
* Simultaneous operation with previous versions

#### Error Correction
* Correct the operation error of the item of authentication method at distribution
* Add pem file required value check
* The problem that the input type does not switch by clicking the password / pem switch radio button

#### Document Change
* Binary upload API Ver1.0 update

### 2012.07.24
#### Add Features

* Add scenario Import / Export function
* Release restrictions on Client Type menu (all menus available)
* Add Phase property for server group equipment separator
* Added confirmation step when deploying server with Phase Type of Product

### 2012.04.24
#### Add Features

* Add binary install page access control function of client application through password input

### 2011.02.22
#### New product release

* It is a service to provide distribution and installation convenience.
* You can distribute software easily and quickly with one click.
