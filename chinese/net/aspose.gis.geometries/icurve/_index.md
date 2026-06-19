---
title: "接口 ICurve"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Geometries.ICurve 接口。ICurve 类型的接口 ICurve 是点的序列"
type: docs
weight: 2760
url: /zh/net/aspose.gis.geometries/icurve/
---
## ICurve interface

ICurve 类型的接口 `ICurve` 是点的序列。

```csharp
public interface ICurve : IGeometry
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [EndPoint](../../aspose.gis.geometries/icurve/endpoint/) { get; } | 返回曲线终点的副本。 |
| [IsClosed](../../aspose.gis.geometries/icurve/isclosed/) { get; } | 获取一个值，指示曲线是否闭合。如果曲线的起点等于终点，则曲线闭合。 |
| [StartPoint](../../aspose.gis.geometries/icurve/startpoint/) { get; } | 返回曲线起点的副本。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ToEditable](../../aspose.gis.geometries/icurve/toeditable/)() | 获取此几何体的可编辑副本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/icurve/tolineargeometry/#tolineargeometry)() | 使用默认的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。 |
| [ToLinearGeometry](../../aspose.gis.geometries/icurve/tolineargeometry/#tolineargeometry_1)(double) | 使用指定的 `tolerance` 获取此几何对象的近似或等效的非曲线版本。 |

### 另见

* interface [IGeometry](../igeometry/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


