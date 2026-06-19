---
title: "IDatabaseEditableDataSource.SubmitChangesAsync"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "IDatabaseEditableDataSource 方法。允许您将累计的更改保存到数据库"
type: docs
weight: 10
url: /zh/net/aspose.gis.formats.database.dataediting/idatabaseeditabledatasource/submitchangesasync/
---
## IDatabaseEditableDataSource.SubmitChangesAsync method

允许您将累计的更改保存到数据库。

```csharp
public Task SubmitChangesAsync(VectorLayer layer, DbConnection connection, 
    DbTransaction transaction)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 图层 | VectorLayer | 具有跟踪更改能力的图层。 |
| 连接 | DbConnection | 到数据库的打开连接。 |
| 事务 | DbTransaction | Transaction |

### 返回值

Task

### 异常

| 异常 | 条件 |
| --- | --- |
| InvalidOperationException |  |

## 备注

如果图层不具备跟踪更改的能力，将抛出 InvalidOperationException 异常。如果连接未打开，也会抛出 InvalidOperationException 异常。

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* interface [IDatabaseEditableDataSource](../)
* namespace [Aspose.Gis.Formats.Database.DataEditing](../../idatabaseeditabledatasource/)
* assembly [Aspose.GIS](../../../)


