---
title: "Kelas GeoJsonOptions"
type: docs
weight: 20
url: /id/python-net/aspose.gis.formats.geojson/geojsonoptions/
---

**Summary:** Driver-specific options for GeoJSON format.

**Module:** [aspose.gis.formats.geojson](/psd/python-net/aspose.gis.formats.geojson/)

**Full Name:** aspose.gis.formats.geojson.GeoJsonOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [GeoJsonOptions()](#GeoJsonOptions__1) | Buat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| array_as_string | bool | r/w | Apakah mengekspose array JSon dari string, integer, atau real sebagai string. |
| attributes_skip | bool | r/w | mengontrol penerjemahan atribut: ya - lewati semua atribut |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | Buat id secara otomatis |
| close_linear_ring | bool | r/w | Menentukan apakah menutup [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) yang tidak tertutup dalam setiap geometri. Nilai default <see langword=\"false\" />. |
| create_midpoints | bool | r/w | Menentukan apakah menambahkan titik baru di tengah setiap segmen geometri. Nilai default <see langword=\"false\" />. |
| date_as_string | bool | r/w | Apakah mengekspose tanggal/waktu/date-time JSon sebagai string. |
| delete_near_points | bool | r/w | Menentukan apakah menghapus titik-titik dekat dalam setiap geometri. Nilai default <see langword=\"false\" />. |
| delete_near_points_distance | double | r/w | Menentukan jarak untuk [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Nilai default <see langword="0" />. |
| description | string | r/w | Deskripsi pada tingkat koleksi fitur (untuk pembuatan lapisan) |
| geometry_as_collection | bool | r/w | mengontrol penerjemahan geometri: ya - membungkus geometri dengan tipe GeometryCollection |
| linearization_tolerance | double | r/w | Toleransi yang digunakan untuk melinierkan geometri kurva. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Sebuah [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) yang akan diterapkan pada koordinat M<br/>            ketika geometri ditambahkan ke [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) atau ketika dibaca dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Nilai default adalah [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nama | string | r/w | Nama pada tingkat koleksi fitur (untuk pembuatan lapisan) |
| nested_properties_separator | string | r/w | Mendapatkan atau mengatur string yang digunakan untuk memisahkan komponen atribut bersarang.<br/>            Nilai default adalah "_". |
| read_bounding_boxes | bool | r/w | Menentukan apakah Bounding Boxes ('bbox') harus dibaca sebagai atribut dengan nama 'bbox_0', 'bbox_1', dll.<br/>            Nilai default adalah <see langword="false" />.<br/>            String [GeoJsonOptions.nested_properties_separator](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions/) digunakan dalam nama bbox_0, bbox_1,.. names. |
| simplify_segments | bool | r/w | Menentukan apakah menghapus titik yang berada pada segmen yang sama di setiap geometri. Nilai default <see langword="false" />. |
| simplify_segments_distance | double | r/w | Menentukan jarak untuk [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Nilai default <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Menentukan apakah geometri harus divalidasi ketika ditambahkan ke lapisan.<br/>            Jika disetel ke <see langword="true" />, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) dipanggil untuk setiap<br/>            geometri saat ditambahkan ke lapisan, dan jika validasi gagal ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) adalah <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) dilempar. |
| write_bounding_boxes | bool | r/w | Menentukan apakah objek GeoJSON harus menyertakan informasi tentang rentang koordinat untuk Geometri‑nya.<br/>            Jika diatur ke <see langword="true" />, sebuah anggota "bbox" dihasilkan untuk setiap geometri (tidak null) ketika ditambahkan ke lapisan.<br/>            Nilai default adalah <see langword="false" />. |
| write_polygons_as_lines | bool | r/w | Menentukan apakah transformasi poligon atau multipoligon menjadi linestring diizinkan. Nilai default <see langword="false" />. |
| write_unset_attribute | bool | r/w | Apakah menulis atribut yang belum diatur dengan menambahkan nilai 'null' |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Sebuah [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) yang akan diterapkan pada koordinat X dan Y<br/>            ketika geometri ditambahkan ke [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) atau ketika dibaca dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Nilai default adalah [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Sebuah [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) yang akan diterapkan pada koordinat Z<br/>            ketika geometri ditambahkan ke [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) atau ketika dibaca dari [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Nilai default adalah [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GeoJsonOptions() {#GeoJsonOptions__1}


```
 GeoJsonOptions() 
```

Buat instance baru.

