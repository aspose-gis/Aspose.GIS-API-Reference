---
title: "Dataset Sınıfı"
type: docs
weight: 590
url: /tr/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Bu veri kümesinin vektör katmanları oluşturup oluşturamayacağını gösteren bir değeri alır. |
| can_remove_layers | bool | r | Bu veri kümesinin vektör katmanlarını kaldırıp kaldıramayacağını gösteren bir değeri alır. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Bu veri kümesini örnekleyen [Dataset.driver](/psd/python-net/aspose.gis/dataset/) öğesini alır. |
| layers_count | int | r | Bu veri kümesindeki katman sayısını alır. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Bir veri kümesi oluşturur. |
| [create(path, driver)](#create_path_driver_2) | Bir veri kümesi oluşturur. |
| [create(path, driver, options)](#create_path_driver_options_3) | Bir veri kümesi oluşturur. |
| [create(path, driver, options)](#create_path_driver_options_4) | Bir veri kümesi oluşturur. |
| [create_layer()](#create_layer__5) | Yeni bir vektör katmanı oluşturur ve ekleme için açar. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Belirtilen adla yeni bir vektör katmanı oluşturur ve ekleme için açar. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Belirtilen adla yeni bir vektör katmanı oluşturur ve ekleme için açar. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Yeni bir vektör katmanı oluşturur ve ekleme için açar. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Yeni bir vektör katmanı oluşturur ve ekleme için açar. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Belirtilen adla katmanı düzenleme için açar. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Belirtilen adla katmanı düzenleme için açar. |
| [get_layer_name(index)](#get_layer_name_index_12) | Belirtilen indeksteki katmanın adını alır. |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | Geçerli veri kümesinin belirli bir ada sahip katmanı olup olmadığını denetler |
| [open(path, driver)](#open_path_driver_14) | Veri kümesini açar. |
| [open(path, driver)](#open_path_driver_15) | Veri kümesini açar. |
| [open(path, driver, options)](#open_path_driver_options_16) | Veri kümesini açar. |
| [open(path, driver, options)](#open_path_driver_options_17) | Veri kümesini açar. |
| [open_layer(name, options)](#open_layer_name_options_18) | Belirtilen adla katmanı okuma için açar. |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | Belirtilen indeksteki katmanı okuma için açar. |
| [remove_layer(name)](#remove_layer_name_20) | Belirtilen adla vektör katmanını kaldırır. |
| [remove_layer_at(index)](#remove_layer_at_index_21) | Belirtilen indeksteki vektör katmanını kaldırır. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | Veri kümesindeki katmanın adını değiştir |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Bir veri kümesi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Yeni bir vektör katmanı oluşturur ve ekleme için açar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yazma için açılmış bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Belirtilen adla yeni bir vektör katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Katmanın adı. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Açma seçenekleri. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Yeni katmanın uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yazma için açılmış bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Belirtilen adla yeni bir vektör katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Katmanın adı. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Yeni katmanın uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yazma için açılmış bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Yeni bir vektör katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Açma seçenekleri. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Yeni katmanın uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yazma için açılmış bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Yeni bir vektör katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Yeni katmanın uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yazma için açılmış bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Belirtilen adla katmanı düzenleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Düzenlenecek katmanın adı. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Açma seçenekleri. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Yeni geometriler için uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Düzenleme için açılmış katman. |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Belirtilen adla katmanı düzenleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | int | Düzenlenecek katmanın indeksi. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Açma seçenekleri. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Yeni geometriler için uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Düzenleme için açılmış katman. |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Belirtilen indeksteki katmanın adını alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | int | Katmanın indeksi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Katmanın adı. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

Geçerli veri kümesinin belirli bir ada sahip katmanı olup olmadığını denetler

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Katmanın adı |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" />, veri kümesinde bu ada sahip katman varsa; aksi takdirde, <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Veri kümesine yol. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Veri kümesini açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Veri kümesine yol. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Bir [Dataset](/psd/python-net/aspose.gis/dataset/) örneği. |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

Belirtilen adla katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Açılacak katmanın adı. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Açma seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Okuma için açılmış katman. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

Belirtilen indeksteki katmanı okuma için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | int | Açılacak katmanın indeksi. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Açma seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Okuma için açılmış katman. |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

Belirtilen adla vektör katmanını kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Katmanın adı |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

Belirtilen indeksteki vektör katmanını kaldırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | int | Katmanın indeksi |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

Veri kümesindeki katmanın adını değiştir

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| current_name | string | Katmanın mevcut adı |
| new_name | string | Katman için yeni ad |

