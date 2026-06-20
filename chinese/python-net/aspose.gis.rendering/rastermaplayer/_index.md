---
title: "RasterMapLayer 类"
type: docs
weight: 250
url: /zh/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | 用于渲染栅格单元的 Colorizer。 |
| 不透明度 | double | r/w | 图层的不透明度。 |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | 指定地图上图层的扭曲选项。 |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | 栅格图层。 |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | 用于渲染图层的 Symbolizer。如果 <see langword="null" />，将使用默认的 colorizer。 |
| keep_open | bool | <see langword="true" /> 在 [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) 对象释放后保持图层打开；否则，<see langword="false" />。 |

