---
title: "فئة FeatureAttribute"
type: docs
weight: 840
url: /ar/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | ينشئ مثيلاً جديداً من الفئة [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | ينشئ مثيلاً جديداً من الفئة [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_be_null | bool | قراءة/كتابة | يحصل على قيمة تشير إلى ما إذا كان هذا الكائن يمكن أن يكون فارغًا. |
| can_be_unset | bool | قراءة/كتابة | يحصل أو يعيّن قيمة تشير إلى ما إذا كان يمكن حذف قيمة هذا السمة. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | يحصل على نوع البيانات الخاص بالسمة. |
| default_value | object | قراءة/كتابة | يحصل أو يعيّن قيمة للسمة، تشير إلى بيانات مفقودة. |
| has_custom_default_value | bool | r | يحصل على قيمة تشير إلى ما إذا تم استبدال القيمة الافتراضية المحددة مسبقًا لهذه السمة بقيمة مخصصة. |
| is_locked | bool | r | يحصل على قيمة تشير إلى ما إذا كانت هذه السمة مقفلة. |
| الاسم | string | قراءة/كتابة | يحصل على اسم السمة. |
| precision | Nullable<int> | قراءة/كتابة | يحصل أو يعيّن الحد الأقصى لعدد الأرقام العشرية التي سيتم تخزينها. |
| type_name | string | قراءة/كتابة | اسم النوع الخاص بالسمة. |
| width | Nullable<int> | قراءة/كتابة | يحصل أو يعيّن الحد الأقصى المسموح به لعرض تمثيل الأحرف للسمة. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| lock() | يقفل هذه السمة. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

ينشئ مثيلاً جديداً من الفئة [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم السمة. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | نوع البيانات الخاص بالسمة. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

ينشئ مثيلاً جديداً من الفئة [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم السمة. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | نوع البيانات الخاص بالسمة. |
| can_be_null | bool | <see langword="true" /> إذا كان هذا الكائن يمكن أن يكون فارغًا؛ وإلا، <see langword="false" />. |

