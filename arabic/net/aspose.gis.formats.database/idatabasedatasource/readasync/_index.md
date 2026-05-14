---
title: "IDatabaseDataSource.ReadAsync"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "IDatabaseDataSource طريقة. طريقة لقراءة البيانات الجغرافية المكانية"
type: docs
weight: 10
url: /ar/net/aspose.gis.formats.database/idatabasedatasource/readasync/
---
## ReadAsync(DbConnection, IDictionary&lt;string, object&gt;) {#readasync}

طريقة لقراءة البيانات الجغرافية المكانية.

```csharp
public Task<VectorLayer> ReadAsync(DbConnection connection, 
    IDictionary<string, object> sqlParametrs = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاتصال | DbConnection | كائن الاتصال. |
| sqlParametrs | IDictionary`2 | مجموعة من معلمات SQL |

### قيمة الإرجاع

يعيد نسخة واحدة من InMemoryLayer ملفوفة في ReadVectorWrapper لإجراء تحويلات هندسية إضافية عند الطلب.

## ملاحظات

يجب تكوين الاتصال وأن يكون في حالة مفتوحة.

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* interface [IDatabaseDataSource](../)
* namespace [Aspose.Gis.Formats.Database](../../idatabasedatasource/)
* assembly [Aspose.GIS](../../../)

---

## ReadAsync(DbConnection, DbTransaction, IDictionary&lt;string, object&gt;) {#readasync_1}

طريقة لقراءة البيانات الجغرافية المكانية داخل معاملة..

```csharp
public Task<VectorLayer> ReadAsync(DbConnection connection, DbTransaction transaction, 
    IDictionary<string, object> sqlParametrs = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاتصال | DbConnection | كائن الاتصال. |
| المعاملة | DbTransaction | المعاملة الحالية. |
| sqlParametrs | IDictionary`2 | مجموعة من معلمات SQL |

### قيمة الإرجاع

يعيد نسخة واحدة من InMemoryLayer ملفوفة في ReadVectorWrapper لإجراء تحويلات هندسية إضافية عند الطلب.

## ملاحظات

يجب تكوين الاتصال وأن يكون في حالة مفتوحة.

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* interface [IDatabaseDataSource](../)
* namespace [Aspose.Gis.Formats.Database](../../idatabasedatasource/)
* assembly [Aspose.GIS](../../../)


