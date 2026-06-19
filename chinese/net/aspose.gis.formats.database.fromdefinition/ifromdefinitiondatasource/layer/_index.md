---
title: "IFromDefinitionDataSource.Layer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IFromDefinitionDataSource 属性。返回实现 IQueryable 的对象，允许对数据库进行 LINQ 查询的属性"
type: docs
weight: 10
url: /zh/net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/layer/
---
## IFromDefinitionDataSource.Layer property

返回实现 IQueryable 的对象的属性，允许对数据库进行 LINQ 查询。

```csharp
public IQueryable<Feature> Layer { get; }
```

### 返回值

IQueryable

## 备注

此外，查询可以通过同步方式使用 ToArray() 或 ToList() 以标准方式执行，或使用异步方式提取整个层的 [`ToVectorLayerAsync`](../../queryablelayerextension/tovectorlayerasync/)。

### 另见

* class [Feature](../../../aspose.gis/feature/)
* interface [IFromDefinitionDataSource](../)
* namespace [Aspose.Gis.Formats.Database.FromDefinition](../../ifromdefinitiondatasource/)
* assembly [Aspose.GIS](../../../)


