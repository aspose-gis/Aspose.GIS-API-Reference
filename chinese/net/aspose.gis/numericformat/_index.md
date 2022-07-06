---
title: NumericFormat
second_title: Aspose.GIS for .NET API 参考
description: NumericFormat./numericformat用于格式化文本中的常见数字类型
type: docs
weight: 1180
url: /zh/net/aspose.gis/numericformat/
---
## NumericFormat class

[`NumericFormat`](../numericformat)用于格式化文本中的常见数字类型。

```csharp
public abstract class NumericFormat
```

## 特性

| 姓名 | 描述 |
| --- | --- |
| static [RoundTrip](../../aspose.gis/numericformat/roundtrip) { get; } | 转换并尝试确保将转换为 字符串的数值解析回相同的数值。 |

## 方法

| 姓名 | 描述 |
| --- | --- |
| static [Flat](../../aspose.gis/numericformat/flat)(int) | 将数字转换为不带科学计数法的定点文本。 |
| static [General](../../aspose.gis/numericformat/general)(int) | 将数字转换为更紧凑的定点或科学计数法， 取决于数字的类型以及是否为精度说明符存在。推荐使用。 |

### 评论

[`NumericFormat`](../numericformat)共有三种类型 &lt;ul&gt;&lt;li&gt;一般 - 定点或科学记数法。一些数字很重要。 &lt;/li&gt;&lt;li&gt;RoundTrip - 定点或科学记数法。最大位数是重要的。 &lt;/li&gt;&lt;li&gt;Flat - 定点表示法。一些数字很重要。 &lt;/li&gt;&lt;/ul&gt; A[`NumericFormat`](../numericformat)可以设置为IGeometry通过AsText 以便在将几何转换为其众所周知的文本 (WKT) 表示时指定数字格式。

### 也可以看看

* 命名空间 [Aspose.Gis](../../aspose.gis)
* 部件 [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->