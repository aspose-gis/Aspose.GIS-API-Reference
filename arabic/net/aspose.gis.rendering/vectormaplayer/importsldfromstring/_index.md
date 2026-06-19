---
title: "VectorMapLayer.ImportSldFromString"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorMapLayer. تستورد النمط من سلسلة Styled Layer Descriptor المحددة"
type: docs
weight: 70
url: /ar/net/aspose.gis.rendering/vectormaplayer/importsldfromstring/
---
## VectorMapLayer.ImportSldFromString method

يستورد النمط من سلسلة Styled Layer Descriptor المحددة.

```csharp
public void ImportSldFromString(string sld, SldImportOptions options = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| sld | String | Styled Layer Descriptor. |
| options | SldImportOptions | خيارات الاستيراد. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الوسيط هو `null`. |
| XmlException | حدث خطأ أثناء تحليل XML. |
| FormatException | لم يتم العثور على نمط SLD في XML. |

## ملاحظات

هذه الطريقة تستبدل قيمة خاصية [`Symbolizer`](../symbolizer/).

### انظر أيضًا

* class [SldImportOptions](../../../aspose.gis.rendering.sld/sldimportoptions/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)


