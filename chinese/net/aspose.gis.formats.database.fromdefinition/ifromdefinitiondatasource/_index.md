---
title: "接口 IFromDefinitionDataSource"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Formats.Database.FromDefinition.IFromDefinitionDataSource 接口。提供通过 LINQ 从数据库读取地理空间数据并更新它们的能力"
type: docs
weight: 1770
url: /zh/net/aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/
---
## IFromDefinitionDataSource interface

提供通过 LINQ 从数据库读取地理空间数据并更新它们的能力。

```csharp
public interface IFromDefinitionDataSource
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Layer](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/layer/) { get; } | 返回实现 IQueryable 的对象的属性，允许对数据库进行 LINQ 查询。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [GetEmptyLayer](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/getemptylayer/)() | 允许创建空图层。当仅向数据库添加新记录时，这可能很有用。但随后该图层可用于编辑新添加的记录。 |
| [SubmitChangesAsync](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/submitchangesasync/)() | 允许保存最后提取的图层中累计的更改。 |
| [UseConnection](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/useconnection/)(DbConnection) | 强制性配置，当前连接。 |
| [UseTransaction](../../aspose.gis.formats.database.fromdefinition/ifromdefinitiondatasource/usetransaction/)(DbTransaction) | 这不是必需的设置，以防需要在事务中执行一系列操作。 |

### 另见

* namespace [Aspose.Gis.Formats.Database.FromDefinition](../../aspose.gis.formats.database.fromdefinition/)
* assembly [Aspose.GIS](../../)


