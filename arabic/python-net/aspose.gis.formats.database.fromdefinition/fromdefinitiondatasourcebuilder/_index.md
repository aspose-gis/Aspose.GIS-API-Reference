---
title: "فئة FromDefinitionDataSourceBuilder"
type: docs
weight: 10
url: /ar/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/
---

**Summary:** Provides the ability to configure a data source object

**Module:** [aspose.gis.formats.database.fromdefinition](/psd/python-net/aspose.gis.formats.database.fromdefinition/)

**Full Name:** aspose.gis.formats.database.fromdefinition.FromDefinitionDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | يضبط اسم الحقل الذي سيحتوي على معلومات سمة الميزة. |
| [build()](#build__2) | تسترجع الطريقة تنفيذًا لـ [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |
| [geometry_field(name)](#geometry_field_name_3) | يضبط اسم الحقل الذي سيتم استخراج الهندسة منه. |
| [identity_attribute(name, overwrite_same_key)](#identity_attribute_name_overwrite_same_key_4) | إعداد إلزامي يسمح بتتبع التغييرات. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

يضبط اسم الحقل الذي سيحتوي على معلومات سمة الميزة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم حقل قاعدة البيانات للسمة. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | نوع البيانات التي يجب تحويل بيانات قاعدة البيانات إليها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: build() {#build__2}


```
 build() 
```

تسترجع الطريقة تنفيذًا لـ [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/)

**Returns**

| نوع | وصف |
| :- | :- |
| [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource) | تنفيذ [IFromDefinitionDataSource](/psd/python-net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/) |


### Method: geometry_field(name) {#geometry_field_name_3}


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
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


### Method: identity_attribute(name, overwrite_same_key) {#identity_attribute_name_overwrite_same_key_4}


```
 identity_attribute(name, overwrite_same_key) 
```

إعداد إلزامي يسمح بتتبع التغييرات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | سمة للميزة سيتم التعامل معها على أنها تحدد الميزة بشكل فريد. |
| overwrite_same_key | bool | إذا تم تعيين هذه العلامة إلى true، فسيتم استبدال الميزات المضافة حديثًا التي لها معرف فريد مماثل للموجود بالفعل في الطبقة، <br/>            وسيتم الكتابة فوق الحالية، وسيتم قراءة البيانات كأنها محدثة إذا تم العثور على اختلافات.<br/>            وإلا، سيتم إلقاء استثناء. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder) | [FromDefinitionDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.fromdefinition/fromdefinitiondatasourcebuilder/) |


