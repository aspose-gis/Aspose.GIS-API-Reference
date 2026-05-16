---
title: "GeoConvert क्लास"
type: docs
weight: 1140
url: /hi/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | निर्दिष्ट प्रारूप में गणना की गई स्थिति को स्ट्रिंग के रूप में लौटाता है। |
| [as_point_text(point, format)](#as_point_text_point_format_2) | निर्दिष्ट प्रारूप में गणना की गई स्थिति को स्ट्रिंग के रूप में लौटाता है। |
| [parse_point_text(text)](#parse_point_text_text_3) | स्ट्रिंग जिसमें निर्देशांक हैं, उसे IPoint ऑब्जेक्ट में परिवर्तित करता है। |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | स्ट्रिंग जिसमें निर्देशांक हैं, उसे IPoint ऑब्जेक्ट में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल। |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

निर्दिष्ट प्रारूप में गणना की गई स्थिति को स्ट्रिंग के रूप में लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| अक्षांश | double | स्थिति अक्षांश। |
| देशांतर | double | स्थिति देशांतर। |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | परिणाम का प्रारूप। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | स्थिति स्ट्रिंग के रूप में। |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

निर्दिष्ट प्रारूप में गणना की गई स्थिति को स्ट्रिंग के रूप में लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint ऑब्जेक्ट। |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | परिणाम का प्रारूप। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | स्थिति स्ट्रिंग के रूप में। |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

स्ट्रिंग जिसमें निर्देशांक हैं, उसे IPoint ऑब्जेक्ट में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | string | परिवर्तित करने के लिए निर्देशांक वाली स्ट्रिंग।<br/>            स्ट्रिंग में दोनों अक्षांश और देशांतर निर्देशांक होने चाहिए।<br/>            निर्देशांक को whitespace, कॉमा या सेमीकोलन द्वारा अलग किया जाना चाहिए। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | इनपुट स्ट्रिंग के बराबर निर्देशांक वाला IPoint ऑब्जेक्ट। |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

स्ट्रिंग जिसमें निर्देशांक हैं, उसे IPoint ऑब्जेक्ट में परिवर्तित करता है। एक रिटर्न वैल्यू यह दर्शाती है कि रूपांतरण सफल हुआ या विफल।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| text | string | परिवर्तित करने के लिए निर्देशांक वाली स्ट्रिंग।<br/>            स्ट्रिंग में दोनों अक्षांश और देशांतर निर्देशांक होने चाहिए।<br/>            निर्देशांक को whitespace, कॉमा या सेमीकोलन द्वारा अलग किया जाना चाहिए। |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | जब यह मेथड रिटर्न करता है, तो इसमें पार्स किए गए निर्देशांक वाला IPoint ऑब्जेक्ट होता है, यदि रूपांतरण सफल हुआ, अन्यथा यदि रूपांतरण विफल हुआ तो null। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यदि टेक्स्ट सफलतापूर्वक पार्स हुआ हो तो True, अन्यथा False। |


