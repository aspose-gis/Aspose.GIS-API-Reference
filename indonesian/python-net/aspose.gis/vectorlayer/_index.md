---
title: "Kelas VectorLayer"
type: docs
weight: 4060
url: /id/python-net/aspose.gis/vectorlayer/
---

**Summary:** Represents a vector layer.<br/>            A vector layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.VectorLayer

**Inheritance:** FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Mengambil koleksi atribut khusus untuk fitur dalam [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| jumlah | int | r | Mengambil jumlah fitur dalam lapisan ini. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Mengambil [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) yang menginstansiasi lapisan ini. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Mendapatkan tipe geometri untuk lapisan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Mendapatkan sistem referensi spasial dari urutan fitur ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add(feature)](#add_feature_1) | Menambahkan fitur baru ke lapisan, jika didukung oleh [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [add(feature, style)](#add_feature_style_2) | Menambahkan fitur baru dengan gaya yang ditentukan ke lapisan, jika didukung oleh [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [as_in_memory()](#as_in_memory__3) | Buat klon lapisan dalam format InMemory. |
| [construct_feature()](#construct_feature__4) | Membuat (tetapi tidak menambahkan ke lapisan) fitur baru dengan atribut yang cocok dengan kumpulan atribut lapisan ini.<br/>            Setelah selesai mengatur data untuk fitur, gunakan [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) untuk menambahkan fitur ke lapisan. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Mengonversi lapisan ke format lain. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Mengonversi lapisan ke format lain. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Mengonversi lapisan ke format lain. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Mengonversi lapisan ke format lain. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Menyalin atribut dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) lain ke yang ini. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Menyalin atribut dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) lain ke yang ini. |
| [create(path, driver)](#create_path_driver_11) | Membuat lapisan dan membukanya untuk menambahkan fitur baru. |
| [create(path, driver)](#create_path_driver_12) | Membuat lapisan dan membukanya untuk menambahkan fitur baru. |
| [create(path, driver, options)](#create_path_driver_options_13) | Membuat lapisan dan membukanya untuk menambahkan fitur baru. |
| [create(path, driver, options)](#create_path_driver_options_14) | Membuat lapisan dan membukanya untuk menambahkan fitur baru. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Membuat lapisan dan membukanya untuk menambahkan. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Membuat lapisan dan membukanya untuk menambahkan. |
| [get_extent()](#get_extent__19) | Mendapatkan batas spasial lapisan ini. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Melakukan intersect lapisan dengan lapisan saat ini berdasarkan geometri. |
| [join(layer, options)](#join_layer_options_21) | Menggabungkan lapisan ke lapisan saat ini. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Menggabungkan lapisan ke lapisan saat ini berdasarkan geometri. |
| [nearest_to(point)](#nearest_to_point_23) | Mendapatkan fitur terdekat ke titik yang diberikan. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Mendapatkan fitur terdekat ke koordinat yang diberikan. |
| [open(path, driver)](#open_path_driver_25) | Buka lapisan untuk membaca. |
| [open(path, driver)](#open_path_driver_26) | Buka lapisan untuk membaca. |
| [open(path, driver, options)](#open_path_driver_options_27) | Buka lapisan untuk membaca. |
| [open(path, driver, options)](#open_path_driver_options_28) | Buka lapisan untuk membaca. |
| [remove_at(index)](#remove_at_index_29) | Hapus [Feature](/psd/python-net/aspose.gis/feature/) pada indeks yang ditentukan. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Ganti [Feature](/psd/python-net/aspose.gis/feature/) pada indeks yang ditentukan. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Menyimpan urutan fitur ke lapisan. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Menyimpan urutan fitur ke lapisan. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Menyimpan urutan fitur ke lapisan. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Menyimpan urutan fitur ke lapisan. |
| [split_to()](#split_to__35) | Membagi fitur berdasarkan tipe geometri. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Memuat indeks atribut untuk mempercepat penyaringan berdasarkan nilai atribut dalam metode filter seperti Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Jika indeks tidak ada, buat terlebih dahulu. Gunakan <paramref name="forceRebuild" /> untuk memaksa pembuatan ulang indeks. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Memuat indeks atribut untuk mempercepat penyaringan berdasarkan nilai atribut dalam metode filter seperti Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Jika indeks tidak ada, buat terlebih dahulu. Gunakan <paramref name="forceRebuild" /> untuk memaksa pembuatan ulang indeks. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Memuat indeks spasial untuk mempercepat penyaringan berdasarkan nilai atribut dalam metode filter seperti Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            dan Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Jika indeks tidak ada, buat terlebih dahulu. Gunakan <paramref name="forceRebuild" /> untuk memaksa pembuatan ulang indeks. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Memuat indeks spasial untuk mempercepat penyaringan berdasarkan nilai atribut dalam metode filter seperti Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            dan Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Jika indeks tidak ada, buat terlebih dahulu. Gunakan <paramref name="forceRebuild" /> untuk memaksa pembuatan ulang indeks. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Memilih fitur dengan nilai atribut yang sama dengan nilai yang diberikan. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Memilih fitur dengan nilai atribut lebih besar dari nilai yang diberikan. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Memilih fitur dengan nilai atribut lebih besar atau sama dengan nilai yang diberikan. |
| [where_intersects(extent)](#where_intersects_extent_43) | Menyaring fitur berdasarkan cakupan. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Menyaring fitur berdasarkan geometri yang diberikan. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Menyaring fitur berdasarkan gabungan semua geometri dalam urutan fitur lainnya. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Memilih fitur dengan nilai atribut tidak sama dengan nilai yang diberikan. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Memilih fitur dengan atribut tidak sama dengan null. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Memilih fitur dengan atribut sama dengan null. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Memilih fitur dengan atribut yang diatur. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Memilih fitur dengan nilai atribut lebih kecil daripada nilai yang diberikan. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Memilih fitur dengan nilai atribut lebih kecil atau sama dengan nilai yang diberikan. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Memilih fitur dimana atribut yang ditentukan tidak diatur. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Menambahkan fitur baru ke lapisan, jika didukung oleh [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Fitur yang akan ditambahkan. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Menambahkan fitur baru dengan gaya yang ditentukan ke lapisan, jika didukung oleh [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Fitur yang akan ditambahkan. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | Gaya fitur. Gunakan <see langword="null" /> untuk menunjukkan gaya yang hilang. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Buat klon lapisan dalam format InMemory.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan InMemory. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Membuat (tetapi tidak menambahkan ke lapisan) fitur baru dengan atribut yang cocok dengan kumpulan atribut lapisan ini.<br/>            Setelah selesai mengatur data untuk fitur, gunakan [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) untuk menambahkan fitur ke lapisan.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Fitur baru. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Mengonversi lapisan ke format lain.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_path | string | Jalur ke lapisan yang akan dikonversi. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pengandar format untuk lapisan sumber. |
| destination_path | string | Jalur ke lapisan yang akan dibuat sebagai hasil konversi. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pengandar format untuk lapisan tujuan. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Mengonversi lapisan ke format lain.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke lapisan yang akan dikonversi. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pengandar format untuk lapisan sumber. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke lapisan yang akan dibuat sebagai hasil konversi. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pengandar format untuk lapisan tujuan. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Mengonversi lapisan ke format lain.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_path | string | Jalur ke lapisan yang akan dikonversi. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pengandar format untuk lapisan sumber. |
| destination_path | string | Jalur ke lapisan yang akan dibuat sebagai hasil konversi. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pengandar format untuk lapisan tujuan. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Opsi untuk prosedur konversi. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Mengonversi lapisan ke format lain.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke lapisan yang akan dikonversi. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pengandar format untuk lapisan sumber. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke lapisan yang akan dibuat sebagai hasil konversi. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pengandar format untuk lapisan tujuan. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Opsi untuk prosedur konversi. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Menyalin atribut dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) lain ke yang ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Urutan fitur untuk menyalin atribut darinya. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Menyalin atribut dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) lain ke yang ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Urutan fitur untuk menyalin atribut darinya. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | Sebuah instance dari [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) khusus yang akan memproses atribut satu per satu. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Membuat lapisan dan membukanya untuk menambahkan fitur baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan hanya-tulis. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Membuat lapisan dan membukanya untuk menambahkan fitur baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan hanya-tulis. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Membuat lapisan dan membukanya untuk menambahkan fitur baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan hanya-tulis. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Membuat lapisan dan membukanya untuk menambahkan fitur baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan hanya-tulis. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Membuat lapisan dan membukanya untuk menambahkan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah instance dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Mendapatkan batas spasial lapisan ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Batas spasial lapisan ini. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Melakukan intersect lapisan dengan lapisan saat ini berdasarkan geometri.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan untuk dipotong. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan baru sebagai hasil perpotongan dua lapisan. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Menggabungkan lapisan ke lapisan saat ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan untuk digabungkan. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Parameter penggabungan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan baru sebagai hasil penggabungan dua lapisan. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Menggabungkan lapisan ke lapisan saat ini berdasarkan geometri.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan untuk digabungkan. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Parameter penggabungan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan baru sebagai hasil penggabungan dua lapisan. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Mendapatkan fitur terdekat ke titik yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Titik. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Fitur terdekat ke titik yang diberikan. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Mendapatkan fitur terdekat ke koordinat yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | double | X dari koordinat. |
| y | double | Y dari koordinat. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Fitur terdekat ke koordinat yang diberikan. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Buka lapisan untuk membaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan hanya-baca. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Buka lapisan untuk membaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan hanya-baca. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Buka lapisan untuk membaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan hanya-baca. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Buka lapisan untuk membaca.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver yang akan digunakan. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opsi khusus driver. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Sebuah lapisan hanya-baca. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Hapus [Feature](/psd/python-net/aspose.gis/feature/) pada indeks yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks fitur. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Ganti [Feature](/psd/python-net/aspose.gis/feature/) pada indeks yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks fitur. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Fitur yang akan diatur. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Menyimpan urutan fitur ke lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| destination_path | string | Jalur ke lapisan output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver format untuk lapisan output. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Menyimpan urutan fitur ke lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke lapisan output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver format untuk lapisan output. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

Menyimpan urutan fitur ke lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| destination_path | string | Jalur ke lapisan output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver format untuk lapisan output. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opsi untuk prosedur penyimpanan. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

Menyimpan urutan fitur ke lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke lapisan output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver format untuk lapisan output. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opsi untuk prosedur penyimpanan. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Membagi fitur berdasarkan tipe geometri.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Lapisan dengan tipe geometri yang sama. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Memuat indeks atribut untuk mempercepat penyaringan berdasarkan nilai atribut dalam metode filter seperti Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Jika indeks tidak ada, buat terlebih dahulu. Gunakan <paramref name="forceRebuild" /> untuk memaksa pembuatan ulang indeks.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index_path | string | Jalur ke berkas indeks. |
| attribute_name | string | Nama atribut untuk membangun indeks. |
| force_rebuild | bool | Apakah akan membuat ulang indeks meskipun sudah ada. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Memuat indeks atribut untuk mempercepat penyaringan berdasarkan nilai atribut dalam metode filter seperti Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Jika indeks tidak ada, buat terlebih dahulu. Gunakan <paramref name="forceRebuild" /> untuk memaksa pembuatan ulang indeks.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke berkas indeks. |
| attribute_name | string | Nama atribut untuk membangun indeks. |
| force_rebuild | bool | Apakah akan membuat ulang indeks meskipun sudah ada. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Memuat indeks spasial untuk mempercepat penyaringan berdasarkan nilai atribut dalam metode filter seperti Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            dan Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Jika indeks tidak ada, buat terlebih dahulu. Gunakan <paramref name="forceRebuild" /> untuk memaksa pembuatan ulang indeks.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index_path | string | Jalur ke berkas indeks. |
| force_rebuild | bool | Apakah akan membuat ulang indeks meskipun sudah ada. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Memuat indeks spasial untuk mempercepat penyaringan berdasarkan nilai atribut dalam metode filter seperti Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            dan Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Jika indeks tidak ada, buat terlebih dahulu. Gunakan <paramref name="forceRebuild" /> untuk memaksa pembuatan ulang indeks.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke berkas indeks. |
| force_rebuild | bool | Apakah akan membuat ulang indeks meskipun sudah ada. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

Memilih fitur dengan nilai atribut yang sama dengan nilai yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |
| nilai | object | Nilai untuk dibandingkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut sama dengan nilai yang diberikan. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

Memilih fitur dengan nilai atribut lebih besar dari nilai yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |
| nilai | object | Nilai untuk dibandingkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut lebih besar dari nilai yang diberikan. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

Memilih fitur dengan nilai atribut lebih besar atau sama dengan nilai yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |
| nilai | object | Nilai untuk dibandingkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut lebih besar atau sama dengan nilai yang diberikan. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

Menyaring fitur berdasarkan cakupan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filter rentang. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur yang berpotongan dengan geometri yang diberikan. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

Menyaring fitur berdasarkan geometri yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filter geometri. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur yang berpotongan dengan geometri yang diberikan. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

Menyaring fitur berdasarkan gabungan semua geometri dalam urutan fitur lainnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Urutan fitur lainnya. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur yang berpotongan dengan gabungan semua geometri dalam urutan fitur lainnya. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

Memilih fitur dengan nilai atribut tidak sama dengan nilai yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |
| nilai | object | Nilai untuk dibandingkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut tidak sama dengan nilai yang diberikan. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

Memilih fitur dengan atribut tidak sama dengan null.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut tidak sama dengan null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

Memilih fitur dengan atribut sama dengan null.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut sama dengan null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

Memilih fitur dengan atribut yang diatur.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut yang diatur. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

Memilih fitur dengan nilai atribut lebih kecil daripada nilai yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |
| nilai | object | Nilai untuk dibandingkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut lebih kecil daripada nilai yang diberikan. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

Memilih fitur dengan nilai atribut lebih kecil atau sama dengan nilai yang diberikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |
| nilai | object | Nilai untuk dibandingkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut lebih kecil atau sama dengan nilai yang diberikan. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

Memilih fitur dimana atribut yang ditentukan tidak diatur.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Atribut untuk difilter. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Fitur dengan nilai atribut yang tidak diatur. |


