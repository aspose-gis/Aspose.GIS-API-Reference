---
title: "NumericFormat.General"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "NumericFormat method. 根据数字的类型以及是否存在精度说明符，将数字转换为固定点或科学计数法中更紧凑的形式。推荐使用。"
type: docs
weight: 30
url: /zh/net/aspose.gis/numericformat/general/
---
## NumericFormat.General method

根据数字类型以及是否存在精度说明符，将数字转换为定点或科学计数法中更紧凑的形式。推荐使用。

```csharp
public static NumericFormat General(int precision = 0)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 精度 | Int32 | 精度定义了结果字符串中可能出现的最大有效数字位数。如果精度为零，则使用值 \"15\"。可用的最大精度为 \"17\"。 |

### 返回值

通用格式说明符。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentOutOfRangeException | 有效数字位数小于 0 或大于 17。 |

## 备注

内部代码通过以下方式为 WKT 生成数字字符串：coordinate.ToString(\"G\", CultureInfo.InvariantCulture)。

### 另见

* class [NumericFormat](../)
* namespace [Aspose.Gis](../../numericformat/)
* assembly [Aspose.GIS](../../../)


