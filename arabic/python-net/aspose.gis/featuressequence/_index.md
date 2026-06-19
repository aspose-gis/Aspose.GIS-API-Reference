---
title: "FeaturesSequence Class"
type: docs
weight: 870
url: /ar/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | يحصل على مجموعة السمات المخصصة للميزات في هذا [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | يحصل على نظام الإحداثيات المكانية لتسلسل الميزات هذا. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_extent()](#get_extent__1) | يحصل على الامتداد المكاني لهذه الطبقة. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | يحفظ تسلسل الميزات إلى الطبقة. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | يحفظ تسلسل الميزات إلى الطبقة. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | يحفظ تسلسل الميزات إلى الطبقة. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | يحفظ تسلسل الميزات إلى الطبقة. |
| [split_to()](#split_to__6) | تقسيم الميزات حسب نوع الهندسة. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | يختار الميزات التي تكون قيمة السمة فيها مساوية للقيمة المقدمة. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | يختار الميزات التي تكون قيمة السمة فيها أكبر من القيمة المقدمة. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | يختار الميزات التي تكون قيمة السمة فيها أكبر أو مساوية للقيمة المقدمة. |
| [where_intersects(extent)](#where_intersects_extent_10) | يقوم بتصفية المعالم بناءً على النطاق. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | يقوم بتصفية المعالم بناءً على الهندسة المقدمة. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | يقوم بتصفية المعالم بناءً على اتحاد جميع الهندسات في تسلسل المعالم الأخرى. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | يختار المعالم التي قيمة الخاصية فيها لا تساوي القيمة المقدمة. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | يختار المعالم التي الخاصية فيها لا تساوي null. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | يختار المعالم التي الخاصية فيها تساوي null. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | يختار المعالم التي تم تعيين الخاصية لها. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | يختار المعالم التي قيمة الخاصية فيها أصغر من القيمة المقدمة. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | يختار المعالم التي قيمة الخاصية فيها أصغر أو تساوي القيمة المقدمة. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | يختار المعالم التي الخاصية المحددة لم يتم تعيينها. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

يحصل على الامتداد المكاني لهذه الطبقة.

**Returns**

| نوع | وصف |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | نطاق مكاني لهذه الطبقة. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

يحفظ تسلسل الميزات إلى الطبقة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| destination_path | string | المسار إلى طبقة الإخراج. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة لطبقة الإخراج. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

يحفظ تسلسل الميزات إلى الطبقة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى طبقة الإخراج. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة لطبقة الإخراج. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

يحفظ تسلسل الميزات إلى الطبقة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| destination_path | string | المسار إلى طبقة الإخراج. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة لطبقة الإخراج. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | خيارات عملية الحفظ. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

يحفظ تسلسل الميزات إلى الطبقة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى طبقة الإخراج. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | برنامج تشغيل الصيغة لطبقة الإخراج. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | خيارات عملية الحفظ. |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

تقسيم الميزات حسب نوع الهندسة.

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | طبقات بنفس نوع الهندسة. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

يختار الميزات التي تكون قيمة السمة فيها مساوية للقيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | عناصر ذات قيمة السمة مساوية للقيمة المقدمة. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

يختار الميزات التي تكون قيمة السمة فيها أكبر من القيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | عناصر ذات قيمة السمة أكبر من القيمة المقدمة. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

يختار الميزات التي تكون قيمة السمة فيها أكبر أو مساوية للقيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | عناصر ذات قيمة السمة أكبر أو مساوية للقيمة المقدمة. |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

يقوم بتصفية المعالم بناءً على النطاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | تصفية النطاق. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي تتقاطع مع الهندسة المقدمة. |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

يقوم بتصفية المعالم بناءً على الهندسة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | تصفية الهندسة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي تتقاطع مع الهندسة المقدمة. |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

يقوم بتصفية المعالم بناءً على اتحاد جميع الهندسات في تسلسل المعالم الأخرى.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | تسلسل العناصر الأخرى. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي تتقاطع مع اتحاد جميع الهندسات في تسلسل العناصر الأخرى. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

يختار المعالم التي قيمة الخاصية فيها لا تساوي القيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها لا تساوي القيمة المقدمة. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

يختار المعالم التي الخاصية فيها لا تساوي null.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها لا تساوي null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

يختار المعالم التي الخاصية فيها تساوي null.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها تساوي null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

يختار المعالم التي تم تعيين الخاصية لها.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي لديها قيمة خاصية محددة. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

يختار المعالم التي قيمة الخاصية فيها أصغر من القيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها أصغر من القيمة المقدمة. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

يختار المعالم التي قيمة الخاصية فيها أصغر أو تساوي القيمة المقدمة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |
| القيمة | object | القيمة للمقارنة بها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها أصغر أو تساوي القيمة المقدمة. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

يختار المعالم التي الخاصية المحددة لم يتم تعيينها.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| attribute_name | string | السمة للتصفية حسبها. |

**Returns**

| نوع | وصف |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | العناصر التي قيمة الخاصية فيها غير محددة. |


