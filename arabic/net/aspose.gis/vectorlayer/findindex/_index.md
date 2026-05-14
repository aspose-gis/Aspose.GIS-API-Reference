---
title: "VectorLayer.FindIndex"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorLayer. البحث عن فهرس Feature وفقًا للشرط"
type: docs
weight: 140
url: /ar/net/aspose.gis/vectorlayer/findindex/
---
## VectorLayer.FindIndex method

البحث عن فهرس [`Feature`](../../feature/) وفقًا للشرط.

```csharp
public virtual int FindIndex(Func<Feature, bool> match)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| match | Func`2 | دالة شرط للبحث. |

### قيمة الإرجاع

الفهرس الصفري للظهور الأول لـ [`Feature`](../../feature/) الذي يطابق الشروط المحددة بواسطة *match*، إذا وجد؛ وإلا -1.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | إذا كانت دالة الشرط فارغة. |

### انظر أيضًا

* class [Feature](../../feature/)
* class [VectorLayer](../)
* namespace [Aspose.Gis](../../vectorlayer/)
* assembly [Aspose.GIS](../../../)


