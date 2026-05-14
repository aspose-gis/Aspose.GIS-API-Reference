---
title: "TopoJsonOptions.Transform"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية TopoJsonOptions. تحدد كائن التحويل لاستخدامه في تقليل دقة الإحداثيات وترميز الفواصل للأقواس في TopoJSON الناتج."
type: docs
weight: 60
url: /ar/net/aspose.gis.formats.topojson/topojsonoptions/transform/
---
## TopoJsonOptions.Transform property

يحدد كائن التحويل لاستخدامه في تكميم الإحداثيات وترميز الفروقات للأقواس في TopoJSON الناتج.

```csharp
public TopoJsonTransform Transform { get; set; }
```

## ملاحظات

هذا خيار كتابة - لا يؤثر على القراءة. هذا الخيار متعارض مع [`QuantizationNumber`](../quantizationnumber/) - لا يمكن أن يكون أحد هذين الخيارين غير `null`. إذا لم يكن هذا `null` - يتم تقليل دقة إحداثيات TopoJSON وتشفير الأقواس بالفرق باستخدام كائن التحويل المحدد. راجع مواصفة TopoJSON لمزيد من التفاصيل حول كائن التحويل. القيمة الافتراضية هي `null`.

### انظر أيضًا

* class [TopoJsonTransform](../../topojsontransform/)
* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


