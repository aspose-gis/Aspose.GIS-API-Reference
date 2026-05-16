---
title: "GeographicDatum क्लास"
type: docs
weight: 70
url: /hi/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | नया इंस्टेंस बनाता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid, इस डेटम में पृथ्वी का अनुमान लगाने के लिए उपयोग किया जाता है। |
| epsg_code | इंट | r | यदि इस वस्तु का पहचानकर्ता EPSG पहचानकर्ता है - तो उसका कोड लौटाएँ। अन्यथा -1 लौटाएँ। |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | ETRS 89 डेटम। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | इस पहचाने जाने योग्य वस्तु का पहचानकर्ता। |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | NAD 83 डेटम। |
| नाम | string | r | इस वस्तु का नाम। |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | OSGB 1936 डेटम। |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters जो इस डेटम में निर्देशांक को WGS84 डेटम में निर्देशांक में बदलने के लिए उपयोग किए जा सकते हैं। |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 72 डेटम। |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 84 डेटम। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | निर्धारित करता है कि दो डेटम समतुल्य हैं या नहीं।<br/>            समतुल्य डेटम के समान निर्देशांक पृथ्वी पर एक ही स्थान से मेल खाते हैं।<br/>            समतुल्य डेटम के कुछ पैरामीटर अलग हो सकते हैं, उदाहरण के लिए [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | निर्धारित करता है कि दो डेटम समतुल्य हैं या नहीं।<br/>            समतुल्य डेटम के समान निर्देशांक पृथ्वी पर एक ही स्थान से मेल खाते हैं।<br/>            समतुल्य डेटम के कुछ पैरामीटर अलग हो सकते हैं, उदाहरण के लिए [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | इस डेटम का नाम। |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | इस डेटम का Ellipsoid। null नहीं हो सकता। |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | पैरामीटर, जिन्हें bursa wolf सूत्र को दिया जा सकता है, इस डेटम में निर्देशांक को WGS84 डेटम में निर्देशांक में बदलने के लिए।<br/>            यदि यह डेटम WGS84 के निकट है और कोई परिवर्तन आवश्यक नहीं है, तो सभी मान 0 सेट किए हुए bursa wolf पैरामीटर पास करें।<br/>            यदि null है, तो ToWgs84 को [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) पैरामीटर पर सेट किया जाएगा। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | इस डेटम का पहचानकर्ता। |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

निर्धारित करता है कि दो डेटम समतुल्य हैं या नहीं।<br/>            समतुल्य डेटम के समान निर्देशांक पृथ्वी पर एक ही स्थान से मेल खाते हैं।<br/>            समतुल्य डेटम के कुछ पैरामीटर अलग हो सकते हैं, उदाहरण के लिए [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | पहला डेटम। |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | दूसरा डेटम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | bool मान, जो दर्शाता है कि दो डेटम समतुल्य हैं या नहीं। |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

निर्धारित करता है कि दो डेटम समतुल्य हैं या नहीं।<br/>            समतुल्य डेटम के समान निर्देशांक पृथ्वी पर एक ही स्थान से मेल खाते हैं।<br/>            समतुल्य डेटम के कुछ पैरामीटर अलग हो सकते हैं, उदाहरण के लिए [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | अन्य डेटम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | bool मान, जो दर्शाता है कि दो डेटम समतुल्य हैं या नहीं। |


