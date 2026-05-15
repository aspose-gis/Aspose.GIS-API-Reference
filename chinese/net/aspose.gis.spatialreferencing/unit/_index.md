---
title: "类 Unit"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.SpatialReferencing.Unit 类。表示测量单位"
type: docs
weight: 4740
url: /zh/net/aspose.gis.spatialreferencing/unit/
---
## Unit class

表示测量单位。

```csharp
public class Unit : IdentifiableObject
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Unit](unit/)(string, double, Identifier) | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Degree](../../aspose.gis.spatialreferencing/unit/degree/) { get; } | 获取表示度的 Unit。 |
| static [Meter](../../aspose.gis.spatialreferencing/unit/meter/) { get; } | 获取表示米的 Unit。 |
| static [Radian](../../aspose.gis.spatialreferencing/unit/radian/) { get; } | 获取表示弧度的 Unit。 |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | 如果此对象的标识符是 EPSG 标识符，则返回其代码；否则返回 -1。 |
| [Factor](../../aspose.gis.spatialreferencing/unit/factor/) { get; } | 如果这是长度单位，则为米的因子；如果这是角度单位，则为弧度的因子。 |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | 此可识别对象的标识符。 |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | 此对象的名称。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Apply](../../aspose.gis.spatialreferencing/unit/apply/)(double) | 将参数转换为此实例描述的单位。 |
| [Deapply](../../aspose.gis.spatialreferencing/unit/deapply/)(double) | 将参数从此实例描述的单位转换为弧度或米。 |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | 返回表示当前对象的字符串。 |

### 另见

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


