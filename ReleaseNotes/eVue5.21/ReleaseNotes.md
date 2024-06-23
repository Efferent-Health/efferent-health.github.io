<img class="logo" width="300" alt="logo" src="../../efferent_logo.png" />

<br/>

# Release Notes

```
Product Name:   eVue and eFit
Version Number: 5.21
Release Date:   June, 2024
```

## Table of Contents

1. [Introduction](#introduction)
2. [New Features](#new-features)
3. [Improvements](#improvements)
4. [Bug Fixes](#bug-fixes)
5. [Deprecations](#deprecations)
6. [Known Issues](#known-issues)
7. [Upcoming Features](#upcoming-features)
8. [Patch Release 5.20.1](#patch-release-5-20-1)

## Introduction

Welcome to the June, 2024 release of Efferent eVue and eFit. In this update, we've focused on enhancing the user experience to ensure the best performance for our users.

## New Features

### Pelvic tool
The Pelvic tool is an eFit tool capable of calculating the inclination of the hip from the lateral view. To get the inclination angle, the user has to set the landmarks of the Anterior Pelvic Plane and the Pelvic Tilt as seen in the images, they can be set manually or with the help an integrated AI algorithm.


_Manual Process drawing points_

<img height=300 src="I0.1.png">

_Using the AI Algorithm_

<img height=300 src="I0.2.png">

## Improvements

### Annotations on multiframe images
Annotations on multi-frame images were not enabled independently, so they were applied to all frames of an image. Now annotations can be made and displayed on each frame as expected.

_Annotations in frame 2/77_
<img width=400 src="I2.1.png">

_Annotations in frame 3/77_
<img width=400 src="I2.2.png">

### Dicom upload with graphic annotations
This enhancement supports the uploading of dicom files containing previous annotations. These images can now be displayed in eVue with the annotations from the Dicom.

<img width=400 src="I3.png">


### Soft deletion of several selected studies
The action of deleting more than one selected study at a time has been enabled. This applies to delete studies from the worklist, removing them to the recycle bin.


<img width=600 src="I1.png">

### Quick Print preview
An image preview has been implemented in the quick print options when selecting "current image". Previously this layout was limited to show a gray square instead to represent the scale of the image on the print sheet.

_Before_

<img width=400 src="I4.1.png">

_After_

<img width=400 src="I4.2.png">

### Autosave for AI in Hip Implant tool

This improvement consists of an automatic save of the annotations made with the AI in the hip implant tool, avoiding the loss of changes during the process.


_Adding the first annotations:_

<img width=300 src="I5.1.png">



_After closing and reopening the study with unsaved changes:_

<img width=300 src="I5.2.png">



## Bug Fixes

- **Thumbnails scroll bar in top and bottom position**: The scrollbar for thumbnails was not displayed when thumbnails were placed horizontally above or below the viewport.


## Deprecations

None

## Known Issues

None

## Upcoming Features




---

Thank you for being a valued user of Efferent. We hope these updates enhance your experience. For any questions or feedback, please contact our support team at support@efferenthealth.com .