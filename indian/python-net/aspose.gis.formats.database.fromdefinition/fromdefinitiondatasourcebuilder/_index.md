---
title: "FromDefinitionDataSourceBuilder क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | फ़ीचर एट्रिब्यूट के लिए जानकारी रखने वाले फ़ील्ड का नाम कॉन्फ़िगर करता है। |
| [build()](#build__2) | यह मेथड [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) का कार्यान्वयन प्राप्त करता है। |
| [geometry_field(name)](#geometry_field_name_3) | उस फ़ील्ड का नाम कॉन्फ़िगर करता है जिससे ज्यामिति निकाली जाएगी। |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | परिवर्तनों को ट्रैक करने की अनुमति देने वाली अनिवार्य सेटिंग। |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

फ़ीचर एट्रिब्यूट के लिए जानकारी रखने वाले फ़ील्ड का नाम कॉन्फ़िगर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | एट्रिब्यूट के लिए डेटाबेस फ़ील्ड का नाम। |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | डेटाबेस से डेटा को जिस प्रकार के डेटा में परिवर्तित किया जाना चाहिए। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

यह मेथड [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) का कार्यान्वयन प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | का कार्यान्वयन [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


```
 geometry_field(name) 
```

उस फ़ील्ड का नाम कॉन्फ़िगर करता है जिससे ज्यामिति निकाली जाएगी।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | ज्यामिति फ़ील्ड का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

परिवर्तनों को ट्रैक करने की अनुमति देने वाली अनिवार्य सेटिंग।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | एक विशेषता जो किसी फीचर को अद्वितीय रूप से पहचानने के लिए मानी जाएगी। |
| overwrite_same_key | bool | यदि यह फ़्लैग true पर सेट किया गया है, तो लेयर में पहले से मौजूद समान अद्वितीय पहचानकर्ता वाले नए जोड़े गए फीचर, <br/>            वर्तमान वाला ओवरराइट कर दिया जाएगा, और यदि अंतर पाया जाता है तो डेटा को अपडेटेड के रूप में पढ़ा जाएगा।<br/>            अन्यथा, एक अपवाद फेंका जाएगा। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


