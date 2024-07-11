<img class="logo" width="300" alt="logo" src="eVue_logo.png" />

# eVue Features per Role

## Role descriptions

### Organization Admin
This role has access to every available feature in eVue, especially those that may alter DICOM files and other user privileges.

### Organization Practitioner
This is the most common role, for all kind of healthcare practitioners (physicians, techs, admins) and allows to use most of the features of eVue, with exception of admin-exclusive functions.

### Guest Practitioner
A guest practitioner is one invited by an admin or organization practitioner to use eVue to review a specific record. Features that may alter or add information to medical records are restricted.

### Patient
Patients are highly restricted to only view and share their own medical records, without any advanced feature intended for practitioners.

### Application Tags
Application tags are modifiers that allows an admin to enable or disable certain features for specific users, in case they are available at organization level.

### Extensions
Extensions are intended to enable third-party applications, typically as toolbar buttons. Efferent only use this feature for the reporting toolset.

## Worklist View

Feature|Org.<br>&numsp;&numsp;Admin&numsp;&numsp;|Org.<br>Practitioner|Guest<br>Practitioner|&numsp;Patient&numsp;|Anonymous|App&numsp;Tag?|Extension?
--|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
Filter|✓|✓|✓|||||
Search|✓|✓|✓|✓||||
Tags|✓|✓||||||
SmartShare|✓|✓|✓*|✓*||✓&sect;||
Download (As zip package/as ISO file)|✓|✓|✓|✓||✓||
Upload (DICOM, MP4, Attach)|✓|✓||||✓||
Reset Columns|✓|✓|✓|||||
Sort|✓|✓||||✓||
[Read] auto-tag|✓|✓||||✓||
Audit Trail|✓|||||||
Admin Tools (split, merge, inspect,<br>edit, delete, quarantine, anonymnize)|✓|||||||
&nbsp;

_*_ _The role can only share with the option "to practitioner's email"._

_&sect;_ _Configurable option: Share by QR code_

## Imaging Study View

Feature|Org.<br>&numsp;&numsp;Admin&numsp;&numsp;|Org.<br>Practitioner|Guest<br>Practitioner|&numsp;Patient&numsp;|Anonymous|App&numsp;Tag?|Extension?
--|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
Transform Tools (zoom, pan, rotate, etc.)|✓|✓|✓|✓|✓|||
Image render options (W/L, invert, sharpen)|✓|✓|✓|||||
Measure tools|✓|✓|✓|||||
Quick Print|✓|✓|✓|✓|✓|||
Key Image|✓|✓| | | |||
Stitch & resect|✓|✓|||||
Case Study|✓|✓| | | |||
Related study list|✓|✓||||||
Quick Compare|✓|✓| | | |||
Ortho Tools (calibration, cobb, vertebra, eLign)|✓|✓| | | |||
Multi-plannar reconstruction (MPR)|✓|✓||||✓||
eFit - Implant Surgery planning|✓|✓|||✓|✓||
Report|✓|✓| | | ||✓|
Delete Image|✓| | | | |||
&nbsp;

## Settings View

### General Settings

Feature|Org.<br>&numsp;&numsp;Admin&numsp;&numsp;|Org.<br>Practitioner|Guest<br>Practitioner|&numsp;Patient&numsp;|App&numsp;Tag?|Extension?
--|:--:|:--:|:--:|:--:|:--:|:--:|
Platform - SmartLink|✓|✓|||||
Platform - General|✓|✓|✓|✓|||||
Report Templates|✓|✓||||✓|
Practitioners|✓||||
Routings|✓||||||
&nbsp;

### Imaging Study Settings

Feature|Org.<br>&numsp;&numsp;Admin&numsp;&numsp;|Org.<br>Practitioner|Guest<br>Practitioner|&numsp;Patient&numsp;|App&numsp;Tag?|Extension?
--|:--:|:--:|:--:|:--:|:--:|:--:|
Imaging Study|✓|✓|||
DICOM - General|✓|✓|||
DICOM - Overlay Text|✓|✓|||
Ortho Tools|✓|✓|||
&nbsp;