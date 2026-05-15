---
title: "فئة MapOptions"
type: docs
weight: 30
url: /ar/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | ينشئ مثلاً جديداً من فئة MapOptions |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | لون الخلفية للخريطة. القيمة الافتراضية هي System.Drawing.Color.Transparent. |
| height | int | r/w | الارتفاع البصري للخريطة. القيمة الافتراضية هي 400. يُستخدم عندما يكون [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | مجموعة من الخيارات لطبقات المتجهات لتمثيلها بواسطة Aspose.Gis.GeoTools.LayersMap.MapLayerOptions. |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | مجموعة من الخيارات لطبقات الصور النقطية لتمثيلها بواسطة Aspose.Gis.GeoTools.LayersMap.MapRasterOptions. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | المُعالج المستخدم. القيمة الافتراضية هي Aspose.Gis.Rendering.Renders.Jpeg. |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | وضع الحجم. القيمة الافتراضية هي [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | المرجع المكاني. القيمة الافتراضية هي Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator. |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | خيارات البلاط. |
| width | int | r/w | العرض البصري للخريطة. القيمة الافتراضية هي 400. يُستخدم عندما يكون [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

ينشئ مثلاً جديداً من فئة MapOptions

