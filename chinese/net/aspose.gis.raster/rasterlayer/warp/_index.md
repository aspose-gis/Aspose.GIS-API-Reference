---
title: "RasterLayer.Warp"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "RasterLayer 方法。将栅格图层扭曲到另一个。"
type: docs
weight: 210
url: /zh/net/aspose.gis.raster/rasterlayer/warp/
---
## RasterLayer.Warp method

将栅格图层变形到另一个。

```csharp
public RasterLayer Warp(WarpOptions options)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| options | WarpOptions | 重投影过程的选项。 |

### 返回值

扭曲后的栅格图层。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数不能为空。参数名：options。 |
| ArgumentException | 未知的源空间参考系统。 |
| InvalidOperationException | 原始图层不能是另一个 WarpRasterLayer。 |

### 另见

* class [WarpOptions](../../warpoptions/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


