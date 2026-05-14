---
title: "VectorLayer.Item"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية VectorLayer. تحصل على Feature في الفهرس المحدد"
type: docs
weight: 70
url: /ar/net/aspose.gis/vectorlayer/item/
---
## VectorLayer indexer

تحصل على [`Feature`](../../feature/) في الفهرس المحدد.

```csharp
public virtual Feature this[int index] { get; }
```

| معامل | الوصف |
| --- | --- |
| الفهرس | فهرس الـ feature. |

### Property Value

الـ [`Feature`](../../feature/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException | يتم رميه إذا تم فتح الطبقة للكتابة فقط. |
| ArgumentOutOfRangeException | الفهرس خارج النطاق. |
| [GisException](../../gisexception/) | خطأ في قراءة العنصر من الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


