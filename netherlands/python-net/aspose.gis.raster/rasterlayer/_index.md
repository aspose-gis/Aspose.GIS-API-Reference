---
title: "RasterLayer Klasse"
type: docs
weight: 70
url: /nl/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| band_count | int | r | Haalt het aantal banden op in de rasterlaag. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Haalt de rastergrenzen op. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Haalt de cel- of pixelgrootte van het raster op. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Haalt de [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) op die deze laag heeft geïnstantieerd. |
| hoogte | int | r | Haalt de hoogte van het raster in pixels op. Ook bekend als het aantal rijen. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Haalt de waarden op die de achtergrond of 'geen data' van het raster vertegenwoordigen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Haalt een ruimtelijk referentiesysteem van het raster op.<br/>            Kan <see langword=\"null\" /> zijn als het onbekend is. |
| upper_left_x | double | r | Haalt de x-coördinaat van de linkerbovenhoek van het raster op. |
| upper_left_y | double | r | Haalt de y-coördinaat van de linkerbovenhoek van het raster op. |
| width | int | r | Haalt de breedte van het raster in pixels op. Ook bekend als het aantal kolommen. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Snijdt de rasterlaag bij met behulp van een vorm (en bandmasker). |
| [crop(masks)](#crop_masks_2) | Snijdt de rasterlaag bij met behulp van een bandmasker). |
| [get_band(index)](#get_band_index_3) | Haalt een band op op basis van de opgegeven index. |
| [get_extent()](#get_extent__4) | Berekent de ruimtelijke omvang van deze laag. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Converteert de opgegeven kolom en rij naar de ruimtelijke coördinaat. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Bereken samenvattende statistieken bestaande uit aantal, som, gemiddelde, minimum, maximum. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Leest de waarden in de opgegeven cel. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Leest de waarden in het opgegeven blok als een één-dimensionale array. |
| [warp(options)](#warp_options_9) | Vervormt de rasterlaag naar een andere. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Snijdt de rasterlaag bij met behulp van een vorm (en bandmasker).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie vertegenwoordigt de vorm. |
| maskers | double | Masker voor bijsnijdingslaag |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | De bijgesneden rasterlaag. Als er geen intersecties worden gevonden, retourneert het <see langword="null" />. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Snijdt de rasterlaag bij met behulp van een bandmasker).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| maskers | double | Masker voor bijsnijdingslaag |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | De bijgesneden rasterlaag. Als er geen intersecties worden gevonden, retourneert het <see langword="null" />. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Haalt een band op op basis van de opgegeven index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | Bandnummers beginnen bij 0 en band wordt verondersteld 0 te zijn als deze niet is gespecificeerd. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Retourneert basismetadata over een rasterband. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Berekent de ruimtelijke omvang van deze laag.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Een ruimtelijke omvang van deze laag. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Converteert de opgegeven kolom en rij naar de ruimtelijke coördinaat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cell_x | int | De waarde voor kolom (x-coördinaat). Nummering begint bij 0. |
| cell_y | int | De waarde voor rij (y-coördinaat). Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Retourneert de x-coördinaat van de linkerbovenhoek gegeven een kolom en rij. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Bereken samenvattende statistieken bestaande uit aantal, som, gemiddelde, minimum, maximum.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |
| exclude_nodata_value | bool | Staat toe om 'nodata'-waarden uit te sluiten. Als 'excludeNodataValue' is ingesteld op false, worden alle pixels beschouwd. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | De samenvattende statistieken. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Leest de waarden in de opgegeven cel.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| cell_x | int | De waarde voor kolom (x-coördinaat). Nummering begint bij 0. |
| cell_y | int | De waarde voor rij (y-coördinaat). Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | De rasterwaarden. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Leest de waarden in het opgegeven blok als een één-dimensionale array.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Blok van rastercellen waar de dump wordt gelezen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | De dump van waarden. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Vervormt de rasterlaag naar een andere.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Opties voor de reprojectieprocedure. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | De warp-rasterlaag. |


