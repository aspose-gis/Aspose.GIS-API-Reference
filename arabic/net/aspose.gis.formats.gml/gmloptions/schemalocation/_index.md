---
title: "GmlOptions.SchemaLocation"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "خاصية GmlOptions. قائمة مفصولة بمسافات من أزواج URI. الـ URI الأول في كل زوج هو URI للمساحة الاسمية والـ URI الثاني هو مسار إلى مخطط XML للمساحة الاسمية. إذا تم تعيينه إلى null سيحاول GmlDriver قراءة schemaLocation من العنصر الجذر للمستند. القيمة الافتراضية هي null"
type: docs
weight: 50
url: /ar/net/aspose.gis.formats.gml/gmloptions/schemalocation/
---
## GmlOptions.SchemaLocation property

قائمة مفصولة بمسافات من أزواج URI. الـ URI الأول في كل زوج هو URI للمساحة الاسمية، والـ URI الثاني هو مسار إلى مخطط XML للمساحة الاسمية. إذا تم تعيينه إلى `null`، فإن [`GmlDriver`](../../gmldriver/) سيحاول قراءة schemaLocation من العنصر الجذر للمستند. القيمة الافتراضية هي `null`.

```csharp
public string SchemaLocation { get; set; }
```

## ملاحظات

Aspose.GIS يستخدم مخطط XML لملف GML لإنشاء [`FeatureAttributeCollection`](../../../aspose.gis/featureattributecollection/). بشكل افتراضي، يتم استخراج موقع المخطط من سمة schemaLocation. إذا لم توجد هذه السمة أو أشارت إلى موقع غير صالح، سيفشل Aspose.GIS في قراءة ملف GML. في هذه الحالة - اضبط هذا الخيار، حتى يتمكن Aspose.GIS من تحميل المخطط.

## أمثلة

"http://site.com/namespace http://site.com/schema.xsd"

### انظر أيضًا

* class [GmlOptions](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmloptions/)
* assembly [Aspose.GIS](../../../)


