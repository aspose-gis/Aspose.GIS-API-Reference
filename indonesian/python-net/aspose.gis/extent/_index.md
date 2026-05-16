---
title: "Kelas Extent"
type: docs
weight: 820
url: /id/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [Extent()](#Extent__1) | Membuat instance baru. |
| [Extent(srs)](#Extent_srs_2) | Membuat instance baru. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Membuat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Pusat extent. |
| tinggi | double | r | Tinggi extent. |
| is_valid | bool | r | Menentukan apakah [Extent](/psd/python-net/aspose.gis/extent/) ini valid. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) terkait dengan extent ini.<br/>            Bisa <see langword="null" /> jika [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) tidak diketahui.<br/>            Gunakan Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem)<br/>            untuk mentransformasi extent antara sistem referensi spasial yang berbeda. |
| width | double | r | Lebar extent. |
| x_max | double | r/w | Nilai maksimum koordinat X. |
| x_min | double | r/w | Nilai minimum koordinat X. |
| y_max | double | r/w | Nilai maksimum dari koordinat Y. |
| y_min | double | r/w | Nilai minimum dari koordinat Y. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Menggandakan instance ini. |
| [contains(extent)](#contains_extent_2) | Menentukan apakah rentang ini mengandung argumen. |
| [contains(geometry)](#contains_geometry_3) | Menentukan apakah rentang ini mengandung argumen. |
| [contains(x, y)](#contains_x_y_4) | Menentukan apakah rentang ini mengandung koordinat yang didefinisikan oleh argumen. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Mengembalikan rentang baru dalam [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) yang ditentukan yang mengandung rentang ini. |
| [grow(extent)](#grow_extent_6) | Memperluas rentang ini sehingga mencakup argumen. |
| [grow(x, y)](#grow_x_y_7) | Memperluas rentang ini sehingga mencakup titik yang ditentukan. |
| [grow_x(value)](#grow_x_value_8) | Memperluas rentang ini sepanjang sumbu X sehingga mencakup nilai yang ditentukan. |
| [grow_y(value)](#grow_y_value_9) | Memperluas rentang ini sepanjang sumbu Y sehingga mencakup nilai yang ditentukan. |
| [intersects(extent)](#intersects_extent_10) | Menentukan apakah rentang ini berpotongan dengan argumen. |
| [intersects(geometry)](#intersects_geometry_11) | Menentukan apakah rentang ini berpotongan dengan argumen. |
| normalize() | Menukar [Extent.x_min](/psd/python-net/aspose.gis/extent/) dengan [Extent.x_max](/psd/python-net/aspose.gis/extent/) jika [Extent.width](/psd/python-net/aspose.gis/extent/) negatif dan<br/>            [Extent.y_min](/psd/python-net/aspose.gis/extent/) dengan [Extent.y_max](/psd/python-net/aspose.gis/extent/) jika [Extent.height](/psd/python-net/aspose.gis/extent/) negatif. |
| [to_polygon()](#to_polygon__12) | Mengonversi rentang ini menjadi poligon persegi panjang yang mewakilinya. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Membuat instance baru.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) yang terkait dengan rentang ini.<br/>            Dapat menjadi <see langword="null" /> untuk menunjukkan bahwa SRS tidak diketahui. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x_min | double | Nilai X minimum. |
| y_min | double | Nilai Y minimum. |
| x_max | double | Nilai X maksimum. |
| y_max | double | Nilai Y maksimum. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) yang terkait dengan rentang ini.<br/>            Dapat menjadi <see langword="null" /> untuk menunjukkan bahwa SRS tidak diketahui. |

### Method: clone() {#clone__1}


```
 clone() 
```

Menggandakan instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Klon dari instance ini. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Menentukan apakah rentang ini mengandung argumen.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Rentang lain. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Nilai, yang menunjukkan apakah rentang ini mengandung argumen. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Menentukan apakah rentang ini mengandung argumen.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri untuk menguji keberadaan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Nilai, yang menunjukkan apakah rentang ini mengandung argumen. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Menentukan apakah rentang ini mengandung koordinat yang didefinisikan oleh argumen.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | double | X dari koordinat. |
| y | double | Y dari koordinat. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Nilai, yang menunjukkan apakah koordinat berada di dalam kotak pembatas. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Mengembalikan rentang baru dalam [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) yang ditentukan yang mengandung rentang ini.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) untuk ditransformasikan ke. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Hasil transformasi ekstensi ini ke SRS yang ditentukan. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Memperluas rentang ini sehingga mencakup argumen.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Ekstensi lain. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Memperluas rentang ini sehingga mencakup titik yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| x | double | Koordinat X yang disertakan. |
| y | double | Koordinat Y yang disertakan. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Memperluas rentang ini sepanjang sumbu X sehingga mencakup nilai yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nilai | double | Nilai yang disertakan. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Memperluas rentang ini sepanjang sumbu Y sehingga mencakup nilai yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| nilai | double | Nilai yang disertakan. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Menentukan apakah rentang ini berpotongan dengan argumen.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Rentang lain. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Nilai, yang menunjukkan apakah ekstensi ini berpotongan dengan argumen. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Menentukan apakah rentang ini berpotongan dengan argumen.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri untuk menguji perpotongan |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool | Nilai, yang menunjukkan apakah ekstensi ini berpotongan dengan argumen. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Mengonversi rentang ini menjadi poligon persegi panjang yang mewakilinya.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Poligon persegi panjang [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) yang mewakili ekstensi ini. Untuk ekstensi yang tidak valid<br/>            poligon kosong dikembalikan. |


