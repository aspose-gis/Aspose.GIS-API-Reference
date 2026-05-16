---
title: "FeaturesSequence Kelas"
type: docs
weight: 870
url: /id/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Mengambil koleksi atribut khusus untuk fitur dalam [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Mendapatkan sistem referensi spasial dari urutan fitur ini. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_extent()](#get_extent__1) | Mendapatkan batas spasial lapisan ini. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | Menyimpan urutan fitur ke lapisan. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | Menyimpan urutan fitur ke lapisan. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | Menyimpan urutan fitur ke lapisan. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | Menyimpan urutan fitur ke lapisan. |
| [split_to()](#split_to__6) | Membagi fitur berdasarkan tipe geometri. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | Memilih fitur dengan nilai atribut yang sama dengan nilai yang diberikan. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | Memilih fitur dengan nilai atribut lebih besar dari nilai yang diberikan. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | Memilih fitur dengan nilai atribut lebih besar atau sama dengan nilai yang diberikan. |
| [where_intersects(extent)](#where_intersects_extent_10) | Menyaring fitur berdasarkan cakupan. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | Menyaring fitur berdasarkan geometri yang diberikan. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | Menyaring fitur berdasarkan gabungan semua geometri dalam urutan fitur lainnya. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | Memilih fitur dengan nilai atribut tidak sama dengan nilai yang diberikan. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | Memilih fitur dengan atribut tidak sama dengan null. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | Memilih fitur dengan atribut sama dengan null. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | Memilih fitur dengan atribut yang diatur. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | Memilih fitur dengan nilai atribut lebih kecil daripada nilai yang diberikan. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | Memilih fitur dengan nilai atribut lebih kecil atau sama dengan nilai yang diberikan. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | Memilih fitur dimana atribut yang ditentukan tidak diatur. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

Mendapatkan batas spasial lapisan ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Batas spasial lapisan ini. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

Menyimpan urutan fitur ke lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| destination_path | string | Jalur ke lapisan output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver format untuk lapisan output. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

Menyimpan urutan fitur ke lapisan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Jalur ke lapisan output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver format untuk lapisan output. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


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

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


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

### Method: split_to() {#split_to__6}


```
 split_to() 
```

Membagi fitur berdasarkan tipe geometri.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Lapisan dengan tipe geometri yang sama. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


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


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


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


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


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


### Method: where_intersects(extent) {#where_intersects_extent_10}


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


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


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


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


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


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


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


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


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


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


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


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


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


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


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


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


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


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


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


