<img class="logo" width="300" alt="logo" src="../../efferent_logo.png" />

<br/>

# Release Notes

```
Product Name:   eVue and eFit
Version Number: 5.23
Release Date:   August, 2024
```

## Table of Contents

1. [Introduction](#introduction)
2. [New Features](#new-features)
3. [Improvements](#improvements)
4. [Bug Fixes](#bug-fixes)
5. [Deprecations](#deprecations)
6. [Known Issues](#known-issues)
7. [Upcoming Features](#upcoming-features)

## Introduction

Welcome to the August 2024 release of Efferent eVue and eFit. In this update, we've focused on improving several features.

## New Features

None

## Improvements

### eFit on Stitch images

The Stitch & Resect tool allows to select one or more images from a study to generate a composite image, with the option to perform cropping and apply basic transformations such as rotation and flip. From this update it will be possible to run eFit planning for hip on a stitched image, using AI and autocalibration services.

<img width=600 src="i0.png">

### Accession number field in the Imaging Study form

An editable field for the accession number has been added to the Imaging Study form displayed in the study edition view. Now, when performing a Merge, this data will also be displayed in the new study information.

_Before:_

<img width=300 src="i1.1.png">

_After:_

<img width=300 src="i1.2.png">

### Inspect view

The presentation of Audit Trail and Consents tables in the Inspect view has been improved, increasing the width of the columns according to the window size.

_Before:_

<img width=600 src="i2.1.png">

_After:_

<img width=600 src="i2.2.png">

### Delete consents in the Inspect view

Added the option to remove records from the consents list in the Inspect view. Select the record you want to delete and then click on the X next to the refresh symbol button.

<img width=600 src="i3.1.png">

<img width=350 src="i3.2.png">

### Confirmation dialog  when uploading a Dicom/MP4 without data

Added a message that pops up if the user selects the option “empty” in all patient information fields (PID, Patient Name, DOB) when uploading a Dicom or mp4. The message asks for confirmation to upload the study with all patient data empty. 

<img width=400 src="i4.png">

### Offline and Hybrid mode for SmartLink 5

#### Hybrid mode: 
eVue shall detect a local SmartLink and retrieve the study images from the SmartLink installed in the same user network, this will increase the downloading experience of the studies.
 
#### Offline mode:
In case eVue detects no connection with Efferent cloud platform, the user wil be notified to switch to offline mode. This feature will allow to keep working with the studies stored locally on SL5.

<img width= 400 src="i5.png">

### Improvement of image rendering

Image rendering has been improved, as well as the presentation of low and high resolution images by applying quality attribute correction and eliminating the grainy effect.

## Bug Fixes

- **Related Studies opened in new tabs**: When opening related studies in a new tab and repeating the process within the newly opened tab successively, some tabs were closed.

- **SmartShare to a guest-patient role**: When sharing studies to a patient who was previously registered as a guest, the user did not have access to the shared study.

## Deprecations

None

## Known Issues

None

## Upcoming Features

None


---

Thank you for being a valued user of Efferent. We hope these updates enhance your experience. For any questions or feedback, please contact our support team at support@efferenthealth.com .
