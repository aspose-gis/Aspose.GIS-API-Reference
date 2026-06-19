---
title: "DatabaseQueryDataSourceBuilder.UseExternalSrsFromQuery"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "DatabaseQueryDataSourceBuilder 方法。允许您配置数据源以使用第三方空间参考系数据，绕过 Aspose.GIS 库中预装的数据。"
type: docs
weight: 60
url: /zh/net/aspose.gis.formats.database/databasequerydatasourcebuilder/useexternalsrsfromquery/
---
## DatabaseQueryDataSourceBuilder.UseExternalSrsFromQuery method

允许您配置数据源使用第三方空间参考系统数据，绕过 Aspose.GIS 库中预装的数据。

```csharp
public DatabaseExternalSrsSettingsBuilder UseExternalSrsFromQuery(string srsQuery)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| srsQuery | 字符串 | 用于检索主查询中用于获取要素的附加空间坐标系信息的查询。 |

### 返回值

[`DatabaseExternalSrsSettingsBuilder`](../../databaseexternalsrssettingsbuilder/)

## 备注

需要注意的是，如果在预先从数据库提取的空间参考系列表中缺少主查询中使用的空间参考系，库将尝试使用内置的 srs。查询示例：SELECT auth_srid, srtext FROM spatial_ref_sys WHERE srid = 4284

### 另见

* class [DatabaseExternalSrsSettingsBuilder](../../databaseexternalsrssettingsbuilder/)
* class [DatabaseQueryDataSourceBuilder](../)
* namespace [Aspose.Gis.Formats.Database](../../databasequerydatasourcebuilder/)
* assembly [Aspose.GIS](../../../)


