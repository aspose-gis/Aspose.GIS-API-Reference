---
title: "Kelas FeatureAttribute"
type: docs
weight: 840
url: /id/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | Menginisialisasi instance baru dari kelas [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | Menginisialisasi instance baru dari kelas [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | Mendapatkan nilai yang menunjukkan apakah instance ini dapat bernilai null. |
| can_be_unset | bool | r/w | Mendapatkan atau mengatur nilai yang menunjukkan apakah nilai untuk atribut ini dapat diabaikan. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | Mendapatkan tipe data dari atribut. |
| default_value | object | r/w | Mendapatkan atau mengatur nilai untuk atribut, yang menunjukkan data yang hilang. |
| has_custom_default_value | bool | r | Mendapatkan nilai yang menunjukkan apakah nilai default yang telah ditentukan untuk atribut ini telah ditimpa dengan nilai khusus. |
| is_locked | bool | r | Mendapatkan nilai yang menunjukkan apakah atribut ini terkunci. |
| nama | string | r/w | Mendapatkan nama atribut. |
| precision | Nullable<int> | r/w | Mendapatkan atau mengatur jumlah maksimum digit desimal yang disimpan. |
| type_name | string | r/w | Nama tipe dari atribut. |
| width | Nullable<int> | r/w | Mendapatkan atau mengatur lebar maksimum yang diizinkan untuk representasi karakter dari atribut. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| lock() | Mengunci atribut ini. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

Menginisialisasi instance baru dari kelas [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama atribut. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Tipe data dari atribut. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

Menginisialisasi instance baru dari kelas [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama atribut. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Tipe data dari atribut. |
| can_be_null | bool | <see langword=\"true\" /> jika instance ini dapat null; jika tidak, <see langword=\"false\" />. |

