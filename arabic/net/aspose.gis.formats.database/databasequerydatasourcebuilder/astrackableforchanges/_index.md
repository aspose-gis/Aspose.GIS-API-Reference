---
title: "DatabaseQueryDataSourceBuilder.AsTrackableForChanges"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة DatabaseQueryDataSourceBuilder. ضبط الطبقة الناتجة لتتبع التغييرات وإنشاء مصدر بيانات لمزامنة التغييرات التي تم إجراؤها."
type: docs
weight: 20
url: /ar/net/aspose.gis.formats.database/databasequerydatasourcebuilder/astrackableforchanges/
---
## DatabaseQueryDataSourceBuilder.AsTrackableForChanges method

قم بتكوين الطبقة الناتجة لتتبع التغييرات وإنشاء مصدر بيانات لمزامنة التغييرات التي تم إجراؤها.

```csharp
public DatabaseEditableDataSourceBuilder AsTrackableForChanges(string tableName, 
    string identityAttribute, bool overwriteSameKey = false, string dbFunc = "ST_GeomFromWKB")
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| tableName | String | اسم الجدول الذي ستُجرى فيه التغييرات. |
| identityAttribute | String | خاصية للميزة ستُعامل كمعرف فريد للميزة. |
| overwriteSameKey | Boolean | إذا تم تعيين هذه العلامة إلى true، فإن الميزات المضافة حديثًا التي تحمل معرفًا فريدًا موجودًا بالفعل في الطبقة سيتم استبدال الحالية به، وسيتم قراءة البيانات كأنها محدثة إذا وُجدت اختلافات. |
| dbFunc | String | الدالة التي سيتم توفيرها في استعلام SQL لتحويل البيانات الثنائية إلى تمثيل بيانات جغرافية لقاعدة البيانات الحالية. |

### قيمة الإرجاع

[`DatabaseEditableDataSourceBuilder`](../../../aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/)

### انظر أيضًا

* class [DatabaseEditableDataSourceBuilder](../../../aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/)
* class [DatabaseQueryDataSourceBuilder](../)
* namespace [Aspose.Gis.Formats.Database](../../databasequerydatasourcebuilder/)
* assembly [Aspose.GIS](../../../)


