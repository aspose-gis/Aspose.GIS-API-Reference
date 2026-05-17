---
title: "XyzTiles Clase"
type: docs
weight: 20
url: /es/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Crea una instancia de [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Carga el mosaico especificado. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Carga el mosaico especificado. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Carga mosaicos mediante el cuadro delimitador espacial y el nivel de zoom. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Carga mosaicos mediante el cuadro delimitador espacial y el nivel de zoom. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Crea una instancia de [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Una conexión que contiene opciones web. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Carga el mosaico especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| zoom | int | El nivel de zoom para cargar mosaicos. El nivel de zoom más alto es 0. La mayoría de los proveedores de mosaicos tienen alrededor de 22 niveles máximos de zoom. |
| x | int | Una columna x de un mosaico. |
| y | int | Una fila y de un mosaico. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | El mosaico web. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Carga el mosaico especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| zoom | int | El nivel de zoom para cargar mosaicos. El nivel de zoom más alto es 0. La mayoría de los proveedores de mosaicos tienen alrededor de 22 niveles máximos de zoom. |
| x | int | Una columna x de un mosaico. |
| y | int | Una fila y de un mosaico. |
| tile_size | int | Tamaño de los mosaicos, por defecto es 256 (es el estándar para el tamaño de mosaicos) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | El mosaico web. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Carga mosaicos mediante el cuadro delimitador espacial y el nivel de zoom.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| zoom | int | El nivel de zoom para cargar mosaicos. El nivel de zoom más alto es 0. La mayoría de los proveedores de mosaicos tienen alrededor de 22 niveles máximos de zoom. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | El cuadro delimitador para cargar mosaicos. Se usará la referencia espacial Wgs84 si falta. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Los mosaicos web. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Carga mosaicos mediante el cuadro delimitador espacial y el nivel de zoom.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| zoom | int | El nivel de zoom para cargar mosaicos. El nivel de zoom más alto es 0. La mayoría de los proveedores de mosaicos tienen alrededor de 22 niveles máximos de zoom. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | El cuadro delimitador para cargar mosaicos. Se usará la referencia espacial Wgs84 si falta. |
| tile_size | int | Tamaño de los mosaicos, por defecto es 256 (es el estándar para el tamaño de mosaicos) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Los mosaicos web. |


