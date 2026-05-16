---
title: "Kelas Feature"
type: docs
weight: 830
url: /id/python-net/aspose.gis/feature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Mendapatkan atau mengatur geometri dari fitur.<br/>            Tidak boleh <see langword=\"null\" />, gunakan [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) untuk menunjukkan geometri yang hilang. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Menyalin nilai atribut dari fitur lain. |
| [get_value(attribute_name)](#get_value_attribute_name_2) | Mendapatkan nilai sebuah atribut. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_3) | Mendapatkan nilai dari sebuah atribut, atau [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) jika nilai belum diatur atau <c>null</c>. |
| [get_values(values, default_value)](#get_values_values_default_value_4) | Mengembalikan nilai untuk semua atribut dalam sebuah array. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_5) | Mengembalikan nilai untuk semua atribut dalam sebuah array. |
| [get_values_dump(default_value)](#get_values_dump_default_value_6) | Mengembalikan nilai untuk semua atribut dalam sebuah array.<br/>            Pertimbangkan untuk menggunakan metode Aspose.Gis.Feature.GetValues(int,System.Object) untuk menghindari alokasi memori tambahan. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_7) | Mendapatkan daftar nilai. Analogi non-generic dari List T GetValuesList |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_8) | Menentukan apakah atribut yang ditentukan telah secara eksplisit diatur ke nilai <c>null</c>. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_9) | Memeriksa apakah nilai atribut telah diatur dalam fitur ini. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_10) | Mengatur nilai. Analogi non-generic dari void SetValue (string attributeName, T value) |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_11) | Mengatur nilai atribut menjadi <c>null</c>. |
| [set_values(values)](#set_values_values_12) | Mengatur nilai baru untuk semua atribut.<br/>            Juga pertimbangkan untuk menggunakan metode [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) untuk mempermudah pengaturan nilai dalam satu panggilan. |
| [unset_value(attribute_name)](#unset_value_attribute_name_13) | Menghapus nilai atribut dari fitur ini. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Menyalin nilai atribut dari fitur lain.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | Fitur yang akan disalin nilainya. |

### Method: get_value(attribute_name) {#get_value_attribute_name_2}


```
 get_value(attribute_name) 
```

Mendapatkan nilai sebuah atribut.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Nama atribut. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| object | Nilai atribut. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_3}


```
 get_value_or_default(attribute_name, default_value) 
```

Mendapatkan nilai dari sebuah atribut, atau [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) jika nilai belum diatur atau <c>null</c>.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Nama atribut. |
| default_value | object | Nilai yang akan dikembalikan jika nilai atribut tidak ada. Nilai default adalah <see langword="null" />. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| object | Nilai atribut. |


### Method: get_values(values, default_value) {#get_values_values_default_value_4}


```
 get_values(values, default_value) 
```

Mengembalikan nilai untuk semua atribut dalam sebuah array.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| values | object |  |
| default_value | object | Nilai yang akan dikembalikan jika nilai atribut tidak ada (belum diatur). Nilai default adalah <see langword="null" />.<br/>            Pertimbangkan untuk menggunakan '.Value' untuk memisahkan nilai 'belum diatur' dan '<see langword="null" />' values. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Sejumlah atribut yang disalin. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_5}


```
 get_values(values_count, default_value) 
```

Mengembalikan nilai untuk semua atribut dalam sebuah array.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| values_count | int | Jumlah nilai. |
| default_value | object | Nilai yang akan dikembalikan jika nilai atribut tidak ada (belum diatur). Nilai default adalah <see langword="null" />.<br/>            Pertimbangkan untuk menggunakan '.Value' untuk memisahkan nilai 'belum diatur' dan '<see langword="null" />' values. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| object | Sejumlah atribut yang disalin. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_6}


```
 get_values_dump(default_value) 
```

Mengembalikan nilai untuk semua atribut dalam sebuah array.<br/>            Pertimbangkan untuk menggunakan metode Aspose.Gis.Feature.GetValues(int,System.Object) untuk menghindari alokasi memori tambahan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| default_value | object | Nilai yang akan dikembalikan jika nilai atribut tidak ada (belum diatur). Nilai default adalah <see langword="null" />.<br/>            Pertimbangkan untuk menggunakan '.Value' untuk memisahkan nilai 'belum diatur' dan '<see langword="null" />' values. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| object | Array baru yang akan menyalin nilai-nilai atribut. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_7}


```
 get_values_list(attribute_name, separator, count) 
```

Mendapatkan daftar nilai. Analogi non-generic dari List T GetValuesList

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Nama atribut. |
| separator | string | String yang digunakan untuk memisahkan nama atribut dan nilai indeks urutan. |
| jumlah | int | Jumlah nilai yang akan dikembalikan (nilai yang hilang diisi sebagai null) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| object | Daftar nilai atribut yang namanya berbeda berdasarkan nilai indeks urutan. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_8}


```
 is_value_null(attribute_name) 
```

Menentukan apakah atribut yang ditentukan telah secara eksplisit diatur ke nilai <c>null</c>.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Nama atribut. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword="true" /> jika nilai atribut adalah <c>null</c>; jika tidak, <see langword="false" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_9}


```
 is_value_set(attribute_name) 
```

Memeriksa apakah nilai atribut telah diatur dalam fitur ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Nama atribut. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword="true" /> jika nilai untuk atribut yang ditentukan telah diatur; jika tidak, <see langword="false" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_10}


```
 set_value(attribute_name, value) 
```

Mengatur nilai. Analogi non-generic dari void SetValue (string attributeName, T value)

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Nama atribut. |
| nilai | object | Nilai atribut. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_11}


```
 set_value_null(attribute_name) 
```

Mengatur nilai atribut menjadi <c>null</c>.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Nama atribut. |

### Method: set_values(values) {#set_values_values_12}


```
 set_values(values) 
```

Mengatur nilai baru untuk semua atribut.<br/>            Juga pertimbangkan untuk menggunakan metode [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) untuk mempermudah pengaturan nilai dalam satu panggilan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| values | object | Array nilai baru. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Jumlah nilai atribut yang diatur. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_13}


```
 unset_value(attribute_name) 
```

Menghapus nilai atribut dari fitur ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute_name | string | Nama atribut. |

