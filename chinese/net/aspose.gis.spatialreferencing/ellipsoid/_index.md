---
title: "类 Ellipsoid"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.SpatialReferencing.Ellipsoid 类。Ellipsoid 表示一个近似地球的椭球体。"
type: docs
weight: 4520
url: /zh/net/aspose.gis.spatialreferencing/ellipsoid/
---
## Ellipsoid class

椭球体表示一种近似地球的椭球体。

```csharp
public class Ellipsoid : IdentifiableObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Ellipsoid](ellipsoid/)(string, double, double, Identifier) | 创建新的 Ellipsoid。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Airy](../../aspose.gis.spatialreferencing/ellipsoid/airy/) { get; } | Airy 椭球体。 |
| static [Grs80](../../aspose.gis.spatialreferencing/ellipsoid/grs80/) { get; } | GRS 1980 椭球体。 |
| static [Wgs72](../../aspose.gis.spatialreferencing/ellipsoid/wgs72/) { get; } | WGS 72 椭球体。 |
| static [Wgs84](../../aspose.gis.spatialreferencing/ellipsoid/wgs84/) { get; } | WGS 84 椭球体。 |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | 此可识别对象的标识符。 |
| [InverseFlattening](../../aspose.gis.spatialreferencing/ellipsoid/inverseflattening/) { get; } | 椭球体的倒数扁率。如果是球体则为 0。 |
| [IsSphere](../../aspose.gis.spatialreferencing/ellipsoid/issphere/) { get; } | 检测此椭球体是否为球体。 |
| [IsValid](../../aspose.gis.spatialreferencing/ellipsoid/isvalid/) { get; } | 检测椭球体是否有效：其半长轴大于 0，且逆扁率为正或等于 0。 |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | 此对象的名称。 |
| [SemiMajorAxis](../../aspose.gis.spatialreferencing/ellipsoid/semimajoraxis/) { get; } | 椭球体的半长轴。 |
| [SemiMinorAxis](../../aspose.gis.spatialreferencing/ellipsoid/semiminoraxis/) { get; } | 椭球体的半短轴。如果是球体，则等于半长轴。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [IsEquivalent](../../aspose.gis.spatialreferencing/ellipsoid/isequivalent/)(Ellipsoid) | 确定两个椭球体是否等价。如果椭球体 A 等价于椭球体 B，则它们具有相同的半长轴和逆扁率。 |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | 返回表示当前对象的字符串。 |
| static [IsEquivalent](../../aspose.gis.spatialreferencing/ellipsoid/isequivalent/)(Ellipsoid, Ellipsoid) | 确定两个椭球体是否等价。如果椭球体 A 等价于椭球体 B，则它们具有相同的半长轴和逆扁率。 |

### 另见

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


