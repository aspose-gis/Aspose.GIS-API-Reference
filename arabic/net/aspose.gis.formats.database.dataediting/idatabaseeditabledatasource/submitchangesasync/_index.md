---
title: "IDatabaseEditableDataSource.SubmitChangesAsync"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IDatabaseEditableDataSource. يسمح لك بحفظ التغييرات المتراكمة في قاعدة البيانات"
type: docs
weight: 10
url: /ar/net/aspose.gis.formats.database.dataediting/idatabaseeditabledatasource/submitchangesasync/
---
## IDatabaseEditableDataSource.SubmitChangesAsync method

يسمح لك بحفظ التغييرات المتراكمة في قاعدة البيانات.

```csharp
public Task SubmitChangesAsync(VectorLayer layer, DbConnection connection, 
    DbTransaction transaction)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الطبقة | VectorLayer | طبقة مع القدرة على تتبع التغييرات. |
| الاتصال | DbConnection | اتصال مفتوح بقاعدة البيانات. |
| المعاملة | DbTransaction | المعاملة |

### قيمة الإرجاع

مهمة

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException |  |

## ملاحظات

في حال عدم امتلاك الطبقة للقدرة على تتبع التغييرات، سيتم إلقاء استثناء InvalidOperationException. إذا لم يكن الاتصال مفتوحًا، سيتم إلقاء استثناء InvalidOperationException.

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* interface [IDatabaseEditableDataSource](../)
* namespace [Aspose.Gis.Formats.Database.DataEditing](../../idatabaseeditabledatasource/)
* assembly [Aspose.GIS](../../../)


