---
title: "NumericFormat.RoundTrip"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "NumericFormat property. 转换并尝试确保被转换为字符串的数值能够解析回相同的数值"
type: docs
weight: 10
url: /zh/net/aspose.gis/numericformat/roundtrip/
---
## NumericFormat.RoundTrip property

转换并尝试确保被转换为字符串的数值能够解析回相同的数值。

```csharp
public static NumericFormat RoundTrip { get; }
```

## 备注

内部代码通过以下方式为 WKT 生成数字字符串：coordinate.ToString(\"R\", CultureInfo.InvariantCulture) 决策。

### 另见

* class [NumericFormat](../)
* namespace [Aspose.Gis](../../numericformat/)
* assembly [Aspose.GIS](../../../)


