---
title: "GeographicSpatialReferenceSystemParameters क्लास"
type: docs
weight: 90
url: /hi/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/
---

**Summary:** Parameters to create geographic SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [GeographicSpatialReferenceSystemParameters()](#GeographicSpatialReferenceSystemParameters__1) | GeographicSpatialReferenceSystemParameters क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | इस SRS में उपयोग किए जाने वाले इकाइयाँ। डिफ़ॉल्ट है [Unit.degree](/psd/python-net/aspose.gis.spatialreferencing/unit/)। |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r/w | अक्षों का क्रम। डिफ़ॉल्ट है [GeographicAxisesOrder.LONGITUDE_LATITUDE](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/)। |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | भौगोलिक SRS का डेटम। डिफ़ॉल्ट है [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/)। |
| latitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | अक्ष जो अक्षांश का वर्णन करता है। डिफ़ॉल्ट है उत्तर दिशा वाला अक्ष। |
| longitude_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | अक्ष जो देशांतर का वर्णन करता है। डिफ़ॉल्ट है पूर्व दिशा वाला अक्ष। |
| नाम | string | r/w | भौगोलिक SRS का नाम। डिफ़ॉल्ट है "Unnamed"। |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | इस SRS का प्रमुख मध्याह्न रेखा। डिफ़ॉल्ट [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) है। |


### Constructor: GeographicSpatialReferenceSystemParameters() {#GeographicSpatialReferenceSystemParameters__1}


```
 GeographicSpatialReferenceSystemParameters() 
```

GeographicSpatialReferenceSystemParameters क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है

