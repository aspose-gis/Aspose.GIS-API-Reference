---
title: "WebTile-klass"
type: docs
weight: 10
url: /sv/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| cell_x | int | r | X-kolumnen i en tile. |
| cell_y | int | r | Y-raden i en tile. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [as_binary()](#as_binary__1) | Returnerar bildens byte-sekvens |
| [as_path()](#as_path__2) | Visar tile-innehållet som en URL eller sökväg till en fil. |
| [as_raster()](#as_raster__3) | Visar tile-innehållet som ett Raster-lager. |
| [get_extent()](#get_extent__4) | Visar ett rumsligt omfång för detta lager. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Returnerar bildens byte-sekvens

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Byte-sekvens |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

Visar tile-innehållet som en URL eller sökväg till en fil.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| string | Url eller sökväg till en fil |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

Visar tile-innehållet som ett Raster-lager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Rasterlagret. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Visar ett rumsligt omfång för detta lager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ett rumsligt omfång för detta lager. |


