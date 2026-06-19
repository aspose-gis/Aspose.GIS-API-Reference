---
title: "RasterMapLayer.RasterMapLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "RasterMapLayer 构造函数。创建新实例"
type: docs
weight: 10
url: /zh/net/aspose.gis.rendering/rastermaplayer/rastermaplayer/
---
## RasterMapLayer constructor

创建新实例。

```csharp
public RasterMapLayer(RasterLayer layer, RasterColorizer colorizer = null, bool keepOpen = false)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | RasterLayer | Raster 图层。 |
| colorizer | RasterColorizer | 用于渲染图层的 Symbolizer。如果 `null`，将使用默认的 colorizer。 |
| keepOpen | Boolean | `true` 表示在 [`VectorMapLayer`](../../vectormaplayer/) 对象被释放后保持图层打开；否则为 `false`。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 图层为 `null`。 |

### 另见

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [RasterColorizer](../../../aspose.gis.rendering.colorizers/rastercolorizer/)
* class [RasterMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../rastermaplayer/)
* assembly [Aspose.GIS](../../../)


