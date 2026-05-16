---
title: "GeoPackageDataset Kelas"
type: docs
weight: 10
url: /id/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | Membuat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | Mendapatkan nilai yang menunjukkan apakah dataset ini dapat membuat lapisan vektor. |
| can_remove_layers | bool | r | Mendapatkan nilai yang menunjukkan apakah dataset ini dapat menghapus lapisan vektor. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Mendapatkan [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) yang menginstansiasi dataset ini. |
| layers_count | int | r | Mendapatkan jumlah lapisan dalam dataset ini. |
| tile_layers_count | int | r | Mendapatkan jumlah lapisan ubin dalam dataset ini. |
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
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | Metode ini masih dalam pengembangan. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | Metode ini masih dalam pengembangan. |
| [get_layer_name(index)](#get_layer_name_index_12) | Mendapatkan nama lapisan pada indeks yang ditentukan. |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | Mendapatkan nama lapisan ubin pada indeks yang ditentukan. |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | Periksa apakah dataset saat ini memiliki lapisan dengan nama tertentu. |
| [open(path, driver)](#open_path_driver_15) | Membuka dataset. |
| [open(path, driver)](#open_path_driver_16) | Membuka dataset. |
| [open(path, driver, options)](#open_path_driver_options_17) | Membuka dataset. |
| [open(path, driver, options)](#open_path_driver_options_18) | Membuka dataset. |
| [open(path, options)](#open_path_options_19) | Metode pabrik untuk membuat dataset dari file gpkg. |
| [open_layer(name, options)](#open_layer_name_options_20) | Membuka lapisan dengan nama yang ditentukan untuk membaca. |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | Membuka lapisan pada indeks yang ditentukan untuk membaca. |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | Membuka lapisan pada indeks yang ditentukan untuk membaca. |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | Membuka lapisan ubin dengan nama yang ditentukan untuk dibaca. |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | Membuka lapisan ubin pada indeks yang ditentukan untuk dibaca. |
| [remove_layer(name)](#remove_layer_name_25) | Menghapus lapisan vektor dengan nama yang ditentukan. |
| [remove_layer_at(index)](#remove_layer_at_index_26) | Menghapus lapisan vektor pada indeks yang ditentukan. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | Mengganti nama lapisan dalam dataset |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Pengaturan terkait keunikan membaca file gpkg. |

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

Metode ini masih dalam pengembangan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama lapisan yang akan disunting. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi pembukaan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial untuk geometri baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

Metode ini masih dalam pengembangan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks lapisan yang akan disunting. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi pembukaan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial untuk geometri baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


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


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

Mendapatkan nama lapisan ubin pada indeks yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks lapisan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string | Nama lapisan. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


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


### Method: open(path, driver)  [static] {#open_path_driver_15}


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


### Method: open(path, driver)  [static] {#open_path_driver_16}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


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


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


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


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

Metode pabrik untuk membuat dataset dari file gpkg.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file gpkg. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Pengaturan terkait keunikan membaca file gpkg. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


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


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


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


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

Membuka lapisan pada indeks yang ditentukan untuk membaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks lapisan yang akan dibuka. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opsi pembukaan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan yang dibuka untuk membaca. |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

Membuka lapisan ubin dengan nama yang ditentukan untuk dibaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama lapisan yang akan dibuka. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opsi pembukaan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | Lapisan ubin dibuka untuk dibaca. |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

Membuka lapisan ubin pada indeks yang ditentukan untuk dibaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks lapisan yang akan dibuka. |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | Opsi pembukaan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

Menghapus lapisan vektor dengan nama yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama lapisan |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

Menghapus lapisan vektor pada indeks yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks lapisan |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

Mengganti nama lapisan dalam dataset

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| current_name | string | Nama saat ini dari lapisan |
| new_name | string | Nama baru untuk lapisan |

