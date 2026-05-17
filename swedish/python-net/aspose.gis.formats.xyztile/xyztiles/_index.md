---
title: "XyzTiles-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Skapa en instans av [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Laddar den angivna tile. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Laddar den angivna tile. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Laddar tiles enligt den rumsliga avgränsningsrutan och zoomnivån. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Laddar tiles enligt den rumsliga avgränsningsrutan och zoomnivån. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Skapa en instans av [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | En anslutning som innehåller webb‑alternativ. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Laddar den angivna tile.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| zoom | int | Zoomnivån för att ladda tiles. Den högsta zoomnivån är 0. De flesta tile‑leverantörer har cirka 22 maximala zoomnivåer. |
| x | int | En x‑kolumn i en tile. |
| y | int | En y‑rad i en tile. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Webb‑tile. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Laddar den angivna tile.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| zoom | int | Zoomnivån för att ladda tiles. Den högsta zoomnivån är 0. De flesta tile‑leverantörer har cirka 22 maximala zoomnivåer. |
| x | int | En x‑kolumn i en tile. |
| y | int | En y‑rad i en tile. |
| tile_size | int | Storlek på tiles, som standard är 256 (det är standard för tile‑storlek). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Webb‑tile. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Laddar tiles enligt den rumsliga avgränsningsrutan och zoomnivån.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| zoom | int | Zoomnivån för att ladda tiles. Den högsta zoomnivån är 0. De flesta tile‑leverantörer har cirka 22 maximala zoomnivåer. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Avgränsningsrutan för att ladda tiles. Wgs84‑referensen kommer att användas om den saknas. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Webbplattorna. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Laddar tiles enligt den rumsliga avgränsningsrutan och zoomnivån.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| zoom | int | Zoomnivån för att ladda tiles. Den högsta zoomnivån är 0. De flesta tile‑leverantörer har cirka 22 maximala zoomnivåer. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Avgränsningsrutan för att ladda tiles. Wgs84‑referensen kommer att användas om den saknas. |
| tile_size | int | Storlek på tiles, som standard är 256 (det är standard för tile‑storlek). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Webbplattorna. |


