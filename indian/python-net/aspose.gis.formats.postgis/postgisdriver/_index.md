---
title: "PostGisDriver क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.gis.formats.postgis/postgisdriver/
---

**Summary:** A driver for the PostGIS database.

**Module:** [aspose.gis.formats.postgis](/psd/python-net/aspose.gis.formats.postgis/)

**Full Name:** aspose.gis.formats.postgis.PostGisDriver

**Inheritance:** DatabaseDriver

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [from_definition(table_name)](#from_definition_table_name_1) | डेटा स्रोत [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) को कॉन्फ़िगर करने की प्रक्रिया की शुरुआत की अनुमति देता है ताकि इसके साथ आगे काम किया जा सके। |
| [from_query(query)](#from_query_query_2) | कस्टम डेटाबेस क्वेरीज़ के लिए डेटा स्रोत को कॉन्फ़िगर करना। |


### Method: from_definition(table_name) {#from_definition_table_name_1}


```
 from_definition(table_name) 
```

डेटा स्रोत [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) को कॉन्फ़िगर करने की प्रक्रिया की शुरुआत की अनुमति देता है ताकि इसके साथ आगे काम किया जा सके।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| table_name | string | डेटा निकालने के लिए डेटाबेस तालिका का नाम |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: from_query(query) {#from_query_query_2}


```
 from_query(query) 
```

कस्टम डेटाबेस क्वेरीज़ के लिए डेटा स्रोत को कॉन्फ़िगर करना।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| query | string | क्वेरी स्ट्रिंग। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


