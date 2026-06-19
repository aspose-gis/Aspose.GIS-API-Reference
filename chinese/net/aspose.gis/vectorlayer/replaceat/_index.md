---
title: "VectorLayer.ReplaceAt"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "VectorLayer 方法。替换指定索引处的 Feature"
type: docs
weight: 190
url: /zh/net/aspose.gis/vectorlayer/replaceat/
---
## VectorLayer.ReplaceAt method

替换指定索引处的 [`Feature`](../../feature/)。

```csharp
public virtual void ReplaceAt(int index, Feature feature)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 索引 | Int32 | 要素的索引。 |
| 要素 | Feature | 要设置的特征。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException | 当图层不可编辑时抛出。 |
| ArgumentOutOfRangeException | 索引超出范围。 |
| IOException | 发生了 I/O 错误。 |

### 另见

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


