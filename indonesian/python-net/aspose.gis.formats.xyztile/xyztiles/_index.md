---
title: "Kelas XyzTiles"
type: docs
weight: 20
url: /id/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Buat sebuah instance dari [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Memuat ubin yang ditentukan. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Memuat ubin yang ditentukan. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Memuat ubin berdasarkan kotak pembatas spasial dan tingkat zoom. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Memuat ubin berdasarkan kotak pembatas spasial dan tingkat zoom. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Buat sebuah instance dari [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Sebuah koneksi yang berisi opsi web. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Memuat ubin yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| zoom | int | Tingkat zoom untuk memuat ubin. Tingkat zoom tertinggi adalah 0. Kebanyakan penyedia ubin memiliki sekitar 22 tingkat zoom maksimum. |
| x | int | Kolom x dari sebuah ubin. |
| y | int | Baris y dari sebuah ubin. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Ubin web. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Memuat ubin yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| zoom | int | Tingkat zoom untuk memuat ubin. Tingkat zoom tertinggi adalah 0. Kebanyakan penyedia ubin memiliki sekitar 22 tingkat zoom maksimum. |
| x | int | Kolom x dari sebuah ubin. |
| y | int | Baris y dari sebuah ubin. |
| tile_size | int | Ukuran ubin, secara default adalah 256 (ini standar untuk ukuran ubin) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Ubin web. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Memuat ubin berdasarkan kotak pembatas spasial dan tingkat zoom.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| zoom | int | Tingkat zoom untuk memuat ubin. Tingkat zoom tertinggi adalah 0. Kebanyakan penyedia ubin memiliki sekitar 22 tingkat zoom maksimum. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Kotak pembatas untuk memuat ubin. Referensi spasial Wgs84 akan digunakan jika tidak disertakan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Ubin web. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Memuat ubin berdasarkan kotak pembatas spasial dan tingkat zoom.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| zoom | int | Tingkat zoom untuk memuat ubin. Tingkat zoom tertinggi adalah 0. Kebanyakan penyedia ubin memiliki sekitar 22 tingkat zoom maksimum. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Kotak pembatas untuk memuat ubin. Referensi spasial Wgs84 akan digunakan jika tidak disertakan. |
| tile_size | int | Ukuran ubin, secara default adalah 256 (ini standar untuk ukuran ubin) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Ubin web. |


