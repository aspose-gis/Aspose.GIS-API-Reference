---
title: "Kelas ProjectedSpatialReferenceSystemParameters"
type: docs
weight: 160
url: /id/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | Membuat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | Urutan sumbu. Default ke [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/). |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | SRS geografis dasar (SRS tempat proyeksi diterapkan).<br/>            Anda HARUS mengatur properti ini agar tidak bernilai <see langword=\"null\" /> untuk membuat SRS yang valid,<br/>            properti ini tidak memiliki nilai default. |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | Unit yang akan digunakan dalam SRS ini. Default adalah [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| nama | string | r/w | Nama SRS terproyeksi. Default adalah "Unnamed". |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | Pengidentifikasi metode proyeksi. Tidak ada nilai default, Anda dapat mengatur parameter ini agar tidak bernilai <see langword=\"null\" />,<br/>            jika Anda ingin menambahkan pengidentifikasi ke proyeksi. Jika Anda melakukannya - terserah Anda untuk memastikan bahwa pengidentifikasi konsisten dengan metode proyeksi<br/>            nama (nama metode proyeksi tidak akan berubah ketika Anda mengatur properti ini). |
| projection_method_name | string | r/w | Nama metode proyeksi. Tidak ada nilai default dan Anda HARUS mengatur parameter ini ke nilai yang tidak <see langword="null" />, karena<br/>            SRS terproyeksi tanpa nama proyeksi tidak berguna. |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Sumbu yang menggambarkan dimensi X (horizontal). Default ke sumbu dengan arah timur. |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Sumbu yang menggambarkan dimensi Y (vertikal). Default ke sumbu dengan arah utara. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | Menambahkan parameter proyeksi ke SRS ini. Jika parameter dengan nama tersebut sudah ditambahkan - perbarui. |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | Mendapatkan parameter proyeksi dengan nama yang ditentukan. |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

Membuat instance baru.

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

Menambahkan parameter proyeksi ke SRS ini. Jika parameter dengan nama tersebut sudah ditambahkan - perbarui.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| parameter_name | string | Nama parameter proyeksi. |
| value | double | Nilai parameter. Satuan nilai harus berada dalam [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/)<br/>            atau [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) dari [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/). |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

Mendapatkan parameter proyeksi dengan nama yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| parameter_name | string | Nama parameter. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Nilai parameter proyeksi. |


