---
title: "TopoJsonDriver.SupportsSpatialReferenceSystem"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "TopoJsonDriver 方法。确定指定的空间参考系统是否被驱动程序支持"
type: docs
weight: 60
url: /zh/net/aspose.gis.formats.topojson/topojsondriver/supportsspatialreferencesystem/
---
## TopoJsonDriver.SupportsSpatialReferenceSystem method

确定指定的空间参考系统是否受此驱动程序支持。

```csharp
public override bool SupportsSpatialReferenceSystem(SpatialReferenceSystem spatialReferenceSystem)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

布尔值，指示指定的空间参考系统是否受到驱动程序支持。

## 备注

对于 TopoJSON，唯一受支持的空间参考系统是 'null'，因为在 TopoJSON 文件中没有办法存储空间参考系统信息，并且 TopoJSON 规范未指定 TopoJSON 文件中几何体的空间参考系统是什么。

### 另见

* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem/)
* class [TopoJsonDriver](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsondriver/)
* assembly [Aspose.GIS](../../../)


