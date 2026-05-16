---
title: "LocalSpatialReferenceSystem क्लास"
type: docs
weight: 130
url: /hi/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/
---

**Summary:** Local SRS related coordinates to some object, not earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.LocalSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | इस SRS को [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) में परिवर्तित करके लौटाता है।<br/>            यह पता लगाने के लिए कि परिवर्तन संभव है या नहीं, [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) का उपयोग करें। |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | इस SRS को [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) में परिवर्तित करके लौटाता है।<br/>            यह पता लगाने के लिए कि परिवर्तन संभव है या नहीं, [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) का उपयोग करें। |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | इस SRS को [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) में परिवर्तित करता है। परिवर्तन संभव है या नहीं, यह जानने के लिए [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) का उपयोग करें। |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | इसे लौटाएँ। |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | यह SRS को [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) में परिवर्तित करके लौटाता है।<br/>            यदि परिवर्तन संभव है, तो पता करने के लिए [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) का उपयोग करें। |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | इस SRS को [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) में परिवर्तित करता है। परिवर्तन संभव है या नहीं, यह जानने के लिए [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) का उपयोग करें। |
| dimensions_count | इंट | r | इस SRS में आयामों की संख्या। |
| epsg_code | इंट | r | यदि इस वस्तु का पहचानकर्ता EPSG पहचानकर्ता है - तो उसका कोड लौटाएँ। अन्यथा -1 लौटाएँ। |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) स्थानिक संदर्भ प्रणाली। |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS लैम्बर्ट एज़िमुथल इक्वल एरिया (EPSG:3035) स्थानिक संदर्भ प्रणाली। |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / लैम्बर्ट कॉन्फॉर्मल कोनिक (EPSG:3034) स्थानिक संदर्भ प्रणाली। |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | InvalidOperationException फेंकता है, क्योंकि स्थानीय SRS में भौगोलिक डेटम नहीं है। |
| has_geographic_datum | bool | r | रिटर्न करता है <see langword="false" />, क्योंकि स्थानीय SRS में भौगोलिक डेटम नहीं है। |
| has_prime_meridian | bool | r | रिटर्न करता है <see langword="false" />, क्योंकि स्थानीय SRS में प्रमुख मेरिडियन नहीं है। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | इस पहचाने जाने योग्य वस्तु का पहचानकर्ता। |
| is_compound | bool | r | यह बताता है कि यह SRS संयुक्त है या नहीं (दो SRS का संघ)।<br/>            संयुक्त SRS में निम्नलिखित संयोजन मान्य माने जाते हैं:<br/>            Geographic SRS + Vertical SRS, इस स्थिति में संयुक्त SRS का प्रकार [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) होगा।<br/>            Projected SRS + Vertical SRS, इस स्थिति में संयुक्त SRS का प्रकार [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) होगा।<br/>            यदि SRS के संयोजन अलग हैं, तो संयुक्त SRS का प्रकार [SpatialReferenceSystemType.UNKNOWN](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) होगा। |
| is_single | bool | r | यह बताता है कि यह SRS एकल है (दो SRS का संघ नहीं)। |
| is_valid | bool | r | यह <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> के समान है, लेकिन त्रुटि संदेश नहीं लौटाता। |
| local_datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | r | डेटम, जो मापन विधि का वर्णन करता है। |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) स्थानिक संदर्भ प्रणाली। |
| नाम | string | r | इस वस्तु का नाम। |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) स्थानिक संदर्भ प्रणाली। |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / ब्रिटिश नेशनल ग्रिड (EPSG:27700) स्थानिक संदर्भ प्रणाली। |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | InvalidOperationException फेंकता है, क्योंकि स्थानीय SRS में प्रमुख मेरिडियन नहीं है। |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | रिटर्न करें [SpatialReferenceSystemType.LOCAL](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | इस SRS की इकाई। |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Web Mercator (EPSG:3857) स्थानिक संदर्भ प्रणाली। |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 72 (EPSG:4322) स्थानिक संदर्भ प्रणाली। |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 84 (EPSG:4326) स्थानिक संदर्भ प्रणाली। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | संयुक्त SRS बनाएं। |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | निर्दिष्ट EPSG कोड के आधार पर एक स्थानिक संदर्भ प्रणाली बनाएं। |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | WKT (Well-Known Text) स्ट्रिंग के आधार पर नया <c>SpatialReferenceSystem</c> बनाता है। |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | कस्टम पैरामीटर से जियोसेंट्रिक SRS बनाएं। |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | कस्टम पैरामीटर से जियोग्राफिक SRS बनाएं। |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | स्थानीय स्थानिक संदर्भ प्रणाली बनाएं। |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | कस्टम पैरामीटर से प्रोजेक्टेड SRS बनाएं। |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | इस <c>SpatialReferenceSystem</c> से दूसरे <c>SpatialReferenceSystem</c> तक रूपांतरण बनाता है। |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | वर्टिकल SRS बनाएं। |
| [export_to_wkt()](#export_to_wkt__10) | इस SRS का प्रतिनिधित्व WKT स्ट्रिंग के रूप में लौटाता है।<br/>            परिणामस्वरूप WKT स्ट्रिंग OGC 01-009 विनिर्देश के अनुरूप होगी, आमतौर पर इसे "WKT1" कहा जाता है। |
| [get_axis(dimension)](#get_axis_dimension_11) | आयाम का वर्णन करने वाला [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) प्राप्त करें। |
| [get_unit(dimension)](#get_unit_dimension_12) | प्राप्त करें [LocalSpatialReferenceSystem.unit](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) आयाम की। |
| [is_equivalent(other)](#is_equivalent_other_13) | पता करता है कि यह SRS अन्य SRS के बराबर है या नहीं। [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | निर्धारित करता है कि दो SRS बराबर हैं या नहीं।<br/>            बराबर SRS के समान निर्देशांक पृथ्वी पर एक ही स्थान से मेल खाते हैं।<br/>            बराबर SRS के कुछ पैरामीटर अलग हो सकते हैं, उदाहरण के लिए [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | निर्दिष्ट EPSG कोड के आधार पर एक स्थानिक संदर्भ प्रणाली बनाएं। |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | WKT (Well-Known Text) स्ट्रिंग के आधार पर नया <c>SpatialReferenceSystem</c> बनाता है। |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | इस <c>SpatialReferenceSystem</c> से दूसरे <c>SpatialReferenceSystem</c> तक रूपांतरण बनाता है। |
| [validate(error_message)](#validate_error_message_18) | निर्धारित करें कि यह SRS मान्य है या नहीं। वैधता विवरण के लिए <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> देखें। |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

संयुक्त SRS बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | नए SRS का नाम। |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | नए SRS का हेड SRS। |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | नए SRS का टेल SRS। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | पहचानकर्ता, जिसे SRS से जोड़ा जाएगा। पहचानकर्ता जोड़ने से अन्य SRS पैरामीटर नहीं बदलेंगे।<br/>            पहचानकर्ता और SRS पैरामीटर की स्थिरता सुनिश्चित करना आपका कार्य है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | नया संयुक्त SRS। |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

निर्दिष्ट EPSG कोड के आधार पर एक स्थानिक संदर्भ प्रणाली बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| epsg | इंट | स्पैटियल रेफ़रेंस सिस्टम का EPSG कोड। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | निर्दिष्ट EPSG कोड के साथ एक नया स्पैटियल रेफ़रेंस सिस्टम। |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

WKT (Well-Known Text) स्ट्रिंग के आधार पर नया <c>SpatialReferenceSystem</c> बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| wkt | string | WKT स्ट्रिंग। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | नया <c>SpatialReferenceSystem</c>। |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

कस्टम पैरामीटर से जियोसेंट्रिक SRS बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | निर्माण के लिए पैरामीटर। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | पहचानकर्ता, जिसे SRS से जोड़ा जाएगा। पहचानकर्ता जोड़ने से अन्य SRS पैरामीटर नहीं बदलेंगे।<br/>            पहचानकर्ता और SRS पैरामीटर की स्थिरता सुनिश्चित करना आपका कार्य है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | नया जियोसेंट्रिक SRS। |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

कस्टम पैरामीटर से जियोग्राफिक SRS बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | निर्माण के लिए पैरामीटर। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | पहचानकर्ता, जिसे SRS से जोड़ा जाएगा। पहचानकर्ता जोड़ने से अन्य SRS पैरामीटर नहीं बदलेंगे।<br/>            पहचानकर्ता और SRS पैरामीटर की स्थिरता सुनिश्चित करना आपका कार्य है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | नया जियोग्राफिक SRS। |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

स्थानीय स्थानिक संदर्भ प्रणाली बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | स्पैटियल रेफ़रेंस सिस्टम का नाम। |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | SRS में उपयोग किया जाने वाला डेटम। |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS में उपयोग किया जाने वाला यूनिट। |
| अक्ष | System.Collections.Generic.ICollection<Axis> | SRS में उपयोग किए जाने वाले अक्ष। खाली नहीं होना चाहिए। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | पहचानकर्ता, जिसे SRS से जोड़ा जाएगा। पहचानकर्ता जोड़ने से अन्य SRS पैरामीटर नहीं बदलेंगे।<br/>            पहचानकर्ता और SRS पैरामीटर की स्थिरता सुनिश्चित करना आपका कार्य है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | नया स्थानीय स्पैटियल रेफ़रेंस सिस्टम। |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

कस्टम पैरामीटर से प्रोजेक्टेड SRS बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | निर्माण के लिए पैरामीटर। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | पहचानकर्ता, जिसे SRS से जोड़ा जाएगा। पहचानकर्ता जोड़ने से अन्य SRS पैरामीटर नहीं बदलेंगे।<br/>            पहचानकर्ता और SRS पैरामीटर की स्थिरता सुनिश्चित करना आपका कार्य है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | नया प्रोजेक्टेड SRS। |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

इस <c>SpatialReferenceSystem</c> से दूसरे <c>SpatialReferenceSystem</c> तक रूपांतरण बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | एक और <c>SpatialReferenceSystem</c>। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | इस <c>SpatialReferenceSystem</c> से दूसरे <c>SpatialReferenceSystem</c> तक का ट्रांसफ़ॉर्मेशन। |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

वर्टिकल SRS बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | SRS का नाम। यदि <see langword=\"null\" />। |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | SRS में उपयोग किया जाने वाला डेटम। |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS में उपयोग किया जाने वाला यूनिट। यदि <see langword=\"null\" /> है, तो [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) उपयोग किया जाएगा। |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | SRS में उपयोग किया जाने वाला अक्ष जिसका दिशा \"up\" या \"down\" हो। यदि <see langword=\"null\" /> है, तो ऊपर की दिशा वाला अक्ष उपयोग किया जाएगा। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | पहचानकर्ता, जिसे SRS से जोड़ा जाएगा। पहचानकर्ता जोड़ने से अन्य SRS पैरामीटर नहीं बदलेंगे।<br/>            पहचानकर्ता और SRS पैरामीटर की स्थिरता सुनिश्चित करना आपका कार्य है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | नया वर्टिकल SRS। |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

इस SRS का प्रतिनिधित्व WKT स्ट्रिंग के रूप में लौटाता है।<br/>            परिणामस्वरूप WKT स्ट्रिंग OGC 01-009 विनिर्देश के अनुरूप होगी, आमतौर पर इसे "WKT1" कहा जाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | इस SRS का WKT प्रतिनिधित्व। |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

आयाम का वर्णन करने वाला [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) प्राप्त करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| आयाम | इंट | आयाम की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | आयाम का वर्णन करने वाला अक्ष। |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

प्राप्त करें [LocalSpatialReferenceSystem.unit](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) आयाम की।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| आयाम | इंट | आयाम की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | आयाम की इकाई। |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

पता करता है कि यह SRS अन्य SRS के बराबर है या नहीं। [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | अन्य SRS। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | bool मान, यह दर्शाता है कि यह SRS अन्य SRS के बराबर है या नहीं। |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

निर्धारित करता है कि दो SRS बराबर हैं या नहीं।<br/>            बराबर SRS के समान निर्देशांक पृथ्वी पर एक ही स्थान से मेल खाते हैं।<br/>            बराबर SRS के कुछ पैरामीटर अलग हो सकते हैं, उदाहरण के लिए [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | पहला SRS। |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | दूसरा SRS। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | bool मान, यह दर्शाता है कि दो SRS बराबर हैं या नहीं। |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

निर्दिष्ट EPSG कोड के आधार पर एक स्थानिक संदर्भ प्रणाली बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| epsg | इंट | स्पैटियल रेफ़रेंस सिस्टम का EPSG कोड। |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | जब यह मेथड <see langword=\"true\" /> लौटाता है, तो निर्दिष्ट EPSG कोड वाला SRS शामिल होता है; अन्यथा,<br/>            <see langword=\"null\" /> शामिल होता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि निर्दिष्ट EPSG कोड ज्ञात है और SRS बनाया गया है; अन्यथा <see langword=\"false\" />। |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

WKT (Well-Known Text) स्ट्रिंग के आधार पर नया <c>SpatialReferenceSystem</c> बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| wkt | string | WKT स्ट्रिंग। |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | जब यह मेथड <see langword=\"true\" /> लौटाता है, तो WKT से बनाया गया SRS शामिल होता है; अन्यथा,<br/>            <see langword=\"null\" /> शामिल होता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword=\"true\" /> यदि SRS सफलतापूर्वक बनाया गया है; अन्यथा <see langword=\"false\" />। |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

इस <c>SpatialReferenceSystem</c> से दूसरे <c>SpatialReferenceSystem</c> तक रूपांतरण बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | एक और <c>SpatialReferenceSystem</c>। |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | जब यह मेथड <see langword=\"true\" /> लौटाता है, तो एक ट्रांसफ़ॉर्मेशन शामिल होता है; अन्यथा, <see langword=\"null\" /> शामिल होता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | इस <c>SpatialReferenceSystem</c> से दूसरे <c>SpatialReferenceSystem</c> तक का ट्रांसफ़ॉर्मेशन। |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

निर्धारित करें कि यह SRS मान्य है या नहीं। वैधता विवरण के लिए <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" /> देखें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| error_message | String | अमान्यता का विवरण (यदि परिणाम <see langword="false" /> है) |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यदि यह SRS मान्य है - <see langword="true" />, अन्यथा - <see langword="false" />. |


