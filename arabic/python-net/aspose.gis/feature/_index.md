---
title: "فئة Feature"
type: docs
weight: 830
url: /ar/python-net/aspose.gis/feature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | يحصل على أو يضبط هندسة العنصر.<br/>            لا يمكن أن تكون <see langword=\"null\" />، استخدم [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) للإشارة إلى هندسة مفقودة. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | ينسخ قيم الخصائص من عنصر آخر. |
| [get_value(attribute_name)](#get_value_attribute_name_2) | يحصل على قيمة الخاصية. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_3) | يحصل على قيمة الخاصية، أو [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) إذا كانت القيمة غير مضبوطة أو <c>null</c>. |
| [get_values(values, default_value)](#get_values_values_default_value_4) | يعيد القيم لجميع الخصائص في مصفوفة. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_5) | يعيد القيم لجميع الخصائص في مصفوفة. |
| [get_values_dump(default_value)](#get_values_dump_default_value_6) | يعيد القيم لجميع الخصائص في مصفوفة.<br/>            يُنصح باستخدام طريقة Aspose.Gis.Feature.GetValues(int,System.Object) لتجنب تخصيص الذاكرة الإضافي. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_7) | يحصل على قائمة القيم. نظير غير عام لـ List T GetValuesList |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_8) | يحدد ما إذا كان السمة المحددة قد تم تعيينها صراحةً إلى القيمة <c>null</c>. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_9) | يتحقق مما إذا كانت قيمة السمة مضبوطة في هذه الميزة. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_10) | يضبط القيمة. نظير غير عام لـ void SetValue (string attributeName, T value) |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_11) | يضبط قيمة السمة إلى <c>null</c>. |
| [set_values(values)](#set_values_values_12) | يضبط قيمًا جديدة لجميع السمات.<br/>            كما يُنصح باستخدام طريقة [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) لتبسيط ضبط القيم في استدعاء واحد. |
| [unset_value(attribute_name)](#unset_value_attribute_name_13) | يزيل قيمة السمة من هذه الميزة. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

ينسخ قيم الخصائص من عنصر آخر.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | الميزة التي يتم نسخ القيم منها. |

### Method: get_value(attribute_name) {#get_value_attribute_name_2}


```
 get_value(attribute_name) 
```

يحصل على قيمة الخاصية.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | اسم السمة. |

**Returns**

| نوع | وصف |
| :- | :- |
| object | قيمة السمة. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_3}


```
 get_value_or_default(attribute_name, default_value) 
```

يحصل على قيمة الخاصية، أو [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) إذا كانت القيمة غير مضبوطة أو <c>null</c>.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | اسم السمة. |
| default_value | object | القيمة التي تُرجع إذا كانت قيمة السمة مفقودة. القيمة الافتراضية هي <see langword="null" />. |

**Returns**

| نوع | وصف |
| :- | :- |
| object | قيمة السمة. |


### Method: get_values(values, default_value) {#get_values_values_default_value_4}


```
 get_values(values, default_value) 
```

يعيد القيم لجميع الخصائص في مصفوفة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| values | object |  |
| default_value | object | القيمة التي تُرجع إذا كانت قيمة السمة مفقودة (غير مضبوطة). القيمة الافتراضية هي <see langword="null" />.<br/>            يُنصح باستخدام '.Value' للتمييز بين القيم 'غير المضبوطة' و '<see langword="null" />'. |

**Returns**

| نوع | وصف |
| :- | :- |
| int | عدد السمات التي تم نسخها. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_5}


```
 get_values(values_count, default_value) 
```

يعيد القيم لجميع الخصائص في مصفوفة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| values_count | int | عدد القيم. |
| default_value | object | القيمة التي تُرجع إذا كانت قيمة السمة مفقودة (غير مضبوطة). القيمة الافتراضية هي <see langword="null" />.<br/>            يُنصح باستخدام '.Value' للتمييز بين القيم 'غير المضبوطة' و '<see langword="null" />'. |

**Returns**

| نوع | وصف |
| :- | :- |
| object | عدد السمات التي تم نسخها. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_6}


```
 get_values_dump(default_value) 
```

يعيد القيم لجميع الخصائص في مصفوفة.<br/>            يُنصح باستخدام طريقة Aspose.Gis.Feature.GetValues(int,System.Object) لتجنب تخصيص الذاكرة الإضافي.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| default_value | object | القيمة التي تُرجع إذا كانت قيمة السمة مفقودة (غير مضبوطة). القيمة الافتراضية هي <see langword="null" />.<br/>            يُنصح باستخدام '.Value' للتمييز بين القيم 'غير المضبوطة' و '<see langword="null" />'. |

**Returns**

| نوع | وصف |
| :- | :- |
| object | مصفوفة جديدة تُنسخ إليها قيم السمات. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_7}


```
 get_values_list(attribute_name, separator, count) 
```

يحصل على قائمة القيم. نظير غير عام لـ List T GetValuesList

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | اسم السمة. |
| separator | string | سلسلة تُستخدم لفصل اسم السمة وقيمة الفهرس في التسلسل. |
| العدد | int | عدد القيم التي تُرجع (القيمة المفقودة تُملأ كـ null) |

**Returns**

| نوع | وصف |
| :- | :- |
| object | قائمة القيم للسمات التي تختلف أسماؤها حسب قيمة فهرس التسلسل. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_8}


```
 is_value_null(attribute_name) 
```

يحدد ما إذا كان السمة المحددة قد تم تعيينها صراحةً إلى القيمة <c>null</c>.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | اسم السمة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword="true" /> إذا كانت قيمة السمة <c>null</c>; وإلا، <see langword="false" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_9}


```
 is_value_set(attribute_name) 
```

يتحقق مما إذا كانت قيمة السمة مضبوطة في هذه الميزة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | اسم السمة. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword="true" /> إذا تم تعيين قيمة السمة المحددة; وإلا، <see langword="false" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_10}


```
 set_value(attribute_name, value) 
```

يضبط القيمة. نظير غير عام لـ void SetValue (string attributeName, T value)

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | اسم السمة. |
| القيمة | object | قيمة السمة. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_11}


```
 set_value_null(attribute_name) 
```

يضبط قيمة السمة إلى <c>null</c>.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | اسم السمة. |

### Method: set_values(values) {#set_values_values_12}


```
 set_values(values) 
```

يضبط قيمًا جديدة لجميع السمات.<br/>            كما يُنصح باستخدام طريقة [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) لتبسيط ضبط القيم في استدعاء واحد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| values | object | المصفوفة التي تحتوي على القيم الجديدة. |

**Returns**

| نوع | وصف |
| :- | :- |
| int | عدد قيم السمة المحددة. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_13}


```
 unset_value(attribute_name) 
```

يزيل قيمة السمة من هذه الميزة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | اسم السمة. |

