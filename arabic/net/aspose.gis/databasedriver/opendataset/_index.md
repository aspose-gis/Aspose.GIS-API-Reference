---
title: "DatabaseDriver.OpenDataset"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة DatabaseDriver. تفتح مجموعة البيانات"
type: docs
weight: 10
url: /ar/net/aspose.gis/databasedriver/opendataset/
---
## DatabaseDriver.OpenDataset method

يفتح مجموعة البيانات.

```csharp
public abstract Dataset OpenDataset(IDbConnection connection)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاتصال | IDbConnection | تم فتح الاتصال بقاعدة البيانات. |

### قيمة الإرجاع

كائن من [`Dataset`](../../dataset/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الاتصال هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [Dataset](../../dataset/)
* class [DatabaseDriver](../)
* namespace [Aspose.Gis](../../databasedriver/)
* assembly [Aspose.GIS](../../../)


