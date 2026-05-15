---
title: "XyzTiles Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Erstelle eine Instanz von [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Lädt die angegebene Kachel. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Lädt die angegebene Kachel. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Lädt Kacheln anhand der räumlichen Begrenzungsbox und des Zoom‑Levels. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Lädt Kacheln anhand der räumlichen Begrenzungsbox und des Zoom‑Levels. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Erstelle eine Instanz von [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Eine Verbindung, die Web‑Optionen enthält. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Lädt die angegebene Kachel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| zoom | int | Das Zoom‑Level zum Laden von Kacheln. Das höchste Zoom‑Level ist 0. Die meisten Kachelanbieter haben etwa 22 maximale Zoom‑Levels. |
| x | int | Eine x‑Spalte einer Kachel. |
| y | int | Eine y‑Zeile einer Kachel. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Die Web‑Kachel. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Lädt die angegebene Kachel.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| zoom | int | Das Zoom‑Level zum Laden von Kacheln. Das höchste Zoom‑Level ist 0. Die meisten Kachelanbieter haben etwa 22 maximale Zoom‑Levels. |
| x | int | Eine x‑Spalte einer Kachel. |
| y | int | Eine y‑Zeile einer Kachel. |
| tile_size | int | Größe der Kacheln, standardmäßig ist sie 256 (dies ist die Standardgröße für Kacheln). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Die Web‑Kachel. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Lädt Kacheln anhand der räumlichen Begrenzungsbox und des Zoom‑Levels.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| zoom | int | Das Zoom‑Level zum Laden von Kacheln. Das höchste Zoom‑Level ist 0. Die meisten Kachelanbieter haben etwa 22 maximale Zoom‑Levels. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Die Begrenzungsbox zum Laden von Kacheln. Die räumliche Referenz Wgs84 wird verwendet, falls sie fehlt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Die Webkacheln. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Lädt Kacheln anhand der räumlichen Begrenzungsbox und des Zoom‑Levels.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| zoom | int | Das Zoom‑Level zum Laden von Kacheln. Das höchste Zoom‑Level ist 0. Die meisten Kachelanbieter haben etwa 22 maximale Zoom‑Levels. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Die Begrenzungsbox zum Laden von Kacheln. Die räumliche Referenz Wgs84 wird verwendet, falls sie fehlt. |
| tile_size | int | Größe der Kacheln, standardmäßig ist sie 256 (dies ist die Standardgröße für Kacheln). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Die Webkacheln. |


