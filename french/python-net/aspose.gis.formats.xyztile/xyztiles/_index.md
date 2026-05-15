---
title: "Classe XyzTiles"
type: docs
weight: 20
url: /fr/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Créez une instance de [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Charge la tuile spécifiée. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Charge la tuile spécifiée. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Charge les tuiles selon la boîte englobante spatiale et le niveau de zoom. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Charge les tuiles selon la boîte englobante spatiale et le niveau de zoom. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Créez une instance de [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Une connexion contenant des options web |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Charge la tuile spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| zoom | int | Le niveau de zoom pour charger les tuiles. Le niveau de zoom le plus élevé est 0. La plupart des fournisseurs de tuiles ont environ 22 niveaux de zoom maximum. |
| x | int | Une colonne x d'une tuile |
| y | int | Une ligne y d'une tuile |

**Returns**

| Type | Description |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | La tuile web |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Charge la tuile spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| zoom | int | Le niveau de zoom pour charger les tuiles. Le niveau de zoom le plus élevé est 0. La plupart des fournisseurs de tuiles ont environ 22 niveaux de zoom maximum. |
| x | int | Une colonne x d'une tuile |
| y | int | Une ligne y d'une tuile |
| tile_size | int | Taille des tuiles, par défaut 256 (c'est la taille standard des tuiles). |

**Returns**

| Type | Description |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | La tuile web |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Charge les tuiles selon la boîte englobante spatiale et le niveau de zoom.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| zoom | int | Le niveau de zoom pour charger les tuiles. Le niveau de zoom le plus élevé est 0. La plupart des fournisseurs de tuiles ont environ 22 niveaux de zoom maximum. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | La boîte englobante pour charger les tuiles. La référence spatiale Wgs84 sera utilisée si elle est manquante. |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Les tuiles web. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Charge les tuiles selon la boîte englobante spatiale et le niveau de zoom.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| zoom | int | Le niveau de zoom pour charger les tuiles. Le niveau de zoom le plus élevé est 0. La plupart des fournisseurs de tuiles ont environ 22 niveaux de zoom maximum. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | La boîte englobante pour charger les tuiles. La référence spatiale Wgs84 sera utilisée si elle est manquante. |
| tile_size | int | Taille des tuiles, par défaut 256 (c'est la taille standard des tuiles). |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Les tuiles web. |


