---
title: Measurement
second_title: Aspose.GIS for .NET API 参考
description: 表示渲染测量的数字
type: docs
weight: 1630
url: /zh/net/aspose.gis.rendering/measurement/
---
## Measurement structure

表示渲染测量的数字。

```csharp
public struct Measurement
```

## 构造函数

| 姓名 | 描述 |
| --- | --- |
| [Measurement](measurement)(double, Unit) | 创建新实例。 |

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [Zero](../../aspose.gis.rendering/measurement/zero) { get; } | 零长度的度量。 |
| [Unit](../../aspose.gis.rendering/measurement/unit) { get; } | 度量单位。 |
| [Value](../../aspose.gis.rendering/measurement/value) { get; } | 表示测量长度的数字。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Inches](../../aspose.gis.rendering/measurement/inches)(double) | 返回` 测量` 的新实例，以英寸为单位。 |
| static [MapUnits](../../aspose.gis.rendering/measurement/mapunits)(double) | 返回` Measurement` 的新实例，它表示地图空间参考单位中的长度。 |
| static [MetersOnEarth](../../aspose.gis.rendering/measurement/metersonearth)(double) | 返回` 测量` 的新实例，它表示地球上的长度（以米为单位）。 |
| static [Millimeters](../../aspose.gis.rendering/measurement/millimeters)(double) | 返回` Measurement` 的新实例，以毫米为单位。 |
| static [Pixels](../../aspose.gis.rendering/measurement/pixels)(double) | 返回` Measurement` 的新实例，表示长度（以像素为单位）。 |
| static [Points](../../aspose.gis.rendering/measurement/points)(double) | 返回` 测量` 的新实例，它表示以点为单位的长度。 |
| override [ToString](../../aspose.gis.rendering/measurement/tostring)() | 返回此实例转换为字符串。 |
| [operator /](../../aspose.gis.rendering/measurement/op_division) | 将测量值除以因子。 |
| [implicit operator](../../aspose.gis.rendering/measurement/op_implicit) | 返回` Measurement` 的新实例，表示长度（以像素为单位）。 |
| [operator *](../../aspose.gis.rendering/measurement/op_multiply) | 将测量值乘以因子。 |

### 也可以看看

* 命名空间 [Aspose.Gis.Rendering](../../aspose.gis.rendering)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
