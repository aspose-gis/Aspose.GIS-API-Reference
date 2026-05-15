---
title: "فئة MapInfoTabDriver"
type: docs
weight: 10
url: /ar/python-net/aspose.gis.formats.mapinfotab/mapinfotabdriver/
---

**Summary:** A driver for the MapInfo Tab format.

**Module:** [aspose.gis.formats.mapinfotab](/psd/python-net/aspose.gis.formats.mapinfotab/)

**Full Name:** aspose.gis.formats.mapinfotab.MapInfoTabDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

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
| [create_layer(path, options)](#create_layer_path_options_7) | يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة. |
| [create_layer(path, options)](#create_layer_path_options_8) | يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة. |
| [create_layer(path, options)](#create_layer_path_options_9) | يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة. |
| [create_layer(path, options)](#create_layer_path_options_10) | يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | ينشئ الطبقة ويفتحها للإلحاق. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | ينشئ الطبقة ويفتحها للإلحاق. |
| [edit_layer(path, options)](#edit_layer_path_options_16) | يفتح طبقة للتحرير. |
| [edit_layer(path, options)](#edit_layer_path_options_17) | يفتح طبقة للتحرير. |
| [open_dataset(path)](#open_dataset_path_18) | يفتح مجموعة البيانات. |
| [open_dataset(path)](#open_dataset_path_19) | يفتح مجموعة البيانات. |
| [open_dataset(path, options)](#open_dataset_path_options_20) | يفتح مجموعة البيانات. |
| [open_dataset(path, options)](#open_dataset_path_options_21) | يفتح مجموعة البيانات. |
| [open_layer(path)](#open_layer_path_22) | يفتح الطبقة للقراءة. |
| [open_layer(path)](#open_layer_path_23) | يفتح الطبقة للقراءة. |
| [open_layer(path, options)](#open_layer_path_options_24) | يفتح طبقة للقراءة. |
| [open_layer(path, options)](#open_layer_path_options_25) | يفتح طبقة للقراءة. |
| [open_layer(path, options)](#open_layer_path_options_26) | يفتح طبقة للقراءة. |
| [open_layer(path, options)](#open_layer_path_options_27) | يفتح طبقة للقراءة. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_28) | يحدد ما إذا كان نظام الإسناد المكاني المحدد مدعومًا من قبل السائق. |


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

يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |
| options | [MapInfoTabOptions](/psd/python-net/aspose.gis.formats.mapinfotab/mapinfotaboptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| options | [MapInfoTabOptions](/psd/python-net/aspose.gis.formats.mapinfotab/mapinfotaboptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة.

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


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| options | [MapInfoTabOptions](/psd/python-net/aspose.gis.formats.mapinfotab/mapinfotaboptions) | خيارات خاصة بالمشغل. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | نظام الإسناد المكاني. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

يقوم بإنشاء طبقة ويفتحها لإضافة ميزات جديدة.

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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


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


### Method: open_dataset(path) {#open_dataset_path_18}


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


### Method: open_dataset(path) {#open_dataset_path_19}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_20}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


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


### Method: open_layer(path) {#open_layer_path_22}


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


### Method: open_layer(path) {#open_layer_path_23}


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


### Method: open_layer(path, options) {#open_layer_path_options_24}


```
 open_layer(path, options) 
```

يفتح طبقة للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |
| options | [MapInfoTabOptions](/psd/python-net/aspose.gis.formats.mapinfotab/mapinfotaboptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

يفتح طبقة للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

يفتح طبقة للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | المسار إلى الملف. |
| options | [MapInfoTabOptions](/psd/python-net/aspose.gis.formats.mapinfotab/mapinfotaboptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

يفتح طبقة للقراءة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string | المسار إلى الملف. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | خيارات خاصة بالمشغل. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | مثال على [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_28}


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
| bool | قيمة منطقية، تشير إلى ما إذا كان نظام الإسناد المكاني المحدد مدعومًا من قبل السائق. |


