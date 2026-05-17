---
title: "XyzTiles Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Bir [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) örneği oluştur. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Belirtilen döşemeyi yükler. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Belirtilen döşemeyi yükler. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Döşemeleri mekansal sınırlama kutusu ve yakınlaştırma seviyesine göre yükler. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Döşemeleri mekansal sınırlama kutusu ve yakınlaştırma seviyesine göre yükler. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Bir [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) örneği oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Web seçeneklerini içeren bir bağlantı. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Belirtilen döşemeyi yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| zoom | int | Döşemeleri yüklemek için yakınlaştırma seviyesi. En yüksek yakınlaştırma seviyesi 0'dır. Çoğu döşeme sağlayıcısının yaklaşık 22 maksimum yakınlaştırma seviyesi vardır. |
| x | int | Bir döşemenin x-sütunu. |
| y | int | Bir döşemenin y-satırı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Web döşemesi. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Belirtilen döşemeyi yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| zoom | int | Döşemeleri yüklemek için yakınlaştırma seviyesi. En yüksek yakınlaştırma seviyesi 0'dır. Çoğu döşeme sağlayıcısının yaklaşık 22 maksimum yakınlaştırma seviyesi vardır. |
| x | int | Bir döşemenin x-sütunu. |
| y | int | Bir döşemenin y-satırı. |
| tile_size | int | Döşemelerin boyutu, varsayılan olarak 256'dır (döşeme boyutu için standarttır). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Web döşemesi. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Döşemeleri mekansal sınırlama kutusu ve yakınlaştırma seviyesine göre yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| zoom | int | Döşemeleri yüklemek için yakınlaştırma seviyesi. En yüksek yakınlaştırma seviyesi 0'dır. Çoğu döşeme sağlayıcısının yaklaşık 22 maksimum yakınlaştırma seviyesi vardır. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Döşemeleri yüklemek için sınırlama kutusu. Eksikse Wgs84 mekansal referansı kullanılacaktır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Web döşemeleri. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Döşemeleri mekansal sınırlama kutusu ve yakınlaştırma seviyesine göre yükler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| zoom | int | Döşemeleri yüklemek için yakınlaştırma seviyesi. En yüksek yakınlaştırma seviyesi 0'dır. Çoğu döşeme sağlayıcısının yaklaşık 22 maksimum yakınlaştırma seviyesi vardır. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Döşemeleri yüklemek için sınırlama kutusu. Eksikse Wgs84 mekansal referansı kullanılacaktır. |
| tile_size | int | Döşemelerin boyutu, varsayılan olarak 256'dır (döşeme boyutu için standarttır). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Web döşemeleri. |


