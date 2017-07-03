## Barcode Reader FI

## Description

This widget can be used to read a bar code in different formats or to manually enter it, providing a backend lookup just specifying table name and lookup column in the options.
The image can be provided straigh from camera or camera roll/file system (mobile and desktop).

## Screenshots
![alt text](../images/pe-barcode-reader-fi-01.png "Barcode Reader - Options")
![alt text](../images/pe-barcode-reader-fi-02.png "Barcode Reader - Initial UI")
![alt text](../images/pe-barcode-reader-fi-03.png "Barcode Reader - After code extraction from image")
![alt text](../images/pe-barcode-reader-fi-04.png "Barcode Reader - Manual lookup")

## Additional Information/Notes
> None
---
## Installation
Download and install update set **[pe-barcode-reader-fi.u-update-set.xml](pe-barcode-reader-fi.u-update-set.xml)** <br/><br/>
After installation, the widget can be accessed via the `Service Portal > Widgets` section for use and customization.<br/>
* SN Product Documentation - ['Load a customization from a single XML file'](https://docs.servicenow.com/search?q=Load+a+customization+from+a+single+XML+file)   (<i>Select appropriate instance version</i>)
---
## Configuration
Language variants can be created through the section System UI -> UI Messages, and displayed adding in the HTML body a statement with the syntax:<br/>
* ${<i>key value specified in the Message record</i>}.
---
## Platform Dependencies
> None
---
## Sample Data and Data Structures
> See 'Configuration' above
---
## API Dependencies
* QuaggaJS <br/>
<i>Dependencies are included and configured as part of the provided Update Set.</i>
> None
---
## CSS/SASS Variables
The widget is using colors from Bootstrap SASS variables, and a minimal style configuration to make it easy to customize.
_CSS/SASS variables are given default values that can be overridden with theming or portal-level CSS._