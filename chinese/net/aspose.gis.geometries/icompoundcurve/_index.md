---
title: "接口 ICompoundCurve"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Geometries.ICompoundCurve 接口。表示一系列相连曲线的曲线，使相邻曲线在端点处相接。"
type: docs
weight: 2750
url: /zh/net/aspose.gis.geometries/icompoundcurve/
---
## ICompoundCurve interface

一条曲线，表示一系列连续的曲线，使相邻曲线在端点处相连。

```csharp
public interface ICompoundCurve : ICurve, IEnumerable<ICurve>, IEquatable<ICompoundCurve>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.gis.geometries/icompoundcurve/count/) { get; } | 获取 `ICompoundCurve` 中曲线的数量。 |
| [Item](../../aspose.gis.geometries/icompoundcurve/item/) { get; } | 获取指定索引处的 [`ICurve`](../icurve/)。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [ToEditable](../../aspose.gis.geometries/icompoundcurve/toeditable/)() | 获取此几何体的可编辑副本。 |

### 另见

* interface [ICurve](../icurve/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


