---
title: "Feature क्लास"
type: docs
weight: 830
url: /hi/python-net/aspose.gis/feature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | फ़ीचर की ज्यामिति प्राप्त करता है या सेट करता है।<br/>            इसे <see langword=\"null\" /> नहीं किया जा सकता, गायब ज्यामिति दर्शाने के लिए [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) का उपयोग करें। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | एक अन्य फ़ीचर से गुणों के मानों की प्रतिलिपि बनाता है। |
| [get_value(attribute_name)](#get_value_attribute_name_2) | किसी गुण का मान प्राप्त करता है। |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_3) | किसी गुण का मान प्राप्त करता है, या यदि मान सेट नहीं है या <c>null</c> है तो [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) लौटाता है। |
| [get_values(values, default_value)](#get_values_values_default_value_4) | एक एरे में सभी गुणों के मान लौटाता है। |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_5) | एक एरे में सभी गुणों के मान लौटाता है। |
| [get_values_dump(default_value)](#get_values_dump_default_value_6) | एक एरे में सभी गुणों के मान लौटाता है।<br/>            अतिरिक्त मेमोरी आवंटन से बचने के लिए Aspose.Gis.Feature.GetValues(int,System.Object) मेथड का उपयोग करने पर विचार करें। |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_7) | मानों की सूची प्राप्त करता है। List T GetValuesList का गैर-जनरिक समानार्थी |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_8) | निर्धारित करता है कि निर्दिष्ट विशेषता को स्पष्ट रूप से <c>null</c> मान पर सेट किया गया है या नहीं। |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_9) | जाँचता है कि इस फीचर में विशेषता मान सेट है या नहीं। |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_10) | मान सेट करता है। void SetValue (string attributeName, T value) का गैर-जनरिक समानार्थी |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_11) | विशेषता का मान <c>null</c> पर सेट करता है। |
| [set_values(values)](#set_values_values_12) | सभी विशेषताओं के लिए नए मान सेट करता है।<br/>            एक ही कॉल में मान सेट करने को सरल बनाने के लिए [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) मेथड का उपयोग करने पर भी विचार करें। |
| [unset_value(attribute_name)](#unset_value_attribute_name_13) | इस फीचर से विशेषता मान को हटाता है। |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

एक अन्य फ़ीचर से गुणों के मानों की प्रतिलिपि बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | जिस फीचर से मान कॉपी किए जाने हैं। |

### Method: get_value(attribute_name) {#get_value_attribute_name_2}


```
 get_value(attribute_name) 
```

किसी गुण का मान प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | विशेषता का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| object | विशेषता का मान। |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_3}


```
 get_value_or_default(attribute_name, default_value) 
```

किसी गुण का मान प्राप्त करता है, या यदि मान सेट नहीं है या <c>null</c> है तो [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | विशेषता का नाम। |
| default_value | object | यदि विशेषता मान अनुपलब्ध है तो लौटाने वाला मान। डिफ़ॉल्ट मान <see langword="null" /> है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| object | विशेषता का मान। |


### Method: get_values(values, default_value) {#get_values_values_default_value_4}


```
 get_values(values, default_value) 
```

एक एरे में सभी गुणों के मान लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| मान | object |  |
| default_value | object | यदि विशेषता मान अनुपलब्ध (अनसेट) है तो लौटाने वाला मान। डिफ़ॉल्ट मान <see langword="null" /> है।<br/>            'अनसेट' और '<see langword="null" />' मानों को अलग करने के लिए '.Value' का उपयोग करने पर विचार करें। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| इंट | कॉपी की गई विशेषताओं की संख्या। |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_5}


```
 get_values(values_count, default_value) 
```

एक एरे में सभी गुणों के मान लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| values_count | इंट | मानों की गिनती। |
| default_value | object | यदि विशेषता मान अनुपलब्ध (अनसेट) है तो लौटाने वाला मान। डिफ़ॉल्ट मान <see langword="null" /> है।<br/>            'अनसेट' और '<see langword="null" />' मानों को अलग करने के लिए '.Value' का उपयोग करने पर विचार करें। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| object | कॉपी की गई विशेषताओं की संख्या। |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_6}


```
 get_values_dump(default_value) 
```

एक एरे में सभी गुणों के मान लौटाता है।<br/>            अतिरिक्त मेमोरी आवंटन से बचने के लिए Aspose.Gis.Feature.GetValues(int,System.Object) मेथड का उपयोग करने पर विचार करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| default_value | object | यदि विशेषता मान अनुपलब्ध (अनसेट) है तो लौटाने वाला मान। डिफ़ॉल्ट मान <see langword="null" /> है।<br/>            'अनसेट' और '<see langword="null" />' मानों को अलग करने के लिए '.Value' का उपयोग करने पर विचार करें। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| object | एक नया एरे जिसमें विशेषताओं के मान कॉपी किए जाएंगे। |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_7}


```
 get_values_list(attribute_name, separator, count) 
```

मानों की सूची प्राप्त करता है। List T GetValuesList का गैर-जनरिक समानार्थी

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | विशेषता का नाम। |
| separator | string | एक स्ट्रिंग जिसका उपयोग अनुक्रम के विशेषता नाम और अनुक्रमांक मान को अलग करने के लिए किया जाता है। |
| गिनती | इंट | लौटाने के लिए मानों की गिनती (छूटे हुए मान को null से भरें) |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| object | विशेषताओं के मानों की सूची जिनके नाम अनुक्रमांक मान के अनुसार अलग हैं। |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_8}


```
 is_value_null(attribute_name) 
```

निर्धारित करता है कि निर्दिष्ट विशेषता को स्पष्ट रूप से <c>null</c> मान पर सेट किया गया है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | विशेषता का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword="true" /> यदि विशेषता मान <c>null</c> है; अन्यथा, <see langword="false" />। |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_9}


```
 is_value_set(attribute_name) 
```

जाँचता है कि इस फीचर में विशेषता मान सेट है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | विशेषता का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword="true" /> यदि निर्दिष्ट विशेषता का मान सेट है; अन्यथा, <see langword="false" />। |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_10}


```
 set_value(attribute_name, value) 
```

मान सेट करता है। void SetValue (string attributeName, T value) का गैर-जनरिक समानार्थी

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | विशेषता का नाम। |
| मान | object | विशेषता का मान। |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_11}


```
 set_value_null(attribute_name) 
```

विशेषता का मान <c>null</c> पर सेट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | विशेषता का नाम। |

### Method: set_values(values) {#set_values_values_12}


```
 set_values(values) 
```

सभी विशेषताओं के लिए नए मान सेट करता है।<br/>            एक ही कॉल में मान सेट करने को सरल बनाने के लिए [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) मेथड का उपयोग करने पर भी विचार करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| मान | object | नए मानों का एरे। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| इंट | सेट किए गए एट्रिब्यूट मानों की संख्या। |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_13}


```
 unset_value(attribute_name) 
```

इस फीचर से विशेषता मान को हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | विशेषता का नाम। |

