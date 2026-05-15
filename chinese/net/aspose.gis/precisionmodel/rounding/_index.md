---
title: "PrecisionModel.Rounding"
second_title: "Aspose.GIS for .NET API 参考"
description: "PrecisionModel 方法。返回一个四舍五入精度模型。根据四舍五入精度模型，只有有限数量的数字是有效的"
type: docs
weight: 20
url: /zh/net/aspose.gis/precisionmodel/rounding/
---
## PrecisionModel.Rounding method

返回一个四舍五入的精度模型。根据四舍五入的精度模型，只有有限数量的数字是有效的。

```csharp
public static PrecisionModel Rounding(int significantDigits)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| significantDigits | Int32 | 有效数字的数量。 |

### 返回值

四舍五入精度模型。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 有效数字的数量小于 0 或大于 15。 |

## 备注

当应用于坐标时，使用以下代码来降低精度：

```csharp
double rounded = Math.Round(value, significantDigits);
```

### 另见

* class [PrecisionModel](../)
* namespace [Aspose.Gis](../../precisionmodel/)
* assembly [Aspose.GIS](../../../)


