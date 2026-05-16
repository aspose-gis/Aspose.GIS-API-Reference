---
title: "GeoPackageDriver Kelas"
type: docs
weight: 20
url: /id/python-net/aspose.gis.formats.geopackage/geopackagedriver/
---

**Summary:** A driver for the GPKG file format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GeoPackageDriver()](#GeoPackageDriver__1) | Menginisialisasi sebuah instance baru dari kelas GeoPackageDriver |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | Mendapatkan nilai yang menunjukkan apakah driver ini dapat membuat datasets. |
| can_create_layers | bool | r | Mendapatkan nilai yang menunjukkan apakah driver ini dapat membuat lapisan vektor. |
| can_open_datasets | bool | r | Mendapatkan nilai yang menunjukkan apakah driver ini dapat membuka datasets. |
| can_open_layers | bool | r | Mendapatkan nilai yang menunjukkan apakah driver ini dapat membuka lapisan vektor. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | Membuat sebuah dataset. |
| [create_dataset(path)](#create_dataset_path_2) | Membuat sebuah dataset. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | Membuat sebuah dataset. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | Membuat sebuah dataset. |
| [create_layer(path)](#create_layer_path_5) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path)](#create_layer_path_6) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, options)](#create_layer_path_options_7) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, options)](#create_layer_path_options_8) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_9) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_10) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_11) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_12) | Membuat lapisan dan membukanya untuk menambahkan. |
| [edit_layer(path, options)](#edit_layer_path_options_13) | Membuka lapisan untuk penyuntingan. |
| [edit_layer(path, options)](#edit_layer_path_options_14) | Membuka lapisan untuk penyuntingan. |
| [open_dataset(path)](#open_dataset_path_15) | Membuka dataset. |
| [open_dataset(path)](#open_dataset_path_16) | Membuka dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_17) | Membuka dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_18) | Membuka dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_19) | Membuka dataset. |
| [open_layer(path)](#open_layer_path_20) | Membuka lapisan untuk dibaca. |
| [open_layer(path)](#open_layer_path_21) | Membuka lapisan untuk dibaca. |
| [open_layer(path, options)](#open_layer_path_options_22) | Membuka lapisan untuk dibaca. |
| [open_layer(path, options)](#open_layer_path_options_23) | Membuka lapisan untuk dibaca. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_24) | Menentukan, apakah sistem referensi spasial yang ditentukan didukung oleh driver. |


### Constructor: GeoPackageDriver() {#GeoPackageDriver__1}


```
 GeoPackageDriver() 
```

Menginisialisasi sebuah instance baru dari kelas GeoPackageDriver

### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

Membuat sebuah dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke dataset. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

Membuat sebuah dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

Membuat sebuah dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

Membuat sebuah dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_9}


```
 create_layer(path, options, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_10}


```
 create_layer(path, options, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_11}


```
 create_layer(path, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_12}


```
 create_layer(path, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_13}


```
 edit_layer(path, options) 
```

Membuka lapisan untuk penyuntingan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_14}


```
 edit_layer(path, options) 
```

Membuka lapisan untuk penyuntingan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_dataset(path) {#open_dataset_path_15}


```
 open_dataset(path) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke dataset. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_16}


```
 open_dataset(path) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_17}


```
 open_dataset(path, options) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_18}


```
 open_dataset(path, options) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_19}


```
 open_dataset(path, options) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke dataset. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_20}


```
 open_layer(path) 
```

Membuka lapisan untuk dibaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_21}


```
 open_layer(path) 
```

Membuka lapisan untuk dibaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_22}


```
 open_layer(path, options) 
```

Membuka lapisan untuk dibaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_23}


```
 open_layer(path, options) 
```

Membuka lapisan untuk dibaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_24}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

Menentukan, apakah sistem referensi spasial yang ditentukan didukung oleh driver.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Nilai Boolean, yang menunjukkan apakah sistem referensi spasial yang ditentukan didukung oleh driver.<br/>            <see langword=\"null\" /> dianggap didukung oleh driver mana pun. |


