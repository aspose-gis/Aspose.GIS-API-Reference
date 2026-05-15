---
title: "接口 ICircularString"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Geometries.ICircularString 接口。一个在点之间进行圆形插值的多顶点曲线"
type: docs
weight: 2740
url: /zh/net/aspose.gis.geometries/icircularstring/
---
## ICircularString interface

一个在点之间具有圆形插值的多顶点曲线。

```csharp
public interface ICircularString : ICurve, IEquatable<ICircularString>, IReadOnlyList<IPoint>
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [ToEditable](../../aspose.gis.geometries/icircularstring/toeditable/)() | 获取此几何体的可编辑副本。 |

## 备注

`CircularString` 由一个或多个首尾相连的圆弧段组成。前三个点定义第一段。第一个点是弧的起始点。第二个点是弧上除起始点和终止点之外的任意中间点。第三个点是弧的终止点。后续的弧仅通过其中间点和终止点定义，因为起始点隐式为前一段的终止点。

### 另见

* interface [ICurve](../icurve/)
* interface [IPoint](../ipoint/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


