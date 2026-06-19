---
title: "接口 IDatabaseEditableDataSource"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Formats.Database.DataEditing.IDatabaseEditableDataSource 接口。实现此接口的对象能够接受具有跟踪更改能力的图层并将其保存到数据库"
type: docs
weight: 1720
url: /zh/net/aspose.gis.formats.database.dataediting/idatabaseeditabledatasource/
---
## IDatabaseEditableDataSource interface

实现此接口的对象具有接受图层、跟踪更改并将其保存到数据库的能力。

```csharp
public interface IDatabaseEditableDataSource : IDatabaseDataSource
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [SubmitChangesAsync](../../aspose.gis.formats.database.dataediting/idatabaseeditabledatasource/submitchangesasync/)(VectorLayer, DbConnection, DbTransaction) | 允许您将累计的更改保存到数据库。 |

## 备注

要获取可跟踪的图层，需要在配置数据源时调用 [`AsTrackableForChanges`](../../aspose.gis.formats.database/databasequerydatasourcebuilder/astrackableforchanges/)，然后通过 [`ReadAsync`](../../aspose.gis.formats.database/idatabasedatasource/readasync/) 检索该图层。

### 另见

* interface [IDatabaseDataSource](../../aspose.gis.formats.database/idatabasedatasource/)
* namespace [Aspose.Gis.Formats.Database.DataEditing](../../aspose.gis.formats.database.dataediting/)
* assembly [Aspose.GIS](../../)


