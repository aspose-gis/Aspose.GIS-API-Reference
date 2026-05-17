---
title: "MapOptions klass"
type: docs
weight: 30
url: /sv/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | Initierar en ny instans av klassen MapOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | läs/skriv | Bakgrundsfärg för kartan. Standardvärde är System.Drawing.Color.Transparent. |
| height | int | r/w | Visuell höjd för kartan. Standardvärde är 400. Används när [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | En samling alternativ för vektorlager att representera med Aspose.Gis.GeoTools.LayersMap.MapLayerOptions. |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | En samling alternativ för rasterlager att representera med Aspose.Gis.GeoTools.LayersMap.MapRasterOptions. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | Renderare att använda. Standardvärde är Aspose.Gis.Rendering.Renders.Jpeg. |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | Storleksläge. Standardvärde är [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Rumslig referens. Standardvärde är Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator. |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | Tile‑alternativ. |
| width | int | r/w | Visuell bredd för kartan. Standardvärde är 400. Används när [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

Initierar en ny instans av klassen MapOptions

