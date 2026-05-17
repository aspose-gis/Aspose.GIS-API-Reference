---
title: "Класс MapOptions"
type: docs
weight: 30
url: /ru/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | Инициализирует новый экземпляр класса MapOptions |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Фоновый цвет карты. По умолчанию System.Drawing.Color.Transparent. |
| height | int | r/w | Визуальная высота карты. По умолчанию 400. Используется, когда [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | Коллекция параметров для векторных слоёв, представляемых Aspose.Gis.GeoTools.LayersMap.MapLayerOptions. |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | Коллекция параметров для растровых слоёв, представляемых Aspose.Gis.GeoTools.LayersMap.MapRasterOptions. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | Рендерер для использования. По умолчанию Aspose.Gis.Rendering.Renders.Jpeg. |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | Режим размера. По умолчанию [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Пространственная привязка. По умолчанию Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator. |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | Параметры тайлов. |
| width | int | r/w | Визуальная ширина карты. По умолчанию 400. Используется, когда [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/). |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

Инициализирует новый экземпляр класса MapOptions

