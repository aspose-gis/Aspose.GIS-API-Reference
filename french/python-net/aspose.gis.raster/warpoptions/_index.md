---
title: "Classe WarpOptions"
type: docs
weight: 100
url: /fr/python-net/aspose.gis.raster/warpoptions/
---

**Summary:** Options for raster warping.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.WarpOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WarpOptions()](#WarpOptions__1) | Initialise une nouvelle instance de la classe WarpOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_height | double | r/w | Spécifie une nouvelle hauteur de la cellule raster (dans les unités géoréférencées cibles).<br/>            Si la valeur est définie à 0, le [WarpOptions.cell_height](/psd/python-net/aspose.gis.raster/warpoptions/) est calculé automatiquement. La valeur par défaut est "0". |
| cell_width | double | r/w | Spécifie une nouvelle largeur de la cellule raster (dans les unités géoréférencées cibles).<br/>            Si la valeur est définie à 0, le [WarpOptions.cell_width](/psd/python-net/aspose.gis.raster/warpoptions/) est calculé automatiquement. La valeur par défaut est "0". |
| default_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Spécifie une valeur pour une référence spatiale source si elle est manquante. |
| hauteur | int | r/w | Spécifie la hauteur du raster de sortie en pixels et colonnes.<br/>            Si la valeur est définie à 0, la hauteur est calculée automatiquement. La valeur par défaut est "0". |
| target_extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Spécifie les limites de la couche raster à déformer.<br/>            Si défini à <see langword="null" />, l'étendue est calculée pendant la déformation pour inclure toutes les cellules du raster. |
| target_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Spécifie la référence spatiale cible.<br/>            Si défini à <see langword="null" />, la référence spatiale par défaut ou source est utilisée. |
| width | int | r/w | Spécifie la largeur du raster de sortie en pixels et colonnes.<br/>            Si la valeur est définie à 0, la largeur est calculée automatiquement. La valeur par défaut est "0". |


### Constructor: WarpOptions() {#WarpOptions__1}


```
 WarpOptions() 
```

Initialise une nouvelle instance de la classe WarpOptions

