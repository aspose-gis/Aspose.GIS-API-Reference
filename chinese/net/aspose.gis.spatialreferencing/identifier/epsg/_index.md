---
title: "Identifier.Epsg"
second_title: "Aspose.GIS for .NET API 参考"
description: "Identifier 方法。创建一个新的 Identifier，表示代码为 epsgCode 的 EPSG 标识符"
type: docs
weight: 20
url: /zh/net/aspose.gis.spatialreferencing/identifier/epsg/
---
## Identifier.Epsg method

创建一个新的 Identifier，表示代码为 *epsgCode* 的 EPSG 标识符。

```csharp
public static Identifier Epsg(int epsgCode)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| epsgCode | Int32 | Epsg 代码。 |

### 返回值

使用 [`AuthorityName`](../authorityname/) 为 "EPSG" 且 [`AuthorityUniqueIdentifier`](../authorityuniqueidentifier/)*epsgCode* 的新标识符。如果 *epsgCode* 小于 0，则返回 `null`;

### 另见

* class [Identifier](../)
* namespace [Aspose.Gis.SpatialReferencing](../../identifier/)
* assembly [Aspose.GIS](../../../)


