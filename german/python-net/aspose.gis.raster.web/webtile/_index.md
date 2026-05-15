---
title: "WebTile Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| cell_x | int | r | Die X-Spalte einer Kachel. |
| cell_y | int | r | Die Y-Zeile einer Kachel. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [as_binary()](#as_binary__1) | Gibt die Bild-Bytefolge zurück |
| [as_path()](#as_path__2) | Stellt den Kachelinhalt als URL oder Pfad zu einer Datei dar. |
| [as_raster()](#as_raster__3) | Stellt den Kachelinhalt als Raster-Layer dar. |
| [get_extent()](#get_extent__4) | Stellt die räumliche Ausdehnung dieser Ebene dar. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Gibt die Bild-Bytefolge zurück

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte | Bytefolge |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

Stellt den Kachelinhalt als URL oder Pfad zu einer Datei dar.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string | URL oder Pfad zu einer Datei |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

Stellt den Kachelinhalt als Raster-Layer dar.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Das Raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Stellt die räumliche Ausdehnung dieser Ebene dar.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ein räumlicher Ausdehnungsbereich dieser Ebene. |


