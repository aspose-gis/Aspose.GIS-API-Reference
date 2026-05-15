---
title: "Classe WebTile"
type: docs
weight: 10
url: /fr/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_x | int | r | La colonne X d'une tuile. |
| cell_y | int | r | La ligne Y d'une tuile. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | Renvoie la séquence d'octets de l'image |
| [as_path()](#as_path__2) | Présente le contenu de la tuile sous forme d'URL ou de chemin vers un fichier. |
| [as_raster()](#as_raster__3) | Présente le contenu de la tuile sous forme de couche Raster. |
| [get_extent()](#get_extent__4) | Présente une étendue spatiale de cette couche. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Renvoie la séquence d'octets de l'image

**Returns**

| Type | Description |
| :- | :- |
| byte | Séquence d'octets |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

Présente le contenu de la tuile sous forme d'URL ou de chemin vers un fichier.

**Returns**

| Type | Description |
| :- | :- |
| string | URL ou chemin vers un fichier |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

Présente le contenu de la tuile sous forme de couche Raster.

**Returns**

| Type | Description |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Le Raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Présente une étendue spatiale de cette couche.

**Returns**

| Type | Description |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Une étendue spatiale de cette couche. |


