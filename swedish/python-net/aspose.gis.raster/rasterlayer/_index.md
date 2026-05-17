---
title: "RasterLayer-klass"
type: docs
weight: 70
url: /sv/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| band_count | int | r | Hämtar antalet band i rasterlagret. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Hämtar rastergränserna. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Hämtar cell- eller pixelstorleken för raster. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Hämtar [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) som instansierade detta lager. |
| höjd | int | r | Hämtar rasterhöjden i pixlar. Den är också känd som radantal. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Hämtar värdena som representerar bakgrund eller 'ingen data' för raster. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Hämtar ett rumsligt referenssystem för raster.<br/>            Kan vara <see langword="null" /> om det är okänt. |
| upper_left_x | double | r | Hämtar x-koordinaten för rasterns övre vänstra hörn. |
| upper_left_y | double | r | Hämtar y-koordinaten för rasterns övre vänstra hörn. |
| bredd | int | r | Hämtar rasterbredden i pixlar. Den är också känd som kolumnantal. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Beskär rasterlagret med en form (och bandmask). |
| [crop(masks)](#crop_masks_2) | Beskär rasterlagret med en bandmask). |
| [get_band(index)](#get_band_index_3) | Hämtar ett band med det angivna indexet. |
| [get_extent()](#get_extent__4) | Beräknar ett rumsligt omfång för detta lager. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Omvandlar den angivna kolumnen och raden till den rumsliga koordinaten. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Beräkna sammanfattande statistik bestående av antal, summa, medelvärde, min, max. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Läser värdena i den angivna cellen. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Läser värdena i det angivna blocket som en endimensionell array. |
| [warp(options)](#warp_options_9) | Warpar rasterlagret till ett annat. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Beskär rasterlagret med en form (och bandmask).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri representerade formformen. |
| masker | double | Mask för beskärningslager |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Det beskurna rasterlagret. Om inga korsningar hittas returneras <see langword="null" />. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Beskär rasterlagret med en bandmask).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| masker | double | Mask för beskärningslager |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Det beskurna rasterlagret. Om inga korsningar hittas returneras <see langword="null" />. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Hämtar ett band med det angivna indexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Bandnummer börjar på 0 och band antas vara 0 om det inte specificeras. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Returnerar grundläggande metadata om ett rasterband. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Beräknar ett rumsligt omfång för detta lager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ett rumsligt omfång för detta lager. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Omvandlar den angivna kolumnen och raden till den rumsliga koordinaten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cell_x | int | Värdet för kolumn (x-koordinat). Numrering börjar på 0. |
| cell_y | int | Värdet för rad (y-koordinat). Numrering börjar på 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Returnerar x-koordinaten för övre vänstra hörnet givet en kolumn och rad. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Beräkna sammanfattande statistik bestående av antal, summa, medelvärde, min, max.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |
| exclude_nodata_value | bool | Tillåter att exkludera 'nodata'-värden. Om 'excludeNodataValue' är satt till false, betraktas alla pixlar. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | Sammanfattande statistik. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Läser värdena i den angivna cellen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| cell_x | int | Värdet för kolumn (x-koordinat). Numrering börjar på 0. |
| cell_y | int | Värdet för rad (y-koordinat). Numrering börjar på 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | Rastervärdena. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Läser värdena i det angivna blocket som en endimensionell array.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Block av rasterceller där dump läses. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | Dumpen av värden. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Warpar rasterlagret till ett annat.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Alternativ för reprojektionproceduren. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Warp-rasterlagret. |


