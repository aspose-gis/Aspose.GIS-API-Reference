---
title: "Kelas Projection"
type: docs
weight: 170
url: /id/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unit yang digunakan untuk parameter sudut. |
| epsg_code | int | r | Jika pengenal objek ini adalah pengenal EPSG - kembalikan kodenya. Jika tidak - kembalikan -1. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Pengenal objek yang dapat diidentifikasi ini. |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Unit yang digunakan untuk parameter linier. |
| nama | string | r | Nama objek ini. |
| parameters_names | System.Collections.Generic.IList<string> | r | Mendapatkan koleksi enumerable dari nama-nama parameter yang diberikan ke proyeksi ini |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | Mendapatkan parameter dengan nama yang ditentukan dari proyeksi ini. |
| [is_equivalent(other)](#is_equivalent_other_2) | Menentukan apakah dua proyeksi setara. Proyeksi yang setara memetakan (longitude, latitude) ke (x, y) dengan cara yang sama.<br/>             |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | Mendapatkan parameter dengan nama yang ditentukan dari proyeksi ini. Jika tidak ada parameter tersebut - mengembalikan <see langword=\"null\" />. |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

Mendapatkan parameter dengan nama yang ditentukan dari proyeksi ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nama | string | Nama parameter. |
