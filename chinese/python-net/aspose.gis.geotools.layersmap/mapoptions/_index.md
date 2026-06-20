---
title: "MapOptions 类"
type: docs
weight: 30
url: /zh/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | 初始化 MapOptions 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | 地图的背景颜色。默认值为 System.Drawing.Color.Transparent。 |
| height | int | r/w | 地图的可视高度。默认值为 400。当使用 [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) 时使用。 |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | 用于表示矢量图层的选项集合，由 Aspose.Gis.GeoTools.LayersMap.MapLayerOptions 提供。 |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | 用于表示栅格图层的选项集合，由 Aspose.Gis.GeoTools.LayersMap.MapRasterOptions 提供。 |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | 要使用的渲染器。默认值为 Aspose.Gis.Rendering.Renders.Jpeg。 |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | 尺寸模式。默认值为 [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 空间参考。默认值为 Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator。 |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | 瓦片选项。 |
| width | int | r/w | 地图的可视宽度。默认值为 400。当使用 [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) 时使用。 |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

初始化 MapOptions 类的新实例

