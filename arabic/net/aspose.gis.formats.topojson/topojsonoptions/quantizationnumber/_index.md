---
title: "TopoJsonOptions.QuantizationNumber"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية TopoJsonOptions. تحدد رقم التكميم لاستخدامه في تقليل دقة الإحداثيات وترميز الفواصل (deltaencode) للأقواس في TopoJSON الناتج"
type: docs
weight: 50
url: /ar/net/aspose.gis.formats.topojson/topojsonoptions/quantizationnumber/
---
## TopoJsonOptions.QuantizationNumber property

يحدد رقم التكميم لاستخدامه في تكميم الإحداثيات وترميز الفواصل للأقواس في ملف TopoJSON الناتج.

```csharp
public int? QuantizationNumber { get; set; }
```

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentOutOfRangeException | المعامل أقل من اثنين. |

## ملاحظات

هذا خيار كتابة - لا يؤثر على القراءة. هذا الخيار متعارض مع [`Transform`](../transform/) - لا يمكن أن يكون أحد هذين الخيارين غير `null`. إذا لم يكن هذا `null` - يتم تقليل دقة إحداثيات TopoJSON وتشفير الأقواس (delta-encoded) باستخدام رقم التكميم المحدد. يحدد رقم التكميم الحد الأقصى لعدد القيم القابلة للتعبير عنها لكل بُعد في الإحداثيات المكمَّمة الناتجة؛ عادةً ما يُختار أس القوة من عشرة. القيمة الافتراضية هي `null`.

### انظر أيضًا

* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


