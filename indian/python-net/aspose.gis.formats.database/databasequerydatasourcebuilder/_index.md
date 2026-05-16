---
title: "DatabaseQueryDataSourceBuilder क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | फ़ीचर एट्रिब्यूट के लिए जानकारी रखने वाले फ़ील्ड का नाम कॉन्फ़िगर करता है। |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | परिणामी लेयर को बदलावों को ट्रैक करने के लिए कॉन्फ़िगर करें और किए गए बदलावों को सिंक्रनाइज़ करने के लिए डेटा स्रोत बनाएं। |
| [build()](#build__3) | यह मेथड [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) का इम्प्लीमेंटेशन प्राप्त करता है। |
| [geometry_field(name)](#geometry_field_name_4) | उस फ़ील्ड का नाम कॉन्फ़िगर करता है जिससे ज्यामिति निकाली जाएगी। |
| [srid_field(name)](#srid_field_name_5) | स्पैशियल रेफ़रेंस सिस्टम आइडेंटिफ़ायर (srid) रखने वाले क्वेरी फ़ील्ड के नाम को कॉन्फ़िगर करना। |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | आपको डेटा स्रोत को थर्ड-पार्टी स्पैशियल रेफ़रेंस सिस्टम डेटा उपयोग करने के लिए कॉन्फ़िगर करने की अनुमति देता है, Aspose.GIS लाइब्रेरी में प्री-इंस्टॉल्ड डेटा को बायपास करते हुए। |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

फ़ीचर एट्रिब्यूट के लिए जानकारी रखने वाले फ़ील्ड का नाम कॉन्फ़िगर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | एट्रिब्यूट के लिए क्वेरी फ़ील्ड का नाम। |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | डेटाबेस से डेटा को जिस प्रकार के डेटा में परिवर्तित किया जाना चाहिए। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

परिणामी लेयर को बदलावों को ट्रैक करने के लिए कॉन्फ़िगर करें और किए गए बदलावों को सिंक्रनाइज़ करने के लिए डेटा स्रोत बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| table_name | string | टेबल का नाम जहाँ बदलाव किए जाएंगे। |
| identity_attribute | string | एक विशेषता जो किसी फीचर को अद्वितीय रूप से पहचानने के लिए मानी जाएगी। |
| overwrite_same_key | bool | यदि यह फ़्लैग true पर सेट किया गया है, तो लेयर में पहले से मौजूद समान यूनिक आइडेंटिफ़ायर वाले नए जोड़े गए फीचर को वर्तमान वाला ओवरराइट कर दिया जाएगा, और यदि अंतर पाया जाता है तो डेटा को अपडेटेड के रूप में पढ़ा जाएगा। |
| db_func | string | फ़ंक्शन जो SQL क्वेरी में प्रदान किया जाएगा ताकि बाइनरी डेटा को वर्तमान डेटाबेस के जियोग्राफिक डेटा प्रतिनिधित्व में परिवर्तित किया जा सके। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

यह मेथड [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) का इम्प्लीमेंटेशन प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) का इम्प्लीमेंटेशन |


### Method: geometry_field(name) {#geometry_field_name_4}


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
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

स्पैशियल रेफ़रेंस सिस्टम आइडेंटिफ़ायर (srid) रखने वाले क्वेरी फ़ील्ड के नाम को कॉन्फ़िगर करना।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | स्पैशियल रेफ़रेंस सिस्टम आइडेंटिफ़ायर रखने वाले क्वेरी फ़ील्ड का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

आपको डेटा स्रोत को थर्ड-पार्टी स्पैशियल रेफ़रेंस सिस्टम डेटा उपयोग करने के लिए कॉन्फ़िगर करने की अनुमति देता है, Aspose.GIS लाइब्रेरी में प्री-इंस्टॉल्ड डेटा को बायपास करते हुए।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| srs_query | string | मुख्य क्वेरी में उपयोग किए गए अतिरिक्त स्थानिक निर्देशांक प्रणालियों के बारे में जानकारी प्राप्त करने के लिए क्वेरी। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


