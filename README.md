# IBM Engineering Systems Design Rhapsody Repository
This repository provides the current release of the **SAF Profile** intended to be used with IBM Rhapsody 9.0.2 or 10.0.1. Please see the model file itself for licensing terms.

## SAF_Profile
**SAF Profile** has been created by the System Architecture Framework Working Group of the German Chapter of INCOSE, GfSE e.V. The SAF Profile contains the Stereotypes according to the [SAF-Specification](https://github.com/GfSE/SAF-Specification/), [List of Stereotypes](https://github.com/GfSE/SAF-Specification/blob/main/stereotypes.csv).


For the creation of the SAF profile the Profile Builder Technology of SodiusWillert https://www.sodiuswillert.com/en/home has been used. See additionally the videos on https://www.youtube.com/playlist?list=PLSW-q842dhtaNk9MCO9WR-ygkyClQG85I.

## Versions
This is the main branch, reflecting the current development and it is updated as required.

The following releases are available, each is kept in a separate branch:
* [Initial Release](https://github.com/GfSE/SAF-Rhapsody-Profile/tree/Initial-Release)
* [TdSE2023](https://github.com/GfSE/SAF-Rhapsody-Profile/tree/TdSE2023)
* [TdSE2024](https://github.com/GfSE/SAF-Rhapsody-Profile/tree/TdSE2024)

## Start using the SAF_Profile in IBM Rhapsody
### Step 1
Copy the **SAF_Profile** folder to "C:\Program Files\IBM\Rhapsody\9.0.2\Share\Profiles" (in Case of RHY 9.0.2) or "C:\Program Files\IBM\Rhapsody\10.0.1\Share\Profiles" (in Case of RHY 10.0.1) with supplemental material.

### Step 2
Create a new project based on the **SAF_Profile**
### Step 3
While creating a new IBM Rhapsody model select the newly created IBM Rhapsody Project and open the context menu via right click. Within the context menu you will find the entry **SAF Toolkit**
### Step 4
Select one entry to start one helper for the dedicated Domain.
* Create Common Domains Views
* Create Operational Domains Views
* Create Functional Domains Views
* Create Logical Domains Views
* Create Physical Domains Views
### Step 4
Click on the relevant Viewpoint to generate the diagram. The toolbar is available if the dedicated Perspective is selected according to the domain.
