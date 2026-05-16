---
title: "NumericFormat क्लास"
type: docs
weight: 2870
url: /hi/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | एक संख्यात्मक मान को स्ट्रिंग में परिवर्तित करने के बाद उसे फिर से उसी संख्यात्मक मान में पार्स करने को सुनिश्चित करने का प्रयास करता है।<br/>             |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | एक संख्या को वैज्ञानिक नोटेशन के बिना फिक्स्ड-पॉइंट टेक्स्ट में परिवर्तित करता है। |
| [general(precision)](#general_precision_2) | संख्या को फिक्स्ड-पॉइंट या वैज्ञानिक नोटेशन में से अधिक कॉम्पैक्ट रूप में परिवर्तित करता है,<br/>            संख्या के प्रकार और यदि प्रिसीजन स्पेसिफायर मौजूद है, इस पर निर्भर करता है। उपयोग करने की सलाह दी जाती है। |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

एक संख्या को वैज्ञानिक नोटेशन के बिना फिक्स्ड-पॉइंट टेक्स्ट में परिवर्तित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| significant_digits | इंट | महत्वपूर्ण अंकों की संख्या। अधिकतम उपलब्ध सटीकता "308" है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | राउंडिंग सटीकता निर्दिष्टकर्ता। |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

संख्या को फिक्स्ड-पॉइंट या वैज्ञानिक नोटेशन में से अधिक कॉम्पैक्ट रूप में परिवर्तित करता है,<br/>            संख्या के प्रकार और यदि प्रिसीजन स्पेसिफायर मौजूद है, इस पर निर्भर करता है। उपयोग करने की सलाह दी जाती है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| precision | इंट | सटीकता परिणाम स्ट्रिंग में दिखाई देने वाले अधिकतम महत्वपूर्ण अंकों की संख्या को परिभाषित करती है।<br/>            यदि सटीकता शून्य है, तो मान "15" उपयोग किया जाता है। अधिकतम उपलब्ध सटीकता "17" है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | सामान्य फ़ॉर्मेट निर्दिष्टकर्ता। |


