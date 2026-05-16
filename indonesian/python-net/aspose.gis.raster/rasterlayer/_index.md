---
title: "Kelas RasterLayer"
type: docs
weight: 70
url: /id/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| band_count | int | r | Mendapatkan jumlah pita dalam lapisan raster. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Mendapatkan batas raster. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Mendapatkan ukuran sel atau piksel raster. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Mendapatkan [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) yang menginstansiasi lapisan ini. |
| tinggi | int | r | Mendapatkan tinggi raster dalam piksel. Juga dikenal sebagai jumlah baris. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Mendapatkan nilai yang mewakili latar belakang atau 'tidak ada data' raster. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Mendapatkan sistem referensi spasial raster.<br/>            Dapat berupa <see langword="null" /> jika tidak diketahui. |
| upper_left_x | double | r | Mendapatkan koordinat x sudut kiri atas raster. |
| upper_left_y | double | r | Mendapatkan koordinat y sudut kiri atas raster. |
| width | int | r | Mendapatkan lebar raster dalam piksel. Juga dikenal sebagai jumlah kolom. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Memotong lapisan raster menggunakan bentuk geometris (dan masker pita). |
| [crop(masks)](#crop_masks_2) | Memotong lapisan raster menggunakan masker pita). |
| [get_band(index)](#get_band_index_3) | Mendapatkan pita berdasarkan indeks yang ditentukan. |
| [get_extent()](#get_extent__4) | Menghitung jangkauan spasial lapisan ini. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Mengonversi kolom dan baris yang ditentukan ke koordinat spasial. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Menghitung statistik ringkasan yang terdiri dari jumlah, total, rata-rata, min, maks. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Membaca nilai dalam sel yang ditentukan. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Membaca nilai dalam blok yang ditentukan sebagai array satu dimensi. |
| [warp(options)](#warp_options_9) | Membengkokkan lapisan raster ke lapisan lain. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Memotong lapisan raster menggunakan bentuk geometris (dan masker pita).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri mewakili bentuk geometris. |
| masker | double | Mask untuk lapisan pemotongan |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Lapisan raster yang dipotong. Jika tidak ada irisan yang ditemukan, mengembalikan <see langword="null" />. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Memotong lapisan raster menggunakan masker pita).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| masker | double | Mask untuk lapisan pemotongan |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Lapisan raster yang dipotong. Jika tidak ada irisan yang ditemukan, mengembalikan <see langword="null" />. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Mendapatkan pita berdasarkan indeks yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| index | int | Nomor band dimulai dari 0 dan band diasumsikan 0 jika tidak ditentukan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Mengembalikan metadata dasar tentang sebuah band raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Menghitung jangkauan spasial lapisan ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Batas spasial lapisan ini. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Mengonversi kolom dan baris yang ditentukan ke koordinat spasial.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cell_x | int | Nilai untuk kolom (koordinat x). Penomoran dimulai dari 0. |
| cell_y | int | Nilai untuk baris (koordinat y). Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Mengembalikan koordinat x sudut kiri atas berdasarkan kolom dan baris. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Menghitung statistik ringkasan yang terdiri dari jumlah, total, rata-rata, min, maks.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| band_index | int | Indeks band. Penomoran dimulai dari 0. |
| exclude_nodata_value | bool | Mengizinkan pengecualian nilai 'nodata'. Jika 'excludeNodataValue' diatur ke false, maka semua piksel akan dipertimbangkan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | Statistik ringkasan. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Membaca nilai dalam sel yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| cell_x | int | Nilai untuk kolom (koordinat x). Penomoran dimulai dari 0. |
| cell_y | int | Nilai untuk baris (koordinat y). Penomoran dimulai dari 0. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | Nilai raster. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Membaca nilai dalam blok yang ditentukan sebagai array satu dimensi.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Blok sel raster tempat dump dibaca. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | Dump nilai. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Membengkokkan lapisan raster ke lapisan lain.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Opsi untuk prosedur reproyeksi. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Lapisan raster warp. |


