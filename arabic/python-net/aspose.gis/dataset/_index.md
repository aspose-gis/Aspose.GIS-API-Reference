---
title: "فئة Dataset"
type: docs
weight: 590
url: /ar/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا مجموعة البيانات يمكنها إنشاء طبقات متجهية. |
| can_remove_layers | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا مجموعة البيانات يمكنها إزالة طبقات متجهية. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | يحصل على [Dataset.driver](/psd/python-net/aspose.gis/dataset/) الذي أنشأ مجموعة البيانات هذه. |
| layers_count | int | r | يحصل على عدد الطبقات في مجموعة البيانات هذه. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | ينشئ مجموعة بيانات. |
| [create(path, driver)](#create_path_driver_2) | ينشئ مجموعة بيانات. |
| [create(path, driver, options)](#create_path_driver_options_3) | ينشئ مجموعة بيانات. |
| [create(path, driver, options)](#create_path_driver_options_4) | ينشئ مجموعة بيانات. |
| [create_layer()](#create_layer__5) | ينشئ طبقة متجهة جديدة ويفتحها للإلحاق. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | ينشئ طبقة متجهة جديدة بالاسم المحدد ويفتحها للإلحاق. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | ينشئ طبقة متجهة جديدة بالاسم المحدد ويفتحها للإلحاق. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | ينشئ طبقة متجهة جديدة ويفتحها للإلحاق. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | ينشئ طبقة متجهة جديدة ويفتحها للإلحاق. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | يفتح الطبقة بالاسم المحدد للتعديل. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | يفتح الطبقة بالاسم المحدد للتعديل. |
| [get_layer_name(index)](#get_layer_name_index_12) | يحصل على اسم الطبقة في الفهرس المحدد. |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | تحقق مما إذا كان مجموعة البيانات الحالية تحتوي على طبقة بالاسم المحدد |
| [open(path, driver)](#open_path_driver_14) | يفتح مجموعة البيانات. |
| [open(path, driver)](#open_path_driver_15) | يفتح مجموعة البيانات. |
| [open(path, driver, options)](#open_path_driver_options_16) | يفتح مجموعة البيانات. |
| [open(path, driver, options)](#open_path_driver_options_17) | يفتح مجموعة البيانات. |
| [open_layer(name, options)](#open_layer_name_options_18) | يفتح الطبقة بالاسم المحدد للقراءة. |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | يفتح الطبقة في الفهرس المحدد للقراءة. |
| [remove_layer(name)](#remove_layer_name_20) | يزيل الطبقة المتجهة بالاسم المحدد. |
| [remove_layer_at(index)](#remove_layer_at_index_21) | يزيل الطبقة المتجهة في الفهرس المحدد. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | إعادة تسمية الطبقة في مجموعة البيانات |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

ينشئ طبقة متجهة جديدة ويفتحها للإلحاق.

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوحة للكتابة. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

ينشئ طبقة متجهة جديدة بالاسم المحدد ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للطبقة الجديدة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوحة للكتابة. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

ينشئ طبقة متجهة جديدة بالاسم المحدد ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للطبقة الجديدة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوحة للكتابة. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

ينشئ طبقة متجهة جديدة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للطبقة الجديدة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوحة للكتابة. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

ينشئ طبقة متجهة جديدة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للطبقة الجديدة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوحة للكتابة. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

يفتح الطبقة بالاسم المحدد للتعديل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة للتعديل. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للأشكال الهندسية الجديدة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | الطبقة المفتوحة للتعديل. |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

يفتح الطبقة بالاسم المحدد للتعديل.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس الطبقة للتعديل. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للأشكال الهندسية الجديدة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | الطبقة المفتوحة للتعديل. |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

يحصل على اسم الطبقة في الفهرس المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس الطبقة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| string | اسم الطبقة. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

تحقق مما إذا كان مجموعة البيانات الحالية تحتوي على طبقة بالاسم المحدد

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | <see langword=\"true\" />, إذا كان مجموعة البيانات تحتوي على طبقة بهذا الاسم؛ وإلا، <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

يفتح الطبقة بالاسم المحدد للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة للفتح. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | الطبقة المفتوحة للقراءة. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

يفتح الطبقة في الفهرس المحدد للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس الطبقة للفتح. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | الطبقة المفتوحة للقراءة. |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

يزيل الطبقة المتجهة بالاسم المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

يزيل الطبقة المتجهة في الفهرس المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| index | int | فهرس الطبقة |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

إعادة تسمية الطبقة في مجموعة البيانات

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| current_name | string | الاسم الحالي للطبقة |
| new_name | string | اسم جديد للطبقة |

