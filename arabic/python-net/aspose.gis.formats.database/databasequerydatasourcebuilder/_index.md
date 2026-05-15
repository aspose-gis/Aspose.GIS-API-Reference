---
title: "فئة DatabaseQueryDataSourceBuilder"
type: docs
weight: 40
url: /ar/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | يضبط اسم الحقل الذي سيحتوي على معلومات سمة الميزة. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | قم بتكوين الطبقة الناتجة لتتبع التغييرات وإنشاء مصدر بيانات لمزامنة التغييرات التي تم إجراؤها. |
| [build()](#build__3) | تسترجع الطريقة تنفيذًا للواجهة [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | يضبط اسم الحقل الذي سيتم استخراج الهندسة منه. |
| [srid_field(name)](#srid_field_name_5) | تكوين اسم حقل الاستعلام الذي سيحتوي على معرف نظام الإحداثيات المكانية (srid). |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | يتيح لك تكوين مصدر البيانات لاستخدام بيانات نظام إحداثيات مكاني من طرف ثالث، متجاوزًا البيانات المثبتة مسبقًا في مكتبة Aspose.GIS. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

يضبط اسم الحقل الذي سيحتوي على معلومات سمة الميزة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم حقل الاستعلام للخاصية. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | نوع البيانات التي يجب تحويل بيانات قاعدة البيانات إليها. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

قم بتكوين الطبقة الناتجة لتتبع التغييرات وإنشاء مصدر بيانات لمزامنة التغييرات التي تم إجراؤها.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| table_name | string | اسم الجدول الذي ستُجرى فيه التغييرات. |
| identity_attribute | string | سمة للميزة سيتم اعتبارها هي المعرّف الفريد للميزة. |
| overwrite_same_key | bool | إذا تم تعيين هذه العلامة إلى true، فسيتم استبدال الميزات المضافة حديثًا التي تحمل معرفًا فريدًا موجودًا بالفعل في الطبقة بالنسخة الحالية، وسيتم قراءة البيانات على أنها محدثة إذا وُجدت اختلافات. |
| db_func | string | دالة سيتم توفيرها في استعلام SQL لتحويل البيانات الثنائية إلى تمثيل بيانات جغرافية لقاعدة البيانات الحالية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

تسترجع الطريقة تنفيذًا للواجهة [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| نوع | الوصف |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | تنفيذ للواجهة [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

يضبط اسم الحقل الذي سيتم استخراج الهندسة منه.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم حقل الهندسة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

تكوين اسم حقل الاستعلام الذي سيحتوي على معرف نظام الإحداثيات المكانية (srid).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم حقل الاستعلام الذي يحتوي على معرف نظام الإحداثيات المكانية. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

يتيح لك تكوين مصدر البيانات لاستخدام بيانات نظام إحداثيات مكاني من طرف ثالث، متجاوزًا البيانات المثبتة مسبقًا في مكتبة Aspose.GIS.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| srs_query | string | استعلام لاسترجاع معلومات حول أنظمة الإحداثيات المكانية الإضافية المستخدمة في الاستعلام الرئيسي لاسترجاع العناصر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


