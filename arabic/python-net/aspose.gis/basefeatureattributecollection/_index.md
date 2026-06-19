---
title: "فئة BaseFeatureAttributeCollection"
type: docs
weight: 90
url: /ar/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | يحصل على عدد السمات في [Feature](/psd/python-net/aspose.gis/feature/). |
| is_locked | bool | r | يحصل على قيمة تشير إلى ما إذا كانت مجموعة السمات هذه مقفلة. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | يضيف سمة إلى المجموعة. |
| [contains(name)](#contains_name_2) | يحدد ما إذا كانت مجموعة السمات تحتوي على سمة بالاسم المحدد. |
| [index_of(name)](#index_of_name_3) | يبحث عن السمة ويعيد الفهرس الصفري الخاص بها. |
| lock() | يقفل مجموعة السمات هذه لمنع التعديلات الإضافية. |
| [remove(index)](#remove_index_4) | يزيل السمة من المجموعة. |
| [remove(name)](#remove_name_5) | يزيل السمة من المجموعة. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

يضيف سمة إلى المجموعة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | السمة المراد إضافتها. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

يحدد ما إذا كانت مجموعة السمات تحتوي على سمة بالاسم المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم السمة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كانت مجموعة السمات تحتوي على سمة بالاسم المحدد؛ وإلا، <see langword=\"false\" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

يبحث عن السمة ويعيد الفهرس الصفري الخاص بها.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم السمة. |

**Returns**

| نوع | وصف |
| :- | :- |
| int | الفهرس الصفري للسمة داخل المجموعة، إذا تم العثور عليها؛ وإلا، –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

يزيل السمة من المجموعة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس السمة. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

يزيل السمة من المجموعة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم السمة. |

