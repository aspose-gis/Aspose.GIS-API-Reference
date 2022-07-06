---
title: Epsg
second_title: Aspose.GIS for .NET API 参考
description: 使用代码epsgCode创建表示 EPSG 标识符的新标识符
type: docs
weight: 20
url: /zh/net/aspose.gis.spatialreferencing/identifier/epsg/
---
## Identifier.Epsg method

使用代码*epsgCode*创建表示 EPSG 标识符的新标识符。

```csharp
public static Identifier Epsg(int epsgCode)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| epsgCode | Int32 | Epsg 代码。 |

### 返回值

带有[`AuthorityName`](../authorityname)"EPSG" 的新标识符和[`AuthorityUniqueIdentifier`](../authorityuniqueidentifier)*epsgCode*。 如果*epsgCode*小于 0 - 返回`null`；

### 也可以看看

* class [Identifier](../../identifier)
* 命名空间 [Aspose.Gis.SpatialReferencing](../../identifier)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->