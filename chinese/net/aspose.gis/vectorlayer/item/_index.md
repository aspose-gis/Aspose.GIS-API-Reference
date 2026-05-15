---
title: "VectorLayer.Item"
second_title: "Aspose.GIS for .NET API 参考"
description: "VectorLayer 属性。获取指定索引处的 Feature。"
type: docs
weight: 70
url: /zh/net/aspose.gis/vectorlayer/item/
---
## VectorLayer indexer

获取指定索引处的 [`Feature`](../../feature/)。

```csharp
public virtual Feature this[int index] { get; }
```

| 参数 | 描述 |
| --- | --- |
| 索引 | 特征的索引。 |

### Property Value

该 [`Feature`](../../feature/)。

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 如果图层以只写方式打开，则会抛出此异常。 |
| ArgumentOutOfRangeException | 索引超出范围。 |
| [GisException](../../gisexception/) | 读取文件中的要素时出错。 |
| IOException | 发生 I/O 错误。 |

### 另见

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


