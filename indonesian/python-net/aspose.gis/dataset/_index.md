---
title: "Kelas Dataset"
type: docs
weight: 590
url: /id/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Mendapatkan nilai yang menunjukkan apakah dataset ini dapat membuat lapisan vektor. |
| can_remove_layers | bool | r | Mendapatkan nilai yang menunjukkan apakah dataset ini dapat menghapus lapisan vektor. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Mendapatkan [Dataset.driver](/psd/python-net/aspose.gis/dataset/) yang menginstansiasi dataset ini. |
| layers_count | int | r | Mendapatkan jumlah lapisan dalam dataset ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | Membuat sebuah dataset. |
| [create(path, driver)](#create_path_driver_2) | Membuat sebuah dataset. |
| [create(path, driver, options)](#create_path_driver_options_3) | Membuat sebuah dataset. |
| [create(path, driver, options)](#create_path_driver_options_4) | Membuat sebuah dataset. |
| [create_layer()](#create_layer__5) | Membuat lapisan vektor baru dan membukanya untuk menambahkan. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | Membuat lapisan vektor baru dengan nama yang ditentukan dan membukanya untuk menambahkan. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | Membuat lapisan vektor baru dengan nama yang ditentukan dan membukanya untuk menambahkan. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | Membuat lapisan vektor baru dan membukanya untuk menambahkan. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | Membuat lapisan vektor baru dan membukanya untuk menambahkan. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Membuka lapisan dengan nama yang ditentukan untuk penyuntingan. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Membuka lapisan dengan nama yang ditentukan untuk penyuntingan. |
| [get_layer_name(index)](#get_layer_name_index_12) | Mendapatkan nama lapisan pada indeks yang ditentukan. |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | Periksa apakah dataset saat ini memiliki lapisan dengan nama tertentu. |
| [open(path, driver)](#open_path_driver_14) | Membuka dataset. |
| [open(path, driver)](#open_path_driver_15) | Membuka dataset. |
| [open(path, driver, options)](#open_path_driver_options_16) | Membuka dataset. |
| [open(path, driver, options)](#open_path_driver_options_17) | Membuka dataset. |
| [open_layer(name, options)](#open_layer_name_options_18) | Membuka lapisan dengan nama yang ditentukan untuk membaca. |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | Membuka lapisan pada indeks yang ditentukan untuk membaca. |
| [remove_layer(name)](#remove_layer_name_20) | Menghapus lapisan vektor dengan nama yang ditentukan. |
| [remove_layer_at(index)](#remove_layer_at_index_21) | Menghapus lapisan vektor pada indeks yang ditentukan. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | Mengganti nama lapisan dalam dataset |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

Membuat sebuah dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

Membuat sebuah dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

Membuat sebuah dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

Membuat sebuah dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

Membuat lapisan vektor baru dan membukanya untuk menambahkan.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) dibuka untuk penulisan. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

Membuat lapisan vektor baru dengan nama yang ditentukan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama lapisan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi pembukaan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial lapisan baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) dibuka untuk penulisan. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

Membuat lapisan vektor baru dengan nama yang ditentukan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama lapisan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial lapisan baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) dibuka untuk penulisan. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

Membuat lapisan vektor baru dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi pembukaan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial lapisan baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) dibuka untuk penulisan. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

Membuat lapisan vektor baru dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial lapisan baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) dibuka untuk penulisan. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

Membuka lapisan dengan nama yang ditentukan untuk penyuntingan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama lapisan yang akan disunting. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi pembukaan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial untuk geometri baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan yang dibuka untuk penyuntingan. |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Membuka lapisan dengan nama yang ditentukan untuk penyuntingan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks lapisan yang akan disunting. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi pembukaan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial untuk geometri baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan yang dibuka untuk penyuntingan. |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

Mendapatkan nama lapisan pada indeks yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks lapisan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Nama lapisan. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

Periksa apakah dataset saat ini memiliki lapisan dengan nama tertentu.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama lapisan |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" />, jika dataset memiliki lapisan dengan nama ini; jika tidak, <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

Membuka dataset.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke dataset. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | Sebuah instance dari [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

Membuka lapisan dengan nama yang ditentukan untuk membaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama lapisan yang akan dibuka. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi pembukaan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan yang dibuka untuk membaca. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

Membuka lapisan pada indeks yang ditentukan untuk membaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks lapisan yang akan dibuka. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi pembukaan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan yang dibuka untuk membaca. |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

Menghapus lapisan vektor dengan nama yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama lapisan |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

Menghapus lapisan vektor pada indeks yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks lapisan |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

Mengganti nama lapisan dalam dataset

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| current_name | string | Nama saat ini dari lapisan |
| new_name | string | Nama baru untuk lapisan |

