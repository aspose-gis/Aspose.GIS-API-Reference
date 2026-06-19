---
title: "接口 IPolygon"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Geometries.IPolygon 接口。一个其边界由线性环定义的 IPolygon"
type: docs
weight: 2880
url: /zh/net/aspose.gis.geometries/ipolygon/
---
## IPolygon interface

一个其边界由线性环定义的 `IPolygon`。

```csharp
public interface IPolygon : ICurvePolygon, IEquatable<IPolygon>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [ExteriorRing](../../aspose.gis.geometries/ipolygon/exteriorring/) { get; } | 获取外环。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetInteriorRing](../../aspose.gis.geometries/ipolygon/getinteriorring/)(int) | 按索引获取内部环。 |
| [ToEditable](../../aspose.gis.geometries/ipolygon/toeditable/)() | 获取此几何体的可编辑副本。 |

### 另见

* interface [ICurvePolygon](../icurvepolygon/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


