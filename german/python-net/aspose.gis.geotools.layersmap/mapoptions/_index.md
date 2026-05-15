---
title: "MapOptions Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | Initialisiert eine neue Instanz der MapOptions-Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Hintergrundfarbe der Karte. Standardwert ist System.Drawing.Color.Transparent. |
| height | int | r/w | Visuelle Höhe der Karte. Standardwert ist 400. Wird verwendet, wenn [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | Eine Sammlung von Optionen für Vektorebenen, die durch Aspose.Gis.GeoTools.LayersMap.MapLayerOptions dargestellt werden. |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | Eine Sammlung von Optionen für Rasterebenen, die durch Aspose.Gis.GeoTools.LayersMap.MapRasterOptions dargestellt werden. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | Renderer zu verwenden. Standardwert ist Aspose.Gis.Rendering.Renders.Jpeg. |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | Größenmodus. Standardwert ist [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Räumliche Referenz. Standardwert ist Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator. |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | Kacheloptionen. |
| width | int | r/w | Visuelle Breite der Karte. Standardwert ist 400. Wird verwendet, wenn [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

Initialisiert eine neue Instanz der MapOptions-Klasse

