---
title: "FeatureAttribute क्लास"
type: docs
weight: 840
url: /hi/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) क्लास का नया उदाहरण आरंभ करता है। |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) क्लास का नया उदाहरण आरंभ करता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | एक मान प्राप्त करता है जो दर्शाता है कि यह इंस्टेंस null हो सकता है या नहीं। |
| can_be_unset | bool | r/w | एक मान प्राप्त करता है या सेट करता है जो दर्शाता है कि इस विशेषता के लिए मान को छोड़ा जा सकता है या नहीं। |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | विशेषता का डेटा प्रकार प्राप्त करता है। |
| default_value | object | r/w | विशेषता के लिए एक मान प्राप्त करता है या सेट करता है, जो अनुपलब्ध डेटा को दर्शाता है। |
| has_custom_default_value | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि इस विशेषता के लिए पूर्वनिर्धारित डिफ़ॉल्ट मान को कस्टम मान से ओवरराइड किया गया है या नहीं। |
| is_locked | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह विशेषता लॉक है या नहीं। |
| नाम | string | r/w | विशेषता का नाम प्राप्त करता है। |
| precision | Nullable<int> | r/w | संग्रहीत करने के लिए अधिकतम दशमलव अंकों की संख्या प्राप्त करता है या सेट करता है। |
| type_name | string | r/w | विशेषता का प्रकार नाम। |
| width | Nullable<int> | r/w | विशेषता के अक्षर प्रतिनिधित्व की अधिकतम अनुमत चौड़ाई प्राप्त करता है या सेट करता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| lock() | इस विशेषता को लॉक करता है। |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

[FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | विशेषता का नाम। |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | विशेषता का डेटा प्रकार। |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

[FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) क्लास का नया उदाहरण आरंभ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | विशेषता का नाम। |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | विशेषता का डेटा प्रकार। |
| can_be_null | bool | <see langword="true" /> if this instance can be null; otherwise, <see langword="false" />. |

