---
title: "MapOptions Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | MapOptions sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Haritanın arka plan rengi. Varsayılan değer System.Drawing.Color.Transparent. |
| height | int | r/w | Haritanın görsel yüksekliği. Varsayılan değer 400. [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) kullanıldığında. |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | Aspose.Gis.GeoTools.LayersMap.MapLayerOptions tarafından temsil edilecek vektör katmanları için bir seçenek koleksiyonu. |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | Aspose.Gis.GeoTools.LayersMap.MapRasterOptions tarafından temsil edilecek raster katmanları için bir seçenek koleksiyonu. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | Kullanılacak renderleyici. Varsayılan değer Aspose.Gis.Rendering.Renders.Jpeg. |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | Boyut Modu. Varsayılan değer [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Uzamsal Referans. Varsayılan değer Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator. |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | Döşeme seçenekleri. |
| width | int | r/w | Haritanın görsel genişliği. Varsayılan değer 400. [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) kullanıldığında. |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

MapOptions sınıfının yeni bir örneğini başlatır

