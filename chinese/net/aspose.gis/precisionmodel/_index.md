---
title: "类 PrecisionModel"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.PrecisionModel 类。PrecisionModel 指定坐标中的有效数字位数"
type: docs
weight: 3700
url: /zh/net/aspose.gis/precisionmodel/
---
## PrecisionModel class

`PrecisionModel` 指定坐标中的有效数字位数。

```csharp
public abstract class PrecisionModel : IEquatable<PrecisionModel>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| static [Exact](../../aspose.gis/precisionmodel/exact/) { get; } | 返回一个精确的精度模型。根据精确的精度模型，double 值中的所有数字都是有效的。 |
| [IsExact](../../aspose.gis/precisionmodel/isexact/) { get; } | 获取一个值，指示此精度模型是否为精确。 |
| [IsRounding](../../aspose.gis/precisionmodel/isrounding/) { get; } | 获取一个值，指示此精度模型是否为四舍五入。 |
| abstract [SignificantDigits](../../aspose.gis/precisionmodel/significantdigits/) { get; } | 如果是四舍五入，则获取精度模型中的有效数字位数。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Rounding](../../aspose.gis/precisionmodel/rounding/)(int) | 返回一个四舍五入的精度模型。根据四舍五入的精度模型，只有有限数量的数字是有效的。 |
| override [Equals](../../aspose.gis/precisionmodel/equals/#equals_1)(object) | 指示当前对象是否等于同类型的另一个对象。 |
| [Equals](../../aspose.gis/precisionmodel/equals/#equals)(PrecisionModel) | 指示当前对象是否等于同类型的另一个对象。 |
| override [GetHashCode](../../aspose.gis/precisionmodel/gethashcode/)() | 用作默认的哈希函数。 |
| [operator ==](../../aspose.gis/precisionmodel/op_equality/) | 实现运算符 ==。 |
| [operator !=](../../aspose.gis/precisionmodel/op_inequality/) | 实现运算符 !=。 |

## 备注

PrecisionModel 有两种类型：精确 `PrecisionModel`（所有数字都是有效的）；四舍五入 `PrecisionModel`（部分数字是有效的）。可以通过 [`DriverOptions`](../driveroptions/) 将 `PrecisionModel` 设置到 [`VectorLayer`](../vectorlayer/)，以在写入或读取几何体时对坐标进行四舍五入。

### 另见

* property [XYPrecisionModel](../driveroptions/xyprecisionmodel/)
* property [ZPrecisionModel](../driveroptions/zprecisionmodel/)
* property [MPrecisionModel](../driveroptions/mprecisionmodel/)
* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


