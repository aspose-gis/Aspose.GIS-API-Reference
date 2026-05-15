---
title: "Classe RasterLayer"
type: docs
weight: 70
url: /fr/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| band_count | int | r | Obtient le nombre de bandes dans la couche raster. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Obtient les limites du raster. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Obtient la taille de la cellule ou du pixel du raster. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Obtient le [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) qui a instancié cette couche. |
| hauteur | int | r | Obtient la hauteur du raster en pixels. Elle est également connue sous le nom de nombre de lignes. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Obtient les valeurs qui représentent l'arrière-plan ou « no data » du raster. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Obtient un système de référence spatiale du raster.<br/>            Peut être <see langword=\"null\" /> s'il est inconnu. |
| upper_left_x | double | r | Obtient la coordonnée x du coin supérieur gauche du raster. |
| upper_left_y | double | r | Obtient la coordonnée y du coin supérieur gauche du raster. |
| width | int | r | Obtient la largeur du raster en pixels. Elle est également connue sous le nom de nombre de colonnes. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Recadre la couche raster en utilisant une forme (et un masque de bande). |
| [crop(masks)](#crop_masks_2) | Recadre la couche raster en utilisant un masque de bande). |
| [get_band(index)](#get_band_index_3) | Obtient une bande par l'index spécifié. |
| [get_extent()](#get_extent__4) | Calcule l'étendue spatiale de cette couche. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Convertit la colonne et la ligne spécifiées en coordonnées spatiales. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Calcule les statistiques récapitulatives composées du nombre, de la somme, de la moyenne, du minimum et du maximum. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Lit les valeurs dans la cellule spécifiée. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Lit les valeurs dans le bloc spécifié sous forme d'un tableau à une dimension. |
| [warp(options)](#warp_options_9) | Déforme la couche raster vers une autre. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Recadre la couche raster en utilisant une forme (et un masque de bande).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La géométrie représente la forme. |
| masques | double | Masque pour la couche de recadrage |

**Returns**

| Type | Description |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | La couche raster recadrée. Si aucune intersection n'est trouvée, renvoie <see langword="null" />. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Recadre la couche raster en utilisant un masque de bande).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| masques | double | Masque pour la couche de recadrage |

**Returns**

| Type | Description |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | La couche raster recadrée. Si aucune intersection n'est trouvée, renvoie <see langword="null" />. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Obtient une bande par l'index spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | Les numéros de bande commencent à 0 et la bande est supposée être 0 si elle n'est pas spécifiée. |

**Returns**

| Type | Description |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Renvoie les métadonnées de base d'une bande raster. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Calcule l'étendue spatiale de cette couche.

**Returns**

| Type | Description |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Une étendue spatiale de cette couche. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Convertit la colonne et la ligne spécifiées en coordonnées spatiales.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cell_x | int | La valeur pour la colonne (coordonnée x). Le comptage commence à 0. |
| cell_y | int | La valeur pour la ligne (coordonnée y). Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Renvoie la coordonnée x du coin supérieur gauche à partir d'une colonne et d'une ligne. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Calcule les statistiques récapitulatives composées du nombre, de la somme, de la moyenne, du minimum et du maximum.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |
| exclude_nodata_value | bool | Permet d'exclure les valeurs 'nodata'. Si 'excludeNodataValue' est défini sur false, alors tous les pixels sont pris en compte. |

**Returns**

| Type | Description |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | Les statistiques récapitulatives. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Lit les valeurs dans la cellule spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| cell_x | int | La valeur pour la colonne (coordonnée x). Le comptage commence à 0. |
| cell_y | int | La valeur pour la ligne (coordonnée y). Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | Les valeurs raster. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Lit les valeurs dans le bloc spécifié sous forme d'un tableau à une dimension.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Bloc de cellules raster où le vidage est lu. |

**Returns**

| Type | Description |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | Le vidage des valeurs. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Déforme la couche raster vers une autre.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Options pour la procédure de reprojection. |

**Returns**

| Type | Description |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | La couche raster de déformation. |


