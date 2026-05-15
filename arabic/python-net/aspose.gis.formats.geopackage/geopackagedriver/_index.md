---
title: "فئة GeoPackageDriver"
type: docs
weight: 20
url: /ar/python-net/aspose.gis.formats.geopackage/geopackagedriver/
---

**Summary:** A driver for the GPKG file format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GeoPackageDriver()](#GeoPackageDriver__1) | ينشئ مثلاً جديداً من فئة GeoPackageDriver |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا السائق يمكنه إنشاء مجموعات البيانات. |
| can_create_layers | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا السائق يمكنه إنشاء طبقات المتجهات. |
| can_open_datasets | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا السائق يمكنه فتح مجموعات البيانات. |
| can_open_layers | bool | r | يحصل على قيمة تشير إلى ما إذا كان هذا السائق يمكنه فتح طبقات المتجهات. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | ينشئ مجموعة بيانات. |
| [create_dataset(path)](#create_dataset_path_2) | ينشئ مجموعة بيانات. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | ينشئ مجموعة بيانات. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | ينشئ مجموعة بيانات. |
| [create_layer(path)](#create_layer_path_5) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create_layer(path)](#create_layer_path_6) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create_layer(path, options)](#create_layer_path_options_7) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create_layer(path, options)](#create_layer_path_options_8) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_9) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_10) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_11) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_12) | ينشئ الطبقة ويفتحها للإلحاق. |
| [edit_layer(path, options)](#edit_layer_path_options_13) | يفتح طبقة للتحرير. |
| [edit_layer(path, options)](#edit_layer_path_options_14) | يفتح طبقة للتحرير. |
| [open_dataset(path)](#open_dataset_path_15) | يفتح مجموعة البيانات. |
| [open_dataset(path)](#open_dataset_path_16) | يفتح مجموعة البيانات. |
| [open_dataset(path, options)](#open_dataset_path_options_17) | يفتح مجموعة البيانات. |
| [open_dataset(path, options)](#open_dataset_path_options_18) | يفتح مجموعة البيانات. |
| [open_dataset(path, options)](#open_dataset_path_options_19) | يفتح مجموعة البيانات. |
| [open_layer(path)](#open_layer_path_20) | يفتح الطبقة للقراءة. |
| [open_layer(path)](#open_layer_path_21) | يفتح الطبقة للقراءة. |
| [open_layer(path, options)](#open_layer_path_options_22) | يفتح الطبقة للقراءة. |
| [open_layer(path, options)](#open_layer_path_options_23) | يفتح الطبقة للقراءة. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_24) | يحدد ما إذا كان نظام الإسناد المكاني المحدد مدعومًا من قبل السائق. |


### Constructor: GeoPackageDriver() {#GeoPackageDriver__1}


```
 GeoPackageDriver() 
```

ينشئ مثلاً جديداً من فئة GeoPackageDriver

### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى مجموعة البيانات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى مجموعة البيانات. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

ينشئ مجموعة بيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_9}


```
 create_layer(path, options, spatial_reference_system) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_10}


```
 create_layer(path, options, spatial_reference_system) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_11}


```
 create_layer(path, spatial_reference_system) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_12}


```
 create_layer(path, spatial_reference_system) 
```

ينشئ الطبقة ويفتحها للإلحاق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_13}


```
 edit_layer(path, options) 
```

يفتح طبقة للتحرير.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_14}


```
 edit_layer(path, options) 
```

يفتح طبقة للتحرير.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_15}


```
 open_dataset(path) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى مجموعة البيانات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_16}


```
 open_dataset(path) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_17}


```
 open_dataset(path, options) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_18}


```
 open_dataset(path, options) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى مجموعة البيانات. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_19}


```
 open_dataset(path, options) 
```

يفتح مجموعة البيانات.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى مجموعة البيانات. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | مثال على [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_20}


```
 open_layer(path) 
```

يفتح الطبقة للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_21}


```
 open_layer(path) 
```

يفتح الطبقة للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_22}


```
 open_layer(path, options) 
```

يفتح الطبقة للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_23}


```
 open_layer(path, options) 
```

يفتح الطبقة للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_24}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

يحدد ما إذا كان نظام الإسناد المكاني المحدد مدعومًا من قبل السائق.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | قيمة منطقية، تشير إلى ما إذا كان نظام الإحداثيات المكانية المحدد مدعومًا من قبل السائق.<br/>            <see langword=\"null\" /> يعتبر مدعومًا من أي سائق. |


