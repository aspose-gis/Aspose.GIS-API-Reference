---
title: "WarpOptions क्लास"
type: docs
weight: 100
url: /hi/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | WarpOptions क्लास का एक नया instance प्रारंभ करता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| cell_height | double | r/w | रास्टर सेल की नई ऊँचाई (लक्षित जियोरेफ़रेंस्ड इकाइयों में) निर्दिष्ट करता है।<br/>            यदि मान 0 पर सेट किया जाता है, तो [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) स्वचालित रूप से गणना की जाती है। डिफ़ॉल्ट मान "0" है। |
| cell_width | double | r/w | रास्टर सेल की नई चौड़ाई (लक्षित जियोरेफ़रेंस्ड इकाइयों में) निर्दिष्ट करता है।<br/>            यदि मान 0 पर सेट किया जाता है, तो [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) स्वचालित रूप से गणना की जाती है। डिफ़ॉल्ट मान "0" है। |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | यदि स्रोत स्पैशियल रेफ़रेंस अनुपलब्ध है तो उसके लिए एक मान निर्दिष्ट करता है। |
| ऊँचाई | इंट | r/w | आउटपुट रास्टर की ऊँचाई पिक्सेल और कॉलम में निर्दिष्ट करता है।<br/>            यदि मान 0 पर सेट किया जाता है, तो ऊँचाई स्वचालित रूप से गणना की जाती है। डिफ़ॉल्ट मान "0" है। |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | रास्टर लेयर के सीमाओं को वॉर्प करने के लिए निर्दिष्ट करता है।<br/>            यदि <see langword="null" /> पर सेट किया जाता है, तो वॉर्पिंग के दौरान विस्तार की गणना की जाती है ताकि रास्टर के सभी सेल शामिल हों। |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | लक्षित स्पैशियल रेफ़रेंस निर्दिष्ट करता है।<br/>            यदि <see langword="null" /> पर सेट किया जाता है, तो डिफ़ॉल्ट या स्रोत स्पैशियल रेफ़रेंस उपयोग किया जाता है। |
| width | इंट | r/w | आउटपुट रास्टर की चौड़ाई पिक्सेल और कॉलम में निर्दिष्ट करता है।<br/>            यदि मान 0 पर सेट किया जाता है, तो चौड़ाई स्वचालित रूप से गणना की जाती है। डिफ़ॉल्ट मान "0" है। |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

WarpOptions क्लास का एक नया instance प्रारंभ करता है।

