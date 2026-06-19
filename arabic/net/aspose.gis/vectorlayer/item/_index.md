---
title: "VectorLayer.Item"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية VectorLayer. تحصل على الـ Feature في الفهرس المحدد"
type: docs
weight: 70
url: /ar/net/aspose.gis/vectorlayer/item/
---
## VectorLayer indexer

يحصل على [`Feature`](../../feature/) في الفهرس المحدد.

```csharp
public virtual Feature this[int index] { get; }
```

| معامل | الوصف |
| --- | --- |
| فهرس | فهرس الـ feature. |

### Property Value

الـ [`Feature`](../../feature/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يتم إلقاؤه إذا تم فتح الطبقة للكتابة فقط. |
| ArgumentOutOfRangeException | الفهرس خارج النطاق. |
| [GisException](../../gisexception/) | خطأ في قراءة الميزة من الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


