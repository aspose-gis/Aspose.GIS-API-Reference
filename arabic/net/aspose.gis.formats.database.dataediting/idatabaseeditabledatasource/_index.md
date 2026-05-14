---
title: "الواجهة IDatabaseEditableDataSource"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "واجهة Aspose.Gis.Formats.Database.DataEditing.IDatabaseEditableDataSource. الكائن الذي ينفذ هذه الواجهة لديه القدرة على قبول طبقة مع القدرة على تتبع التغييرات وحفظها في قاعدة البيانات"
type: docs
weight: 1720
url: /ar/net/aspose.gis.formats.database.dataediting/idatabaseeditabledatasource/
---
## IDatabaseEditableDataSource interface

الكائن الذي يطبق هذه الواجهة يمتلك القدرة على قبول طبقة مع القدرة على تتبع التغييرات وحفظها في قاعدة البيانات.

```csharp
public interface IDatabaseEditableDataSource : IDatabaseDataSource
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [SubmitChangesAsync](../../aspose.gis.formats.database.dataediting/idatabaseeditabledatasource/submitchangesasync/)(VectorLayer, DbConnection, DbTransaction) | يسمح لك بحفظ التغييرات المتراكمة في قاعدة البيانات. |

## ملاحظات

للحصول على طبقة قابلة للتتبع، يلزم استدعاء [`AsTrackableForChanges`](../../aspose.gis.formats.database/databasequerydatasourcebuilder/astrackableforchanges/) عند تكوين مصدر البيانات ثم استرجاع الطبقة عبر [`ReadAsync`](../../aspose.gis.formats.database/idatabasedatasource/readasync/).

### انظر أيضًا

* interface [IDatabaseDataSource](../../aspose.gis.formats.database/idatabasedatasource/)
* namespace [Aspose.Gis.Formats.Database.DataEditing](../../aspose.gis.formats.database.dataediting/)
* assembly [Aspose.GIS](../../)


