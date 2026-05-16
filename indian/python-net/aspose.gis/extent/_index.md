---
title: "Extent क्लास"
type: docs
weight: 820
url: /hi/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [Extent()](#Extent__1) | नया इंस्टेंस बनाता है। |
| [Extent(srs)](#Extent_srs_2) | नया इंस्टेंस बनाता है। |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | नया इंस्टेंस बनाता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Extent का केंद्र। |
| ऊँचाई | double | r | Extent की ऊँचाई। |
| is_valid | bool | r | निर्धारित करता है कि यह [Extent](/psd/python-net/aspose.gis/extent/) वैध है या नहीं। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) इस extent से जुड़ा हुआ है।<br/>            यदि [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) अज्ञात है तो यह <see langword="null" /> हो सकता है.<br/>            Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem) का उपयोग करें<br/>            विभिन्न स्पैटियल रेफ़रेंस सिस्टम के बीच extent को ट्रांसफ़ॉर्म करने के लिए। |
| width | double | r | Extent की चौड़ाई। |
| x_max | double | r/w | X निर्देशांक का अधिकतम मान। |
| x_min | double | r/w | X निर्देशांक का न्यूनतम मान। |
| y_max | double | r/w | Y निर्देशांक का अधिकतम मान। |
| y_min | double | r/w | Y निर्देशांक का न्यूनतम मान। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [clone()](#clone__1) | इस उदाहरण की प्रतिलिपि बनाता है। |
| [contains(extent)](#contains_extent_2) | निर्धारित करता है कि यह विस्तार तर्क को शामिल करता है या नहीं। |
| [contains(geometry)](#contains_geometry_3) | निर्धारित करता है कि यह विस्तार तर्क को शामिल करता है या नहीं। |
| [contains(x, y)](#contains_x_y_4) | निर्धारित करता है कि यह विस्तार तर्कों द्वारा परिभाषित निर्देशांक को शामिल करता है या नहीं। |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | निर्दिष्ट [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) में नया विस्तार लौटाता है जो इस विस्तार को शामिल करता है। |
| [grow(extent)](#grow_extent_6) | इस विस्तार को इस प्रकार बढ़ाता है कि यह तर्क को शामिल करे। |
| [grow(x, y)](#grow_x_y_7) | इस विस्तार को इस प्रकार बढ़ाता है कि यह निर्दिष्ट बिंदु को शामिल करे। |
| [grow_x(value)](#grow_x_value_8) | X अक्ष के साथ इस विस्तार को इस प्रकार बढ़ाता है कि यह निर्दिष्ट मान को शामिल करे। |
| [grow_y(value)](#grow_y_value_9) | Y अक्ष के साथ इस विस्तार को इस प्रकार बढ़ाता है कि यह निर्दिष्ट मान को शामिल करे। |
| [intersects(extent)](#intersects_extent_10) | निर्धारित करता है कि यह विस्तार तर्क के साथ प्रतिच्छेद करता है या नहीं। |
| [intersects(geometry)](#intersects_geometry_11) | निर्धारित करता है कि यह विस्तार तर्क के साथ प्रतिच्छेद करता है या नहीं। |
| normalize() | यदि [Extent.width](/psd/python-net/aspose.gis/extent/) नकारात्मक है तो [Extent.x_min](/psd/python-net/aspose.gis/extent/) को [Extent.x_max](/psd/python-net/aspose.gis/extent/) के साथ बदलता है और<br/>            यदि [Extent.height](/psd/python-net/aspose.gis/extent/) नकारात्मक है तो [Extent.y_min](/psd/python-net/aspose.gis/extent/) को [Extent.y_max](/psd/python-net/aspose.gis/extent/) के साथ बदलता है। |
| [to_polygon()](#to_polygon__12) | इस विस्तार को एक आयताकार बहुभुज में परिवर्तित करता है जो इसे दर्शाता है। |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

नया इंस्टेंस बनाता है।

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) इस विस्तार से जुड़ा है।<br/>            इसे <see langword="null" /> सेट किया जा सकता है यह दर्शाने के लिए कि SRS अज्ञात है। |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x_min | double | न्यूनतम X मान। |
| y_min | double | न्यूनतम Y मान। |
| x_max | double | अधिकतम X मान। |
| y_max | double | अधिकतम Y मान। |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) इस विस्तार से जुड़ा है।<br/>            इसे <see langword="null" /> सेट किया जा सकता है यह दर्शाने के लिए कि SRS अज्ञात है। |

### Method: clone() {#clone__1}


```
 clone() 
```

इस उदाहरण की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | इस इंस्टेंस की क्लोन। |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

निर्धारित करता है कि यह विस्तार तर्क को शामिल करता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | एक अन्य विस्तार। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | मान, जो दर्शाता है कि यह विस्तार तर्क को शामिल करता है या नहीं। |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

निर्धारित करता है कि यह विस्तार तर्क को शामिल करता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | एक ज्यामिति जो समावेशन के परीक्षण के लिए है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | मान, जो दर्शाता है कि यह विस्तार तर्क को शामिल करता है या नहीं। |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

निर्धारित करता है कि यह विस्तार तर्कों द्वारा परिभाषित निर्देशांक को शामिल करता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | double | निर्देशांक का X। |
| y | double | निर्देशांक का Y। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | मान, जो दर्शाता है कि निर्देशांक बाउंडिंग बॉक्स के भीतर है या नहीं। |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

निर्दिष्ट [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) में नया विस्तार लौटाता है जो इस विस्तार को शामिल करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) जिसमें रूपांतरित करना है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | निर्दिष्ट SRS में इस विस्तार के रूपांतरण का परिणाम। |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

इस विस्तार को इस प्रकार बढ़ाता है कि यह तर्क को शामिल करे।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | अन्य विस्तार। |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

इस विस्तार को इस प्रकार बढ़ाता है कि यह निर्दिष्ट बिंदु को शामिल करे।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | double | शामिल करने के लिए X निर्देशांक। |
| y | double | शामिल करने के लिए Y निर्देशांक। |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

X अक्ष के साथ इस विस्तार को इस प्रकार बढ़ाता है कि यह निर्दिष्ट मान को शामिल करे।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| मान | double | शामिल करने के लिए मान। |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Y अक्ष के साथ इस विस्तार को इस प्रकार बढ़ाता है कि यह निर्दिष्ट मान को शामिल करे।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| मान | double | शामिल करने के लिए मान। |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

निर्धारित करता है कि यह विस्तार तर्क के साथ प्रतिच्छेद करता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | एक अन्य विस्तार। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | मान, जो दर्शाता है कि यह विस्तार तर्क के साथ प्रतिच्छेद करता है या नहीं। |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

निर्धारित करता है कि यह विस्तार तर्क के साथ प्रतिच्छेद करता है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | प्रतिच्छेद परीक्षण के लिए एक ज्यामिति |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | मान, जो दर्शाता है कि यह विस्तार तर्क के साथ प्रतिच्छेद करता है या नहीं। |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

इस विस्तार को एक आयताकार बहुभुज में परिवर्तित करता है जो इसे दर्शाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | एक आयताकार [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) जो इस विस्तार का प्रतिनिधित्व करता है। अमान्य विस्तारों के लिए<br/>            एक खाली बहुभुज लौटाया जाता है। |


