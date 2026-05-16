---
title: "BaseFeatureAttributeCollection क्लास"
type: docs
weight: 90
url: /hi/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| count | int | r | एक [Feature](/psd/python-net/aspose.gis/feature/) में विशेषताओं की संख्या प्राप्त करता है। |
| is_locked | bool | r | एक मान प्राप्त करता है जो दर्शाता है कि यह विशेषता संग्रह लॉक है या नहीं। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | संग्रह में एक विशेषता जोड़ता है। |
| [contains(name)](#contains_name_2) | निर्धारित करता है कि विशेषता संग्रह में निर्दिष्ट नाम वाली विशेषता मौजूद है या नहीं। |
| [index_of(name)](#index_of_name_3) | विशेषता को खोजता है और उसका शून्य-आधारित सूचकांक लौटाता है। |
| lock() | इस विशेषता संग्रह को लॉक करता है ताकि आगे के संशोधन रोके जा सकें। |
| [remove(index)](#remove_index_4) | संग्रह से विशेषता को हटाता है। |
| [remove(name)](#remove_name_5) | संग्रह से विशेषता को हटाता है। |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

संग्रह में एक विशेषता जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | जोड़ने के लिए विशेषता। |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

निर्धारित करता है कि विशेषता संग्रह में निर्दिष्ट नाम वाली विशेषता मौजूद है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | विशेषता का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword="true" /> यदि विशेषता संग्रह में निर्दिष्ट नाम वाली विशेषता मौजूद है; अन्यथा, <see langword="false" />। |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

विशेषता को खोजता है और उसका शून्य-आधारित सूचकांक लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | विशेषता का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| इंट | संग्रह में विशेषता का शून्य-आधारित सूचकांक, यदि मिला; अन्यथा, –1। |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

संग्रह से विशेषता को हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | विशेषता का सूचकांक। |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

संग्रह से विशेषता को हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | विशेषता का नाम। |

