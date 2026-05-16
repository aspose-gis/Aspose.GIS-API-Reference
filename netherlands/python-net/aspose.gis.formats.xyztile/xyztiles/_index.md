---
title: "XyzTiles Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Maak een exemplaar van [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Laadt de opgegeven tegel. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Laadt de opgegeven tegel. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Laadt tegels op basis van het ruimtelijke begrenzingsvak en zoomniveau. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Laadt tegels op basis van het ruimtelijke begrenzingsvak en zoomniveau. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Maak een exemplaar van [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Een verbinding met webopties. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Laadt de opgegeven tegel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| zoom | int | Het zoomniveau voor het laden van tegels. Het hoogste zoomniveau is 0. De meeste tegelproviders hebben ongeveer 22 maximale zoomniveaus. |
| x | int | Een x‑kolom van een tegel. |
| y | int | Een y‑rij van een tegel. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | De webtegel. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Laadt de opgegeven tegel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| zoom | int | Het zoomniveau voor het laden van tegels. Het hoogste zoomniveau is 0. De meeste tegelproviders hebben ongeveer 22 maximale zoomniveaus. |
| x | int | Een x‑kolom van een tegel. |
| y | int | Een y‑rij van een tegel. |
| tile_size | int | Grootte van tegels, standaard is 256 (dit is standaard voor tegelgroottes). |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | De webtegel. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Laadt tegels op basis van het ruimtelijke begrenzingsvak en zoomniveau.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| zoom | int | Het zoomniveau voor het laden van tegels. Het hoogste zoomniveau is 0. De meeste tegelproviders hebben ongeveer 22 maximale zoomniveaus. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Het begrenzingsvak om tegels te laden. De Wgs84‑ruimtelijke referentie wordt gebruikt als deze ontbreekt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | De webtegels. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Laadt tegels op basis van het ruimtelijke begrenzingsvak en zoomniveau.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| zoom | int | Het zoomniveau voor het laden van tegels. Het hoogste zoomniveau is 0. De meeste tegelproviders hebben ongeveer 22 maximale zoomniveaus. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Het begrenzingsvak om tegels te laden. De Wgs84‑ruimtelijke referentie wordt gebruikt als deze ontbreekt. |
| tile_size | int | Grootte van tegels, standaard is 256 (dit is standaard voor tegelgroottes). |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | De webtegels. |


