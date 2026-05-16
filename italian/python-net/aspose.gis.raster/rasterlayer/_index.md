---
title: "RasterLayer Classe"
type: docs
weight: 70
url: /it/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| band_count | int | r | Ottiene il numero di bande nel livello raster. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Ottiene i limiti del raster. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Ottiene la dimensione della cella o del pixel del raster. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Ottiene il [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) che ha istanziato questo layer. |
| altezza | int | r | Ottiene l'altezza del raster in pixel. È anche conosciuta come conteggio delle righe. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Ottiene i valori che rappresentano lo sfondo o 'no data' del raster. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Ottiene un sistema di riferimento spaziale del raster.<br/>            Può essere <see langword="null" /> se è sconosciuto. |
| upper_left_x | double | r | Ottiene la coordinata x dell'angolo superiore sinistro del raster. |
| upper_left_y | double | r | Ottiene la coordinata y dell'angolo superiore sinistro del raster. |
| width | int | r | Ottiene la larghezza del raster in pixel. È anche conosciuta come conteggio delle colonne. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Ritaglia il layer raster usando una forma geometrica (e una maschera di banda). |
| [crop(masks)](#crop_masks_2) | Ritaglia il layer raster usando una maschera di banda). |
| [get_band(index)](#get_band_index_3) | Ottiene una banda tramite l'indice specificato. |
| [get_extent()](#get_extent__4) | Calcola l'estensione spaziale di questo layer. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Converte la colonna e la riga specificate nella coordinata spaziale. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Calcola le statistiche riepilogative composte da conteggio, somma, media, minimo, massimo. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Legge i valori nella cella specificata. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Legge i valori nel blocco specificato come un array monodimensionale. |
| [warp(options)](#warp_options_9) | Deforma il layer raster verso un altro. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Ritaglia il layer raster usando una forma geometrica (e una maschera di banda).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometria rappresenta la forma. |
| maschere | double | Maschera per livello di ritaglio |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Il livello raster ritagliato. Se non vengono trovate intersezioni restituisce <see langword="null" />. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Ritaglia il layer raster usando una maschera di banda).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| maschere | double | Maschera per livello di ritaglio |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Il livello raster ritagliato. Se non vengono trovate intersezioni restituisce <see langword="null" />. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Ottiene una banda tramite l'indice specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | I numeri di banda iniziano da 0 e la banda è assunta essere 0 se non specificata. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Restituisce i metadati di base su una banda raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Calcola l'estensione spaziale di questo layer.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Un'estensione spaziale di questo layer. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Converte la colonna e la riga specificate nella coordinata spaziale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cell_x | int | Il valore per la colonna (coordinata x). La numerazione inizia da 0. |
| cell_y | int | Il valore per la riga (coordinata y). La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Restituisce la coordinata x dell'angolo superiore sinistro dato una colonna e una riga. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Calcola le statistiche riepilogative composte da conteggio, somma, media, minimo, massimo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |
| exclude_nodata_value | bool | Consente di escludere i valori 'nodata'. Se 'excludeNodataValue' è impostato su false, allora tutti i pixel sono considerati. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | Le statistiche di riepilogo. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Legge i valori nella cella specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| cell_x | int | Il valore per la colonna (coordinata x). La numerazione inizia da 0. |
| cell_y | int | Il valore per la riga (coordinata y). La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | I valori raster. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Legge i valori nel blocco specificato come un array monodimensionale.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Blocco di celle raster da cui viene letto il dump. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | Il dump dei valori. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Deforma il layer raster verso un altro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Opzioni per la procedura di riproiezione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Il livello raster di deformazione. |


