---
title: "DatabaseQueryDataSourceBuilder.UseExternalSrsFromQuery"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة DatabaseQueryDataSourceBuilder. تسمح لك بتكوين مصدر البيانات لاستخدام بيانات نظام إحداثيات مكاني من طرف ثالث متجاوزةً البيانات المثبتة مسبقًا في مكتبة Aspose.GIS"
type: docs
weight: 60
url: /ar/net/aspose.gis.formats.database/databasequerydatasourcebuilder/useexternalsrsfromquery/
---
## DatabaseQueryDataSourceBuilder.UseExternalSrsFromQuery method

يسمح لك بتكوين مصدر البيانات لاستخدام بيانات نظام الإسناد المكاني من طرف ثالث، متجاوزًا البيانات المثبتة مسبقًا في مكتبة Aspose.GIS.

```csharp
public DatabaseExternalSrsSettingsBuilder UseExternalSrsFromQuery(string srsQuery)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| srsQuery | String | استعلام لاسترجاع معلومات حول أنظمة الإحداثيات المكانية الإضافية المستخدمة في الاستعلام الرئيسي لاسترجاع المميزات. |

### قيمة الإرجاع

[`DatabaseExternalSrsSettingsBuilder`](../../databaseexternalsrssettingsbuilder/)

## ملاحظات

من المهم معرفة أنه في حالة عدم وجود نظام إحداثيات مكاني في القائمة المستخرجة مسبقًا من قاعدة البيانات ولكن تم استخدامه في الاستعلام الرئيسي، ستُحاول المكتبة استخدام نظام إحداثيات مدمج. مثال الاستعلام: SELECT auth_srid, srtext FROM spatial_ref_sys WHERE srid = 4284

### انظر أيضًا

* class [DatabaseExternalSrsSettingsBuilder](../../databaseexternalsrssettingsbuilder/)
* class [DatabaseQueryDataSourceBuilder](../)
* namespace [Aspose.Gis.Formats.Database](../../databasequerydatasourcebuilder/)
* assembly [Aspose.GIS](../../../)


