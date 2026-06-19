---
title: "DatabaseExternalSrsSettingsBuilder.ExternalSrsFields"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "DatabaseExternalSrsSettingsBuilder 方法。指定用于读取额外请求的空间参考系统信息的特殊字段名称。"
type: docs
weight: 20
url: /zh/net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/externalsrsfields/
---
## DatabaseExternalSrsSettingsBuilder.ExternalSrsFields method

指定用于读取额外请求的空间参考系统信息的特殊字段名称。

```csharp
public DatabaseExternalSrsSettingsBuilder ExternalSrsFields(string authSridField, 
    string srTextField)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| authSridField | 字符串 | 用于读取空间参考 ID 的字段，默认值：auth_srid。 |
| srTextField | 字符串 | 用于读取以 WKT 表示的空间坐标系统的字段，默认值：srtext。 |

### 返回值

[`DatabaseExternalSrsSettingsBuilder`](../)

## 备注

如果您的字段已使用默认名称 auth_srid 和 srtext，则无需设置。

### 另见

* class [DatabaseExternalSrsSettingsBuilder](../)
* namespace [Aspose.Gis.Formats.Database](../../databaseexternalsrssettingsbuilder/)
* assembly [Aspose.GIS](../../../)


