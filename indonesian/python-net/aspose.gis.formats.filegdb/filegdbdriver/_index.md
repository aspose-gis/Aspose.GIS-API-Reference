---
title: "FileGdbDriver Kelas"
type: docs
weight: 20
url: /id/python-net/aspose.gis.formats.filegdb/filegdbdriver/
---

**Summary:** A driver for the ESRI File Geodatabase format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

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
| [create_dataset(path, options)](#create_dataset_path_options_5) | Membuat sebuah dataset. |
| [create_dataset(path, options)](#create_dataset_path_options_6) | Membuat sebuah dataset. |
| [create_layer(path)](#create_layer_path_7) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path)](#create_layer_path_8) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, options)](#create_layer_path_options_9) | Membuat lapisan dan membukanya untuk menambahkan fitur baru. |
| [create_layer(path, options)](#create_layer_path_options_10) | Membuat lapisan dan membukanya untuk menambahkan fitur baru. |
| [create_layer(path, options)](#create_layer_path_options_11) | Membuat lapisan dan membukanya untuk menambahkan fitur baru. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_14) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_15) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_16) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_17) | Membuat lapisan dan membukanya untuk menambahkan. |
| [edit_layer(path, options)](#edit_layer_path_options_18) | Membuka lapisan untuk penyuntingan. |
| [edit_layer(path, options)](#edit_layer_path_options_19) | Membuka lapisan untuk penyuntingan. |
| [open_dataset(path)](#open_dataset_path_20) | Membuka dataset. |
| [open_dataset(path)](#open_dataset_path_21) | Membuka dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_22) | Membuka dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_23) | Membuka dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_24) | Membuka dataset. |
| [open_dataset(path, options)](#open_dataset_path_options_25) | Membuka dataset. |
| [open_layer(path)](#open_layer_path_26) | Membuka lapisan untuk dibaca. |
| [open_layer(path)](#open_layer_path_27) | Membuka lapisan untuk dibaca. |
| [open_layer(path, options)](#open_layer_path_options_28) | Membuka lapisan untuk dibaca. |
| [open_layer(path, options)](#open_layer_path_options_29) | Membuka lapisan untuk dibaca. |
| [open_layer(path, options)](#open_layer_path_options_30) | Membuka lapisan untuk dibaca. |
| [open_layer(path, options)](#open_layer_path_options_31) | Membuka lapisan untuk dibaca. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_32) | Menentukan, apakah sistem referensi spasial yang ditentukan didukung oleh driver. |


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
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opsi khusus driver. |

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


### Method: create_dataset(path, options) {#create_dataset_path_options_5}


```
 create_dataset(path, options) 
```

Membuat sebuah dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_6}


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


### Method: create_layer(path) {#create_layer_path_7}


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


### Method: create_layer(path) {#create_layer_path_8}


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


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

Membuat lapisan dan membukanya untuk menambahkan fitur baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

Membuat lapisan dan membukanya untuk menambahkan fitur baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_11}


```
 create_layer(path, options) 
```

Membuat lapisan dan membukanya untuk menambahkan fitur baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opsi khusus driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


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


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_14}


```
 create_layer(path, options, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opsi khusus driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_15}


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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_16}


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


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_17}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_18}


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


### Method: edit_layer(path, options) {#edit_layer_path_options_19}


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


### Method: open_dataset(path) {#open_dataset_path_20}


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


### Method: open_dataset(path) {#open_dataset_path_21}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_22}


```
 open_dataset(path, options) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke dataset. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_23}


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


### Method: open_dataset(path, options) {#open_dataset_path_options_24}


```
 open_dataset(path, options) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_25}


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


### Method: open_layer(path) {#open_layer_path_26}


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


### Method: open_layer(path) {#open_layer_path_27}


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


### Method: open_layer(path, options) {#open_layer_path_options_28}


```
 open_layer(path, options) 
```

Membuka lapisan untuk dibaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_29}


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


### Method: open_layer(path, options) {#open_layer_path_options_30}


```
 open_layer(path, options) 
```

Membuka lapisan untuk dibaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| options | [FileGdbOptions](/psd/python-net/aspose.gis.formats.filegdb/filegdboptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_31}


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


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_32}


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
| bool | Nilai boolean, yang menunjukkan apakah sistem referensi spasial yang ditentukan didukung oleh driver. |


