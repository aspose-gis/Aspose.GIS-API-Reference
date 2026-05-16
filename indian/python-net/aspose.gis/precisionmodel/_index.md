---
title: "PrecisionModel क्लास"
type: docs
weight: 3200
url: /hi/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | एक सटीक प्रिसीजन मॉडल लौटाता है।<br/>            सटीक प्रिसीजन मॉडल के अनुसार डबल मान में सभी अंक महत्वपूर्ण होते हैं। |
| is_exact | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह प्रिसीजन मॉडल सटीक है या नहीं। |
| is_rounding | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह प्रिसीजन मॉडल राउंडिंग है या नहीं। |
| significant_digits | इंट | r | यदि यह राउंडिंग है तो प्रिसीजन मॉडल में महत्वपूर्ण अंकों की संख्या प्राप्त करता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | एक राउंडिंग प्रिसीजन मॉडल लौटाता है।<br/>            राउंडिंग प्रिसीजन मॉडल के अनुसार केवल सीमित संख्या में अंक महत्वपूर्ण होते हैं। |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

एक राउंडिंग प्रिसीजन मॉडल लौटाता है।<br/>            राउंडिंग प्रिसीजन मॉडल के अनुसार केवल सीमित संख्या में अंक महत्वपूर्ण होते हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| significant_digits | इंट | महत्वपूर्ण अंकों की संख्या। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | राउंडिंग प्रिसीजन मॉडल। |


