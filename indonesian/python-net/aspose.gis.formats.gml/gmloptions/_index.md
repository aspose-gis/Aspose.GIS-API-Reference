---
title: "GmlOptions Kelas"
type: docs
weight: 20
url: /id/python-net/aspose.gis.formats.gml/gmloptions/
---

**Summary:** Driver-specific options for GML format.

**Module:** [aspose.gis.formats.gml](/psd/python-net/aspose.gis.formats.gml/)

**Full Name:** aspose.gis.formats.gml.GmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GmlOptions()](#GmlOptions__1) | Buat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| application_namespace | string | r/w | Ini menentukan namespace khusus yang akan digunakan sebagai namespace aplikasi untuk menghasilkan dokumen gml. |
| close_linear_ring | bool | r/w | Menentukan apakah menutup [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) yang tidak tertutup dalam setiap geometri. Nilai default <see langword=\"false\" />. |
| create_midpoints | bool | r/w | Menentukan apakah menambahkan titik baru di tengah setiap segmen geometri. Nilai default <see langword=\"false\" />. |
| delete_near_points | bool | r/w | Menentukan apakah menghapus titik-titik dekat dalam setiap geometri. Nilai default <see langword=\"false\" />. |
| delete_near_points_distance | double | r/w | Menentukan jarak untuk [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Nilai default <see langword="0" />. |
| linearization_tolerance | double | r/w | Toleransi yang digunakan untuk melinierkan geometri kurva. |
| load_schemas_from_internet | bool | r/w | Menentukan apakah Aspose.GIS diizinkan untuk memuat skema XML dari Internet.<br/>            Jika disetel ke <see langword="false" />, skema dengan URI absolut yang tidak dimulai dengan 'file://' tidak akan dimuat.<br/>            Default adalah <see langword="false" />. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Sebuah [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) yang akan diterapkan pada koordinat M<br/>            ketika geometri ditambahkan ke [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) atau ketika dibaca dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Nilai default adalah [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | r/w | Mendapatkan atau mengatur string yang digunakan untuk memisahkan komponen atribut bersarang.<br/>            Nilai default adalah "_". |
| restore_schema | bool | r/w | Menentukan apakah Aspose.GIS diizinkan untuk mengurai atribut dalam file Gml di mana skema XML tidak ada atau tidak dapat dimuat.<br/>            Jika disetel ke <see langword="true" />, pembaca Aspose.GIS tidak memerlukan keberadaan Skema XML.<br/>            Default adalah <see langword="false" />. |
| schema_location | string | r/w | Daftar pasangan URI yang dipisahkan spasi. URI pertama dalam setiap pasangan adalah URI dari namespace, URI kedua adalah Path ke skema XML dari namespace.<br/>            Jika disetel ke <see langword="null" />, [GmlDriver](/psd/python-net/aspose.gis.formats.gml/gmldriver/) akan mencoba membaca schemaLocation dari elemen akar dokumen.<br/>            Default adalah <see langword="null" />. |
| simplify_segments | bool | r/w | Menentukan apakah menghapus titik yang berada pada segmen yang sama di setiap geometri. Nilai default <see langword="false" />. |
| simplify_segments_distance | double | r/w | Menentukan jarak untuk [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Nilai default <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Menentukan apakah geometri harus divalidasi ketika ditambahkan ke lapisan.<br/>            Jika disetel ke <see langword="true" />, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) dipanggil untuk setiap<br/>            geometri saat ditambahkan ke lapisan, dan jika validasi gagal ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) adalah <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) dilempar. |
| write_polygons_as_lines | bool | r/w | Menentukan apakah transformasi poligon atau multipoligon menjadi linestring diizinkan. Nilai default <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Sebuah [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) yang akan diterapkan pada koordinat X dan Y<br/>            ketika geometri ditambahkan ke [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) atau ketika dibaca dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Nilai default adalah [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Sebuah [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) yang akan diterapkan pada koordinat Z<br/>            ketika geometri ditambahkan ke [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) atau ketika dibaca dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Nilai default adalah [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GmlOptions() {#GmlOptions__1}


```
 GmlOptions() 
```

Buat instance baru.

