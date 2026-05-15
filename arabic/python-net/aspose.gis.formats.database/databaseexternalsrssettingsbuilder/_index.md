---
title: "فئة DatabaseExternalSrsSettingsBuilder"
type: docs
weight: 30
url: /ar/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/
---

**Summary:** Provides the possibility of configuring a database query to retrieve a list of used spatial reference systems.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseExternalSrsSettingsBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [end_external_srs()](#end_external_srs__1) | أكمل تكوين نظام الإحداثيات المكاني الخارجي (srs) وأعد السياق الأصلي. |
| [external_srs_fields(auth_srid_field, sr_text_field)](#external_srs_fields_auth_srid_field_sr_text_field_2) | يحدد أسماء الحقول الخاصة التي يُقرأ منها معلومات حول أنظمة الإحداثيات المكانية المطلوبة إضافيًا. |


### Method: end_external_srs() {#end_external_srs__1}


```
 end_external_srs() 
```

أكمل تكوين نظام الإحداثيات المكاني الخارجي (srs) وأعد السياق الأصلي.

**Returns**

| نوع | الوصف |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: external_srs_fields(auth_srid_field, sr_text_field) {#external_srs_fields_auth_srid_field_sr_text_field_2}


```
 external_srs_fields(auth_srid_field, sr_text_field) 
```

يحدد أسماء الحقول الخاصة التي يُقرأ منها معلومات حول أنظمة الإحداثيات المكانية المطلوبة إضافيًا.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| auth_srid_field | string | حقل لقراءة معرف نظام الإحداثيات المكانية، الافتراضي: auth_srid. |
| sr_text_field | string | حقل لقراءة نظام الإحداثيات المكانية المُمَثَّل بصيغة WKT، الافتراضي: srtext. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


