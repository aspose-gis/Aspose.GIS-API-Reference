---
title: "Kelas FeatureAttributeCollection"
type: docs
weight: 850
url: /id/python-net/aspose.gis/featureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttributeCollection

**Inheritance:** BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| count | int | r | Mendapatkan jumlah atribut dalam sebuah [Feature](/psd/python-net/aspose.gis/feature/). |
| is_locked | bool | r | Mendapatkan nilai yang menunjukkan apakah koleksi atribut ini terkunci. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | Menambahkan atribut ke koleksi. |
| [contains(name)](#contains_name_2) | Menentukan apakah koleksi atribut berisi atribut dengan nama yang ditentukan. |
| [index_of(name)](#index_of_name_3) | Mencari atribut dan mengembalikan indeks berbasis nolnya. |
| lock() | Mengunci koleksi atribut ini untuk mencegah modifikasi lebih lanjut. |
| [remove(index)](#remove_index_4) | Menghapus atribut dari koleksi. |
| [remove(name)](#remove_name_5) | Menghapus atribut dari koleksi. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

Menambahkan atribut ke koleksi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | Atribut yang akan ditambahkan. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

Menentukan apakah koleksi atribut berisi atribut dengan nama yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama atribut. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | <see langword=\"true\" /> jika koleksi atribut berisi atribut dengan nama yang ditentukan; jika tidak, <see langword=\"false\" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

Mencari atribut dan mengembalikan indeks berbasis nolnya.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama atribut. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int | Indeks berbasis nol dari atribut dalam koleksi, jika ditemukan; jika tidak, –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

Menghapus atribut dari koleksi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Indeks atribut. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

Menghapus atribut dari koleksi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama atribut. |

