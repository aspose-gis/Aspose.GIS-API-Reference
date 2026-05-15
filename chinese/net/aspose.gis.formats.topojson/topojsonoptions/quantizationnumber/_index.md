---
title: "TopoJsonOptions.QuantizationNumber"
second_title: "Aspose.GIS for .NET API 参考"
description: "TopoJsonOptions 属性。指定用于在输出 TopoJSON 中量化坐标和对弧线进行 delta 编码的量化数字"
type: docs
weight: 50
url: /zh/net/aspose.gis.formats.topojson/topojsonoptions/quantizationnumber/
---
## TopoJsonOptions.QuantizationNumber property

指定用于在输出 TopoJSON 中量化坐标并对弧线进行增量编码的量化数值。

```csharp
public int? QuantizationNumber { get; set; }
```

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 参数小于二。 |

## 备注

这是写入选项——它不影响读取。此选项与 [`Transform`](../transform/) 互斥——这两个选项只能有一个不为 `null`。如果此项不为 `null`——输出 TopoJSON 坐标将被量化，弧线将使用指定的量化数字进行 delta 编码。量化数字决定了在生成的量化坐标中每个维度可表达的最大值；通常选择十的幂。默认值为 `null`。

### 另见

* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


