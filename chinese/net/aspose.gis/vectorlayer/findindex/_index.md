---
title: "VectorLayer.FindIndex"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "VectorLayer 方法。根据条件搜索 Feature 索引"
type: docs
weight: 140
url: /zh/net/aspose.gis/vectorlayer/findindex/
---
## VectorLayer.FindIndex method

根据条件搜索 [`Feature`](../../feature/) 索引。

```csharp
public virtual int FindIndex(Func<Feature, bool> match)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| match | Func`2 | 搜索谓词。 |

### 返回值

如果找到，则返回符合 *match* 定义的条件的第一个 [`Feature`](../../feature/) 出现的零基索引；否则返回 -1。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 如果谓词为 null。 |

### 另见

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


