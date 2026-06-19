---
title: "فئة GeoPackageDataset"
type: docs
weight: 10
url: /ar/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | ينشئ مثلاً جديداً. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا مجموعة البيانات يمكنها إنشاء طبقات متجهية. |
| can_remove_layers | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا مجموعة البيانات يمكنها إزالة طبقات متجهية. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | يحصل على [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) الذي أنشأ هذه مجموعة البيانات. |
| layers_count | int | r | يحصل على عدد الطبقات في مجموعة البيانات هذه. |
| tile_layers_count | int | r | يحصل على عدد طبقات البلاط في مجموعة البيانات هذه. |
## **Methods**
| **Name** | **Description** |
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
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | هذه الطريقة لا تزال قيد التطوير. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | هذه الطريقة لا تزال قيد التطوير. |
| [get_layer_name(index)](#get_layer_name_index_12) | يحصل على اسم الطبقة في الفهرس المحدد. |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | يحصل على اسم طبقة البلاط عند الفهرس المحدد. |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | تحقق مما إذا كان مجموعة البيانات الحالية تحتوي على طبقة بالاسم المحدد |
| [open(path, driver)](#open_path_driver_15) | يفتح مجموعة البيانات. |
| [open(path, driver)](#open_path_driver_16) | يفتح مجموعة البيانات. |
| [open(path, driver, options)](#open_path_driver_options_17) | يفتح مجموعة البيانات. |
| [open(path, driver, options)](#open_path_driver_options_18) | يفتح مجموعة البيانات. |
| [open(path, options)](#open_path_options_19) | طريقة المصنع لإنشاء مجموعة بيانات من ملف gpkg. |
| [open_layer(name, options)](#open_layer_name_options_20) | يفتح الطبقة بالاسم المحدد للقراءة. |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | يفتح الطبقة في الفهرس المحدد للقراءة. |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | يفتح الطبقة في الفهرس المحدد للقراءة. |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | يفتح طبقة البلاط بالاسم المحدد للقراءة. |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | يفتح طبقة البلاط عند الفهرس المحدد للقراءة. |
| [remove_layer(name)](#remove_layer_name_25) | يزيل الطبقة المتجهة بالاسم المحدد. |
| [remove_layer_at(index)](#remove_layer_at_index_26) | يزيل الطبقة المتجهة في الفهرس المحدد. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | إعادة تسمية الطبقة في مجموعة البيانات |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

ينشئ مثلاً جديداً.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | مسار ملف gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | إعدادات تتعلق بخصوصيات قراءة ملف gpkg. |

### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

ينشئ طبقة متجهة جديدة ويفتحها للإلحاق.

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوح للكتابة. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

ينشئ طبقة متجهة جديدة بالاسم المحدد ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للطبقة الجديدة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوح للكتابة. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

ينشئ طبقة متجهة جديدة بالاسم المحدد ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للطبقة الجديدة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوح للكتابة. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

ينشئ طبقة متجهة جديدة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للطبقة الجديدة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوح للكتابة. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

ينشئ طبقة متجهة جديدة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للطبقة الجديدة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) مفتوح للكتابة. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

هذه الطريقة لا تزال قيد التطوير.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة للتحرير. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للأشكال الهندسية الجديدة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

هذه الطريقة لا تزال قيد التطوير.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس الطبقة للتحرير. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني للأشكال الهندسية الجديدة. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

يحصل على اسم الطبقة في الفهرس المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس الطبقة. |

**Returns**

| نوع | وصف |
| :- | :- |
| string | اسم الطبقة. |


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

يحصل على اسم طبقة البلاط عند الفهرس المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس الطبقة. |

**Returns**

| نوع | وصف |
| :- | :- |
| string | اسم الطبقة. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


```
 has_layer_with_name(name) 
```

تحقق مما إذا كان مجموعة البيانات الحالية تحتوي على طبقة بالاسم المحدد

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" />, إذا كانت مجموعة البيانات تحتوي على طبقة بهذا الاسم؛ وإلا، <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_16}


```
 open(path, driver) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


```
 open(path, driver, options) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | المشغل للاستخدام. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

طريقة المصنع لإنشاء مجموعة بيانات من ملف gpkg.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | مسار ملف gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | إعدادات تتعلق بخصوصيات قراءة ملف gpkg. |

**Returns**

| نوع | وصف |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


```
 open_layer(name, options) 
```

يفتح الطبقة بالاسم المحدد للقراءة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة للفتح. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | الطبقة المفتوحة للقراءة. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


```
 open_layer_at(index, options) 
```

يفتح الطبقة في الفهرس المحدد للقراءة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس الطبقة للفتح. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات الفتح. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | الطبقة المفتوحة للقراءة. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

يفتح الطبقة في الفهرس المحدد للقراءة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس الطبقة للفتح. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | خيارات الفتح. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | الطبقة المفتوحة للقراءة. |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

يفتح طبقة البلاط بالاسم المحدد للقراءة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة للفتح. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | خيارات الفتح. |

**Returns**

| نوع | وصف |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | تم فتح طبقة البلاط للقراءة. |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

يفتح طبقة البلاط عند الفهرس المحدد للقراءة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس الطبقة للفتح. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | خيارات الفتح. |

**Returns**

| نوع | وصف |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

يزيل الطبقة المتجهة بالاسم المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم الطبقة |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

يزيل الطبقة المتجهة في الفهرس المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الفهرس | int | فهرس الطبقة |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

إعادة تسمية الطبقة في مجموعة البيانات

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| current_name | string | الاسم الحالي للطبقة |
| new_name | string | اسم جديد للطبقة |

