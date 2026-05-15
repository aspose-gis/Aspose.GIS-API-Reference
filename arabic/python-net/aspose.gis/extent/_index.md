---
title: "فئة Extent"
type: docs
weight: 820
url: /ar/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [Extent()](#Extent__1) | ينشئ نسخة جديدة. |
| [Extent(srs)](#Extent_srs_2) | ينشئ نسخة جديدة. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | ينشئ نسخة جديدة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | مركز الـ extent. |
| الارتفاع | double | r | ارتفاع الـ extent. |
| is_valid | bool | r | يحدد ما إذا كان هذا [Extent](/psd/python-net/aspose.gis/extent/) صالحًا. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) المرتبط بهذا الـ extent.<br/>            يمكن أن يكون <see langword=\"null\" /> إذا كان [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) غير معروف.<br/>            استخدم Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            لتحويل الـ extent بين أنظمة الإسناد المكاني المختلفة. |
| العرض | double | r | عرض الـ extent. |
| x_max | double | r/w | القيمة القصوى لإحداثي X. |
| x_min | double | r/w | القيمة الدنيا لإحداثي X. |
| y_max | double | r/w | القيمة القصوى لإحداثي Y. |
| y_min | double | r/w | القيمة الدنيا لإحداثي Y. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [clone()](#clone__1) | ينسخ هذا الكائن. |
| [contains(extent)](#contains_extent_2) | يحدد ما إذا كان هذا النطاق يحتوي على الوسيط. |
| [contains(geometry)](#contains_geometry_3) | يحدد ما إذا كان هذا النطاق يحتوي على الوسيط. |
| [contains(x, y)](#contains_x_y_4) | يحدد ما إذا كان هذا النطاق يحتوي على إحداثي معرف بالوسائط. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | يعيد نطاقًا جديدًا في [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) المحدد الذي يحتوي على هذا النطاق. |
| [grow(extent)](#grow_extent_6) | يوسع هذا النطاق بحيث يشمل الوسيط. |
| [grow(x, y)](#grow_x_y_7) | يوسع هذا النطاق بحيث يشمل النقطة المحددة. |
| [grow_x(value)](#grow_x_value_8) | يوسع هذا النطاق على محور X بحيث يشمل القيمة المحددة. |
| [grow_y(value)](#grow_y_value_9) | يوسع هذا النطاق على محور Y بحيث يشمل القيمة المحددة. |
| [intersects(extent)](#intersects_extent_10) | يحدد ما إذا كان هذا النطاق يتقاطع مع الوسيط. |
| [intersects(geometry)](#intersects_geometry_11) | يحدد ما إذا كان هذا النطاق يتقاطع مع الوسيط. |
| normalize() | يبدل [Extent.x_min](/psd/python-net/aspose.gis/extent/) مع [Extent.x_max](/psd/python-net/aspose.gis/extent/) إذا كان [Extent.width](/psd/python-net/aspose.gis/extent/) سالبًا و<br/>            [Extent.y_min](/psd/python-net/aspose.gis/extent/) مع [Extent.y_max](/psd/python-net/aspose.gis/extent/) إذا كان [Extent.height](/psd/python-net/aspose.gis/extent/) سالبًا. |
| [to_polygon()](#to_polygon__12) | يحول هذا النطاق إلى مضلع مستطيل يمثلّه. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

ينشئ نسخة جديدة.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

ينشئ نسخة جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) المرتبط بهذا النطاق.<br/>            يمكن أن يكون <see langword=\"null\" /> للدلالة على أن SRS غير معروف. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

ينشئ نسخة جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x_min | double | القيمة الدنيا لـ X. |
| y_min | double | القيمة الدنيا لـ Y. |
| x_max | double | القيمة القصوى لـ X. |
| y_max | double | القيمة القصوى لـ Y. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) المرتبط بهذا النطاق.<br/>            يمكن أن يكون <see langword=\"null\" /> للدلالة على أن SRS غير معروف. |

### Method: clone() {#clone__1}


```
 clone() 
```

ينسخ هذا الكائن.

**Returns**

| نوع | الوصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | نسخة من هذه الحالة. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

يحدد ما إذا كان هذا النطاق يحتوي على الوسيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | نطاق آخر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | القيمة التي تشير إلى ما إذا كان هذا النطاق يحتوي على الوسيط. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

يحدد ما إذا كان هذا النطاق يحتوي على الوسيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | هندسة لاختبار الاحتواء. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | القيمة التي تشير إلى ما إذا كان هذا النطاق يحتوي على الوسيط. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

يحدد ما إذا كان هذا النطاق يحتوي على إحداثي معرف بالوسائط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | double | X للإحداثي. |
| y | double | Y للإحداثي. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | القيمة التي تشير إلى ما إذا كان الإحداثي داخل صندوق الحدود. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

يعيد نطاقًا جديدًا في [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) المحدد الذي يحتوي على هذا النطاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) للتحويل إليه. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | نتيجة تحويل هذا النطاق إلى نظام الإحداثيات المحدد. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

يوسع هذا النطاق بحيث يشمل الوسيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | نطاق آخر. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

يوسع هذا النطاق بحيث يشمل النقطة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| x | double | إحداثي X لتضمينه. |
| y | double | إحداثي Y لتضمينه. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

يوسع هذا النطاق على محور X بحيث يشمل القيمة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | double | القيمة لتضمينها. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

يوسع هذا النطاق على محور Y بحيث يشمل القيمة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| القيمة | double | القيمة لتضمينها. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

يحدد ما إذا كان هذا النطاق يتقاطع مع الوسيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | نطاق آخر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | القيمة، التي تشير إلى ما إذا كان هذا النطاق يتقاطع مع الوسيط. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

يحدد ما إذا كان هذا النطاق يتقاطع مع الوسيط.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | هندسة لاختبار التقاطع |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | القيمة، التي تشير إلى ما إذا كان هذا النطاق يتقاطع مع الوسيط. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

يحول هذا النطاق إلى مضلع مستطيل يمثلّه.

**Returns**

| نوع | الوصف |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | مضلع مستطيل [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) يمثل هذا النطاق. بالنسبة للنطاقات غير الصالحة<br/>            يتم إرجاع مضلع فارغ. |


