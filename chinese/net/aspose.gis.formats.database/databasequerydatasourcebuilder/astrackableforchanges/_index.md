---
title: "DatabaseQueryDataSourceBuilder.AsTrackableForChanges"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "DatabaseQueryDataSourceBuilder 方法。配置生成的图层以跟踪更改并创建数据源以同步所做的更改。"
type: docs
weight: 20
url: /zh/net/aspose.gis.formats.database/databasequerydatasourcebuilder/astrackableforchanges/
---
## DatabaseQueryDataSourceBuilder.AsTrackableForChanges method

配置生成的图层以跟踪更改，并创建数据源以同步所做的更改。

```csharp
public DatabaseEditableDataSourceBuilder AsTrackableForChanges(string tableName, 
    string identityAttribute, bool overwriteSameKey = false, string dbFunc = "ST_GeomFromWKB")
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| tableName | 字符串 | 进行更改的表的名称。 |
| identityAttribute | 字符串 | 特征的属性，将被视为唯一标识该特征。 |
| overwriteSameKey | Boolean | 如果将此标志设置为 true，则新添加的具有与图层中已存在的唯一标识符相同的要素将覆盖当前要素，并且在发现差异时数据将被读取为已更新。 |
| dbFunc | 字符串 | 将在 SQL 查询中提供的函数，用于将二进制数据转换为当前数据库的地理数据表示。 |

### 返回值

[`DatabaseEditableDataSourceBuilder`](../../../aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/)

### 另见

* class [DatabaseEditableDataSourceBuilder](../../../aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/)
* class [DatabaseQueryDataSourceBuilder](../)
* namespace [Aspose.Gis.Formats.Database](../../databasequerydatasourcebuilder/)
* assembly [Aspose.GIS](../../../)


