---
title: "IRasterValues.Item"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IRasterValues 属性。获取波段值为双精度类型"
type: docs
weight: 10
url: /zh/net/aspose.gis.raster/irastervalues/item/
---
## IRasterValues indexer

获取波段值，类型为 `double`。

```csharp
public double this[int bandIndex] { get; }
```

| 参数 | 描述 |
| --- | --- |
| bandIndex | 波段的索引。编号从 0 开始。 |

### 返回值

转换后的值。

## 备注

如果波段类型为 RawBits，建议使用[`AsRawBits`](../asrawbits/) 方法以避免异常。

### 另见

* interface [IRasterValues](../)
* namespace [Aspose.Gis.Raster](../../irastervalues/)
* assembly [Aspose.GIS](../../../)


