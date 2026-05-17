---
title: "Clase WebTile"
type: docs
weight: 10
url: /es/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| cell_x | int | r | La columna X de una tesela. |
| cell_y | int | r | La fila Y de una tesela. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [as_binary()](#as_binary__1) | Devuelve la secuencia de bytes de la imagen |
| [as_path()](#as_path__2) | Presenta el contenido de la tesela como una URL o ruta a un archivo. |
| [as_raster()](#as_raster__3) | Presenta el contenido del mosaico como una capa Raster. |
| [get_extent()](#get_extent__4) | Presenta una extensión espacial de esta capa. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Devuelve la secuencia de bytes de la imagen

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | Secuencia de bytes |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

Presenta el contenido de la tesela como una URL o ruta a un archivo.

**Returns**

| Tipo | Descripción |
| :- | :- |
| string | URL o ruta a un archivo |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

Presenta el contenido del mosaico como una capa Raster.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | El Raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Presenta una extensión espacial de esta capa.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Una extensión espacial de esta capa. |


