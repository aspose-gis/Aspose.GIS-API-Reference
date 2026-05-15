---
title: "DatabaseQueryDataSourceBuilder.GeometryField"
second_title: "Aspose.GIS for .NET API 参考"
description: "DatabaseQueryDataSourceBuilder 方法。配置用于提取几何信息的字段名称"
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.database/databasequerydatasourcebuilder/geometryfield/
---
## DatabaseQueryDataSourceBuilder.GeometryField method

配置将从中提取几何信息的字段名称。

```csharp
public DatabaseQueryDataSourceBuilder GeometryField(string name)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 名称 | String | 几何字段的名称。 |

### 返回值

[`DatabaseQueryDataSourceBuilder`](../)

## 备注

当前支持的二进制格式，即在数据库端的方法有 ST_AsBinary、ST_AsWKB、ST_AsEWKB。如果使用除扩展 WKB 之外的方法（该方法已包含 srs id（srid）），则应使用包含 srid 信息的额外字段，并通过 [`SridField`](../sridfield/) 进行配置。

### 另见

* class [DatabaseQueryDataSourceBuilder](../)
* namespace [Aspose.Gis.Formats.Database](../../databasequerydatasourcebuilder/)
* assembly [Aspose.GIS](../../../)


