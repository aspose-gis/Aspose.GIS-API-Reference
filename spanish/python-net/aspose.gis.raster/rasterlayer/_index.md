---
title: "Clase RasterLayer"
type: docs
weight: 70
url: /es/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| band_count | int | r | Obtiene el número de bandas en la capa raster. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Obtiene los límites del raster. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Obtiene el tamaño de celda o píxel del raster. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Obtiene el [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) que instanció esta capa. |
| altura | int | r | Obtiene la altura del raster en píxeles. También se conoce como recuento de filas. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Obtiene los valores que representan el fondo o 'sin datos' del raster. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Obtiene un sistema de referencia espacial del raster.<br/>            Puede ser <see langword=\"null\" /> si es desconocido. |
| upper_left_x | double | r | Obtiene la coordenada x de la esquina superior izquierda del raster. |
| upper_left_y | double | r | Obtiene la coordenada y de la esquina superior izquierda del raster. |
| width | int | r | Obtiene el ancho del raster en píxeles. También se conoce como recuento de columnas. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Recorta la capa raster usando una forma (y máscara de banda). |
| [crop(masks)](#crop_masks_2) | Recorta la capa raster usando una máscara de banda). |
| [get_band(index)](#get_band_index_3) | Obtiene una banda por el índice especificado. |
| [get_extent()](#get_extent__4) | Calcula la extensión espacial de esta capa. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Convierte la columna y fila especificadas a la coordenada espacial. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Calcula estadísticas resumidas que consisten en recuento, suma, media, mínimo, máximo. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Lee los valores en la celda especificada. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Lee los valores en el bloque especificado como una matriz unidimensional. |
| [warp(options)](#warp_options_9) | Deforma la capa raster a otra. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Recorta la capa raster usando una forma (y máscara de banda).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometría representa la forma. |
| máscaras | double | Máscara para capa de recorte |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | La capa raster recortada. Si no se encuentran intersecciones devuelve <see langword=\"null\" />. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Recorta la capa raster usando una máscara de banda).

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| máscaras | double | Máscara para capa de recorte |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | La capa raster recortada. Si no se encuentran intersecciones devuelve <see langword=\"null\" />. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Obtiene una banda por el índice especificado.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| índice | int | Los números de banda comienzan en 0 y se asume que la banda es 0 si no se especifica. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Devuelve metadatos básicos sobre una banda raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Calcula la extensión espacial de esta capa.

**Returns**

| Tipo | Descripción |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Una extensión espacial de esta capa. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Convierte la columna y fila especificadas a la coordenada espacial.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cell_x | int | El valor para la columna (coordenada x). La numeración comienza en 0. |
| cell_y | int | El valor para la fila (coordenada y). La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Devuelve la coordenada x de la esquina superior izquierda dada una columna y fila. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Calcula estadísticas resumidas que consisten en recuento, suma, media, mínimo, máximo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |
| exclude_nodata_value | bool | Permite excluir valores 'nodata'. Si 'excludeNodataValue' está configurado a false, entonces se consideran todos los píxeles. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | Las estadísticas resumidas. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Lee los valores en la celda especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| cell_x | int | El valor para la columna (coordenada x). La numeración comienza en 0. |
| cell_y | int | El valor para la fila (coordenada y). La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | Los valores raster. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Lee los valores en el bloque especificado como una matriz unidimensional.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Bloque de celdas raster donde se lee el volcado. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | El volcado de valores. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Deforma la capa raster a otra.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Opciones para el procedimiento de reproyección. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | La capa raster deformada. |


