---
title: "Classe WebTile"
type: docs
weight: 10
url: /it/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| cell_x | int | r | La colonna X di una tessera. |
| cell_y | int | r | La riga Y di una tessera. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [as_binary()](#as_binary__1) | Restituisce la sequenza di byte dell'immagine |
| [as_path()](#as_path__2) | Presenta il contenuto della tessera come URL o percorso a un file. |
| [as_raster()](#as_raster__3) | Presenta il contenuto della tessera come un livello Raster. |
| [get_extent()](#get_extent__4) | Presenta un'estensione spaziale di questo livello. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Restituisce la sequenza di byte dell'immagine

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | Sequenza di byte |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

Presenta il contenuto della tessera come URL o percorso a un file.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| string | Url o percorso a un file |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

Presenta il contenuto della tessera come un livello Raster.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Il Raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Presenta un'estensione spaziale di questo livello.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Un'estensione spaziale di questo layer. |


