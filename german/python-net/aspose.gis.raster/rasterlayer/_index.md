---
title: "RasterLayer Klasse"
type: docs
weight: 70
url: /de/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| band_count | int | r | Gibt die Anzahl der Bänder im Rasterlayer zurück. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Gibt die Rastergrenzen zurück. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Gibt die Zell- oder Pixelgröße des Rasters zurück. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Gibt den [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) zurück, der diesen Layer instanziiert hat. |
| Höhe | int | r | Gibt die Höhe des Rasters in Pixeln zurück. Außerdem ist sie als Zeilenanzahl bekannt. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Gibt die Werte zurück, die den Hintergrund oder 'keine Daten' des Rasters darstellen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Gibt ein räumliches Referenzsystem des Rasters zurück.<br/>            Kann <see langword=\"null\" /> sein, wenn es unbekannt ist. |
| upper_left_x | double | r | Gibt die x-Koordinate der oberen linken Ecke des Rasters zurück. |
| upper_left_y | double | r | Gibt die y-Koordinate der oberen linken Ecke des Rasters zurück. |
| width | int | r | Gibt die Breite des Rasters in Pixeln zurück. Außerdem ist sie als Spaltenanzahl bekannt. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Beschneidet den Rasterlayer mit einer Form (und Bandmaske). |
| [crop(masks)](#crop_masks_2) | Beschneidet den Rasterlayer mit einer Bandmaske). |
| [get_band(index)](#get_band_index_3) | Gibt ein Band anhand des angegebenen Index zurück. |
| [get_extent()](#get_extent__4) | Berechnet den räumlichen Umfang dieses Layers. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Wandelt die angegebene Spalte und Zeile in die räumliche Koordinate um. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Berechnet zusammenfassende Statistiken bestehend aus Anzahl, Summe, Mittelwert, Minimum, Maximum. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Liest die Werte in der angegebenen Zelle. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Liest die Werte im angegebenen Block als eindimensionales Array. |
| [warp(options)](#warp_options_9) | Verformt den Rasterlayer zu einem anderen. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Beschneidet den Rasterlayer mit einer Form (und Bandmaske).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie stellt die Form dar. |
| Masken | double | Maske für Beschneidungsebene |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Die beschnittene Rasterebene. Wenn keine Schnittpunkte gefunden werden, wird <see langword="null" /> zurückgegeben. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Beschneidet den Rasterlayer mit einer Bandmaske).

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Masken | double | Maske für Beschneidungsebene |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Die beschnittene Rasterebene. Wenn keine Schnittpunkte gefunden werden, wird <see langword="null" /> zurückgegeben. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Gibt ein Band anhand des angegebenen Index zurück.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Bandnummern beginnen bei 0 und das Band wird angenommen, dass es 0 ist, wenn nicht angegeben. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Gibt grundlegende Metadaten zu einem Rasterband zurück. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Berechnet den räumlichen Umfang dieses Layers.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ein räumlicher Ausdehnungsbereich dieser Ebene. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Wandelt die angegebene Spalte und Zeile in die räumliche Koordinate um.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cell_x | int | Der Wert für die Spalte (x-Koordinate). Die Nummerierung beginnt bei 0. |
| cell_y | int | Der Wert für die Zeile (y-Koordinate). Die Nummerierung beginnt bei 0. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Gibt die x-Koordinate der oberen linken Ecke zurück, basierend auf einer Spalte und Zeile. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Berechnet zusammenfassende Statistiken bestehend aus Anzahl, Summe, Mittelwert, Minimum, Maximum.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| band_index | int | Der Index des Bands. Die Nummerierung beginnt bei 0. |
| exclude_nodata_value | bool | Ermöglicht das Ausschließen von 'nodata'-Werten. Wenn 'excludeNodataValue' auf false gesetzt ist, werden alle Pixel berücksichtigt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | Die zusammenfassenden Statistiken. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Liest die Werte in der angegebenen Zelle.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| cell_x | int | Der Wert für die Spalte (x-Koordinate). Die Nummerierung beginnt bei 0. |
| cell_y | int | Der Wert für die Zeile (y-Koordinate). Die Nummerierung beginnt bei 0. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | Die Rasterwerte. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Liest die Werte im angegebenen Block als eindimensionales Array.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Block von Rasterzellen, aus dem das Dump gelesen wird. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | Der Dump der Werte. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Verformt den Rasterlayer zu einem anderen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Optionen für das Reprojektionsverfahren. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Die Warp-Rasterebene. |


