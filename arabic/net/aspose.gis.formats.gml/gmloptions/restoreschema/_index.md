---
title: "GmlOptions.RestoreSchema"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية GmlOptions. تحدد ما إذا كان يُسمح لـ Aspose.GIS بتحليل السمات في ملف Gml الذي يفتقد مخطط XML أو لا يمكن تحميله. إذا تم تعيينها إلى true، لا يتطلب قارئ Aspose.GIS وجود مخطط XML. القيمة الافتراضية هي false"
type: docs
weight: 40
url: /ar/net/aspose.gis.formats.gml/gmloptions/restoreschema/
---
## GmlOptions.RestoreSchema property

يحدد ما إذا كان يُسمح لـ Aspose.GIS بتحليل السمات في ملف Gml لا يحتوي على مخطط XML أو لا يمكن تحميله. إذا تم تعيينه إلى `true`، فإن قارئ Aspose.GIS لا يتطلب وجود مخطط XML. القيمة الافتراضية هي `false`.

```csharp
public bool RestoreSchema { get; set; }
```

## ملاحظات

يحاول السائق (Driver) تحليل فئات المميزات وخصائصها المرتبطة تلقائيًا عن طريق فحص الملف والبحث عن الكائنات “المعروفة” لتحديد التنظيم. على الرغم من أن هذا النهج عرضة للأخطاء، إلا أنه يمتاز بقدرته على العمل مع ملفات GML حتى إذا فقد المخطط XML المرتبط أو لا يمكن تحميله من الإنترنت.

### انظر أيضًا

* class [GmlOptions](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmloptions/)
* assembly [Aspose.GIS](../../../)


