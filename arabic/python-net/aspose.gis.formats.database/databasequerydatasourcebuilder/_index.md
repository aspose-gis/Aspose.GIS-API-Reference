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
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | يضبط اسم الحقل الذي سيحتوي على معلومات سمة الميزة. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | قم بتكوين الطبقة الناتجة لتتبع التغييرات وإنشاء مصدر بيانات لمزامنة التغييرات التي تم إجراؤها. |
| [build()](#build__3) | تسترجع الطريقة تنفيذًا لـ [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |
| [geometry_field(name)](#geometry_field_name_4) | يضبط اسم الحقل الذي سيتم استخراج الهندسة منه. |
| [srid_field(name)](#srid_field_name_5) | تكوين اسم حقل الاستعلام الذي سيحتوي على معرف نظام الإحداثيات المكاني (srid). |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | يسمح لك بتكوين مصدر البيانات لاستخدام بيانات نظام الإحداثيات المكاني من طرف ثالث، متجاوزًا البيانات المثبتة مسبقًا في مكتبة Aspose.GIS. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

يضبط اسم الحقل الذي سيحتوي على معلومات سمة الميزة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم حقل الاستعلام للخاصية. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | نوع البيانات التي يجب تحويل بيانات قاعدة البيانات إليها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

قم بتكوين الطبقة الناتجة لتتبع التغييرات وإنشاء مصدر بيانات لمزامنة التغييرات التي تم إجراؤها.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| table_name | string | اسم الجدول الذي ستُجرى فيه التغييرات. |
| identity_attribute | string | سمة للميزة سيتم التعامل معها على أنها تحدد الميزة بشكل فريد. |
| overwrite_same_key | bool | إذا تم تعيين هذه العلامة إلى true، فسيتم استبدال الميزات المضافة حديثًا ذات المعرف الفريد المتطابق مع الموجود بالفعل في الطبقة، وسيتم قراءة البيانات كأنها محدثة إذا وُجدت اختلافات. |
| db_func | string | الدالة التي سيتم توفيرها في استعلام SQL لتحويل البيانات الثنائية إلى تمثيل بيانات جغرافية لقاعدة البيانات الحالية. |

**Returns**

| نوع | وصف |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

تسترجع الطريقة تنفيذًا لـ [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/)

**Returns**

| نوع | وصف |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | تنفيذ لـ [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

يضبط اسم الحقل الذي سيتم استخراج الهندسة منه.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم حقل الهندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

تكوين اسم حقل الاستعلام الذي سيحتوي على معرف نظام الإحداثيات المكاني (srid).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم حقل الاستعلام الذي يحتوي على معرف نظام الإحداثيات المكاني. |

**Returns**

| نوع | وصف |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

يسمح لك بتكوين مصدر البيانات لاستخدام بيانات نظام الإحداثيات المكاني من طرف ثالث، متجاوزًا البيانات المثبتة مسبقًا في مكتبة Aspose.GIS.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| srs_query | string | استعلام لاسترجاع معلومات حول أنظمة الإحداثيات المكانية الإضافية المستخدمة في الاستعلام الرئيسي لاسترجاع الكائنات. |

**Returns**

| نوع | وصف |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


