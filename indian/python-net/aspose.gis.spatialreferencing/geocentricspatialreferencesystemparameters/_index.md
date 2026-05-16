---
title: "GeocentricSpatialReferenceSystemParameters क्लास"
type: docs
weight: 60
url: /hi/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/
---

**Summary:** Parameters to create geocentric SRS.<br/>            Parameters have reasonable defaults, so you will have to assign only some of them.<br/>            If you assign <see langword="null" /> to any parameter, a default value will be used.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeocentricSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [GeocentricSpatialReferenceSystemParameters()](#GeocentricSpatialReferenceSystemParameters__1) | GeocentricSpatialReferenceSystemParameters क्लास का नया उदाहरण आरंभ करता है |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| axises_order | [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder) | r/w | अक्षों का क्रम। डिफ़ॉल्ट रूप से [GeocentricAxisesOrder.XYZ](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) है। |
| datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r/w | जियोसेंट्रिक SRS का डेटम। डिफ़ॉल्ट [GeographicDatum.wgs84](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) है। |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | इस SRS में उपयोग किए जाने वाले इकाइयाँ। डिफ़ॉल्ट रूप से [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) है। |
| नाम | string | r/w | जियोसेंट्रिक SRS का नाम। डिफ़ॉल्ट "Unnamed" है। |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r/w | इस SRS का प्रमुख मध्याह्न रेखा। डिफ़ॉल्ट [PrimeMeridian.greenwich](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) है। |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | जियोसेंट्रिक SRS की वह धुरी जो 'X' आयाम का वर्णन करती है (धुरी जो प्रमुख मध्याह्न रेखा की ओर संकेत करती है)। |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | जियोसेंट्रिक SRS की वह धुरी जो 'Y' आयाम का वर्णन करती है (धुरी जो विषुवत तल पर X धुरी के बाएँ या दाएँ की ओर संकेत करती है)।<br/>            डिफ़ॉल्ट रूप से धुरी का दिशा [AxisDirection.EAST](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) है। |
| z_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | जियोसेंट्रिक SRS की वह धुरी जो 'Z' आयाम का वर्णन करती है (धुरी जो उत्तर या दक्षिण ध्रुव की ओर संकेत करती है)।<br/>            डिफ़ॉल्ट रूप से धुरी का दिशा [AxisDirection.NORTH](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) है। |


### Constructor: GeocentricSpatialReferenceSystemParameters() {#GeocentricSpatialReferenceSystemParameters__1}


```
 GeocentricSpatialReferenceSystemParameters() 
```

GeocentricSpatialReferenceSystemParameters क्लास का नया उदाहरण आरंभ करता है

