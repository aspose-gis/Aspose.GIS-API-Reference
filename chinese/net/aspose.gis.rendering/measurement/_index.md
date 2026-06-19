---
title: "结构体 Measurement"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Rendering.Measurement 结构体。表示渲染度量的数值"
type: docs
weight: 4190
url: /zh/net/aspose.gis.rendering/measurement/
---
## Measurement structure

指示渲染度量的数字。

```csharp
public struct Measurement
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Measurement](measurement/)(double, Unit) | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Zero](../../aspose.gis.rendering/measurement/zero/) { get; } | 零长度的度量。 |
| [Unit](../../aspose.gis.rendering/measurement/unit/) { get; } | 计量单位。 |
| [Value](../../aspose.gis.rendering/measurement/value/) { get; } | 表示度量长度的数值。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Inches](../../aspose.gis.rendering/measurement/inches/)(double) | 返回一个表示英寸长度的 `Measurement` 新实例。 |
| static [MapUnits](../../aspose.gis.rendering/measurement/mapunits/)(double) | 返回一个表示地图空间参考单位长度的 `Measurement` 新实例。 |
| static [MetersOnEarth](../../aspose.gis.rendering/measurement/metersonearth/)(double) | 返回一个表示地球上米长度的 `Measurement` 新实例。 |
| static [Millimeters](../../aspose.gis.rendering/measurement/millimeters/)(double) | 返回一个表示毫米长度的 `Measurement` 新实例。 |
| static [Pixels](../../aspose.gis.rendering/measurement/pixels/)(double) | 返回一个表示像素长度的 `Measurement` 新实例。 |
| static [Points](../../aspose.gis.rendering/measurement/points/)(double) | 返回一个新的 `Measurement` 实例，表示以点为单位的长度。 |
| override [ToString](../../aspose.gis.rendering/measurement/tostring/)() | 返回此实例转换为字符串。 |
| [operator /](../../aspose.gis.rendering/measurement/op_division/) | 将测量值除以因子。 |
| [implicit operator](../../aspose.gis.rendering/measurement/op_implicit/) | 返回一个表示像素长度的 `Measurement` 新实例。 |
| [operator *](../../aspose.gis.rendering/measurement/op_multiply/) | 将测量值乘以因子。 |

### 另见

* namespace [Aspose.Gis.Rendering](../../aspose.gis.rendering/)
* assembly [Aspose.GIS](../../)


