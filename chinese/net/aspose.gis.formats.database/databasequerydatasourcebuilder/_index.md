---
title: "类 DatabaseQueryDataSourceBuilder"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Formats.Database.DatabaseQueryDataSourceBuilder 类。提供配置对数据库查询以提取地理空间信息的能力"
type: docs
weight: 1750
url: /zh/net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---
## DatabaseQueryDataSourceBuilder class

提供配置对数据库的查询以提取地理空间信息的能力。

```csharp
public class DatabaseQueryDataSourceBuilder
```

## 方法

| 名称 | 描述 |
| --- | --- |
| [AddAttribute](../../aspose.gis.formats.database/databasequerydatasourcebuilder/addattribute/#addattribute)(string, AttributeDataType) | 配置将包含要素属性信息的字段名称。 |
| [AddAttribute](../../aspose.gis.formats.database/databasequerydatasourcebuilder/addattribute/#addattribute_1)(string, AttributeDataType, DbType) | 配置将包含要素属性信息的字段名称。 |
| [AsTrackableForChanges](../../aspose.gis.formats.database/databasequerydatasourcebuilder/astrackableforchanges/)(string, string, bool, string) | 配置生成的图层以跟踪更改，并创建数据源以同步所做的更改。 |
| [Build](../../aspose.gis.formats.database/databasequerydatasourcebuilder/build/)() | 该方法检索 [`IDatabaseDataSource`](../idatabasedatasource/) 的实现。 |
| [GeometryField](../../aspose.gis.formats.database/databasequerydatasourcebuilder/geometryfield/)(string) | 配置将从中提取几何信息的字段名称。 |
| [SridField](../../aspose.gis.formats.database/databasequerydatasourcebuilder/sridfield/)(string) | 配置将包含空间参考系统标识符 (srid) 的查询字段名称。 |
| [UseExternalSrsFromQuery](../../aspose.gis.formats.database/databasequerydatasourcebuilder/useexternalsrsfromquery/)(string) | 允许您配置数据源使用第三方空间参考系统数据，绕过 Aspose.GIS 库中预装的数据。 |

### 另见

* namespace [Aspose.Gis.Formats.Database](../../aspose.gis.formats.database/)
* assembly [Aspose.GIS](../../)


