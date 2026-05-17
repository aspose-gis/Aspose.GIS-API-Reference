---
title: "GeoPackageDriver Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.gis.formats.geopackage/geopackagedriver/
---

**Summary:** A driver for the GPKG file format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeoPackageDriver()](#GeoPackageDriver__1) | GeoPackageDriver sınıfının yeni bir örneğini başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Bu sürücünün veri kümeleri oluşturup oluşturamayacağını gösteren bir değer alır. |
| can_create_layers | bool | r | Bu sürücünün vektör katmanları oluşturup oluşturamayacağını gösteren bir değer alır. |
| can_open_datasets | bool | r | Bu sürücünün veri kümelerini açıp açamayacağını gösteren bir değer alır. |
| can_open_layers | bool | r | Bu sürücünün vektör katmanlarını açıp açamayacağını gösteren bir değer alır. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Bir veri kümesi oluşturur. |
| [create_dataset(path)](#create_dataset_path_2) | Bir veri kümesi oluşturur. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Bir veri kümesi oluşturur. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Bir veri kümesi oluşturur. |
| [create_layer(path)](#create_layer_path_5) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path)](#create_layer_path_6) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, options)](#create_layer_path_options_7) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, options)](#create_layer_path_options_8) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_9) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_10) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_11) | Katmanı oluşturur ve ekleme için açar. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_12) | Katmanı oluşturur ve ekleme için açar. |
| [edit_layer(path, options)](#edit_layer_path_options_13) | Bir katmanı düzenleme için açar. |
| [edit_layer(path, options)](#edit_layer_path_options_14) | Bir katmanı düzenleme için açar. |
| [open_dataset(path)](#open_dataset_path_15) | Veri kümesini açar. |
| [open_dataset(path)](#open_dataset_path_16) | Veri kümesini açar. |
| [open_dataset(path, options)](#open_dataset_path_options_17) | Veri kümesini açar. |
| [open_dataset(path, options)](#open_dataset_path_options_18) | Veri kümesini açar. |
| [open_dataset(path, options)](#open_dataset_path_options_19) | Veri kümesini açar. |
| [open_layer(path)](#open_layer_path_20) | Katmanı okuma için açar. |
| [open_layer(path)](#open_layer_path_21) | Katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_22) | Katmanı okuma için açar. |
| [open_layer(path, options)](#open_layer_path_options_23) | Katmanı okuma için açar. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_24) | Belirtilen uzamsal referans sisteminin sürücü tarafından desteklenip desteklenmediğini belirler. |


### Constructor: GeoPackageDriver() {#GeoPackageDriver__1}


```
 GeoPackageDriver() 
```

GeoPackageDriver sınıfının yeni bir örneğini başlatır.

### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_9}


```
 create_layer(path, options, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_10}


```
 create_layer(path, options, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_11}


```
 create_layer(path, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_12}


```
 create_layer(path, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: edit_layer(path, options) {#edit_layer_path_options_13}


```
 edit_layer(path, options) 
```

Bir katmanı düzenleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: edit_layer(path, options) {#edit_layer_path_options_14}


```
 edit_layer(path, options) 
```

Bir katmanı düzenleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_dataset(path) {#open_dataset_path_15}


```
 open_dataset(path) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_dataset(path) {#open_dataset_path_16}


```
 open_dataset(path) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_dataset(path, options) {#open_dataset_path_options_17}


```
 open_dataset(path, options) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_dataset(path, options) {#open_dataset_path_options_18}


```
 open_dataset(path, options) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_dataset(path, options) {#open_dataset_path_options_19}


```
 open_dataset(path, options) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_layer(path) {#open_layer_path_20}


```
 open_layer(path) 
```

Katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path) {#open_layer_path_21}


```
 open_layer(path) 
```

Katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path, options) {#open_layer_path_options_22}


```
 open_layer(path, options) 
```

Katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: open_layer(path, options) {#open_layer_path_options_23}


```
 open_layer(path, options) 
```

Katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_24}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Belirtilen uzamsal referans sisteminin sürücü tarafından desteklenip desteklenmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Boolean değer, belirtilen uzamsal referans sisteminin sürücü tarafından desteklenip desteklenmediğini gösterir.<br/>            <see langword="null" /> herhangi bir sürücü tarafından desteklenmiş sayılır. |


