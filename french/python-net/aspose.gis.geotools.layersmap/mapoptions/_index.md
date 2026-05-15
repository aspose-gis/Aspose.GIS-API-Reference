---
title: "Classe MapOptions"
type: docs
weight: 30
url: /fr/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | Initialise une nouvelle instance de la classe MapOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Couleur d'arrière-plan de la carte. La valeur par défaut est System.Drawing.Color.Transparent. |
| height | int | r/w | Hauteur visuelle de la carte. La valeur par défaut est 400. Utilisée lorsque [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | Une collection d'options pour les couches vectorielles à représenter par Aspose.Gis.GeoTools.LayersMap.MapLayerOptions. |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | Une collection d'options pour les couches raster à représenter par Aspose.Gis.GeoTools.LayersMap.MapRasterOptions. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | Moteur de rendu à utiliser. La valeur par défaut est Aspose.Gis.Rendering.Renders.Jpeg. |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | Mode de taille. La valeur par défaut est [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Référence spatiale. La valeur par défaut est Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator. |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | Options de tuiles. |
| width | int | r/w | Largeur visuelle de la carte. La valeur par défaut est 400. Utilisée lorsque [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

Initialise une nouvelle instance de la classe MapOptions

