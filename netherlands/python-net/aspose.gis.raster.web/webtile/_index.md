---
title: "WebTile Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| cell_x | int | r | De X-kolom van een tegel. |
| cell_y | int | r | De Y-rij van een tegel. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [as_binary()](#as_binary__1) | Retourneert de byte-reeks van de afbeelding. |
| [as_path()](#as_path__2) | Presenteert de tegelinhoud als een URL of pad naar een bestand. |
| [as_raster()](#as_raster__3) | Presenteert de tegelinhoud als een Rasterlaag. |
| [get_extent()](#get_extent__4) | Presenteert een ruimtelijke omvang van deze laag. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Retourneert de byte-reeks van de afbeelding.

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | Byte-reeks |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

Presenteert de tegelinhoud als een URL of pad naar een bestand.

**Returns**

| Type | Beschrijving |
| :- | :- |
| string | Url of pad naar een bestand |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

Presenteert de tegelinhoud als een Rasterlaag.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | De Raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Presenteert een ruimtelijke omvang van deze laag.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Een ruimtelijke omvang van deze laag. |


