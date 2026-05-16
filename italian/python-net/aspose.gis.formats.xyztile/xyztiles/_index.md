---
title: "Classe XyzTiles"
type: docs
weight: 20
url: /it/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Crea un'istanza di [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Carica il tile specificato. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Carica il tile specificato. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Carica i tile in base al riquadro spaziale e al livello di zoom. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Carica i tile in base al riquadro spaziale e al livello di zoom. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Crea un'istanza di [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Una connessione contenente le opzioni web. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Carica il tile specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| zoom | int | Il livello di zoom per il caricamento dei tile. Il livello di zoom più alto è 0. La maggior parte dei fornitori di tile ha circa 22 livelli di zoom massimi. |
| x | int | Una colonna x di un tile. |
| y | int | Una riga y di un tile. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Il tile web. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Carica il tile specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| zoom | int | Il livello di zoom per il caricamento dei tile. Il livello di zoom più alto è 0. La maggior parte dei fornitori di tile ha circa 22 livelli di zoom massimi. |
| x | int | Una colonna x di un tile. |
| y | int | Una riga y di un tile. |
| tile_size | int | Dimensione dei tile, per impostazione predefinita è 256 (è lo standard per la dimensione dei tile). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Il tile web. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Carica i tile in base al riquadro spaziale e al livello di zoom.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| zoom | int | Il livello di zoom per il caricamento dei tile. Il livello di zoom più alto è 0. La maggior parte dei fornitori di tile ha circa 22 livelli di zoom massimi. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Il riquadro di delimitazione per caricare i tile. Il riferimento spaziale Wgs84 verrà utilizzato se mancante. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Le piastrelle web. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Carica i tile in base al riquadro spaziale e al livello di zoom.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| zoom | int | Il livello di zoom per il caricamento dei tile. Il livello di zoom più alto è 0. La maggior parte dei fornitori di tile ha circa 22 livelli di zoom massimi. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Il riquadro di delimitazione per caricare i tile. Il riferimento spaziale Wgs84 verrà utilizzato se mancante. |
| tile_size | int | Dimensione dei tile, per impostazione predefinita è 256 (è lo standard per la dimensione dei tile). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Le piastrelle web. |


