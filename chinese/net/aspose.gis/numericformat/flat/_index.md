---
title: "NumericFormat.Flat"
second_title: "Aspose.GIS for .NET API 参考"
description: "NumericFormat 方法。将数字转换为固定点文本，不使用科学计数法。"
type: docs
weight: 20
url: /zh/net/aspose.gis/numericformat/flat/
---
## NumericFormat.Flat method

将数字转换为不使用科学计数法的定点文本。

```csharp
public static NumericFormat Flat(int significantDigits)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| significantDigits | Int32 | 有效数字位数。可用的最大精度为 "308"。 |

### 返回值

四舍五入精度说明符。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 有效数字位数小于 0 或大于 308。 |

## 备注

内部代码通过以下方式为 WKT 生成数字字符串：coordinate.ToString("0.##..", CultureInfo.InvariantCulture) 决策。

### 另见

* class [NumericFormat](../)
* namespace [Aspose.Gis](../../numericformat/)
* assembly [Aspose.GIS](../../../)


