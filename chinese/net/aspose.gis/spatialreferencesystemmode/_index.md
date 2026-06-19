---
title: "枚举 SpatialReferenceSystemMode"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.SpatialReferenceSystemMode 枚举。指定在数据库中写入未知空间参考系统（SRS）时的模式。"
type: docs
weight: 4470
url: /zh/net/aspose.gis/spatialreferencesystemmode/
---
## SpatialReferenceSystemMode enumeration

指定在数据库中写入空间参考系统 (SRS) 的模式，如果它是未知的 SRS。

```csharp
public enum SpatialReferenceSystemMode
```

### 值

| 名称 | 值 | 描述 |
| --- | --- | --- |
| ThrowException | `0` | 如果数据库的 SRS 未知，则抛出异常。 |
| WriteInSystemTable | `1` | 如果数据库的 SRS 未知，则在系统表中写入 SRS 信息。 |
| SetupToZero | `2` | 如果数据库的 SRS 未知，则将几何体的 SRID 设置为 “zero”。 |

### 另见

* namespace [Aspose.Gis](../../aspose.gis/)
* assembly [Aspose.GIS](../../)


