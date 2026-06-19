---
title: "VectorMapLayer.ImportSld"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة VectorMapLayer. تستورد النمط من ملف Styled Layer Descriptor الموجود في المسار المحدد"
type: docs
weight: 60
url: /ar/net/aspose.gis.rendering/vectormaplayer/importsld/
---
## ImportSld(string, SldImportOptions) {#importsld_1}

يستورد النمط من ملف Styled Layer Descriptor الموجود في المسار المحدد.

```csharp
public void ImportSld(string path, SldImportOptions options = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى ملف Styled Layer Descriptor. |
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

---

## ImportSld(AbstractPath, SldImportOptions) {#importsld}

يستورد النمط من ملف Styled Layer Descriptor الموجود في المسار المحدد.

```csharp
public void ImportSld(AbstractPath path, SldImportOptions options = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى ملف Styled Layer Descriptor. |
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

* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [SldImportOptions](../../../aspose.gis.rendering.sld/sldimportoptions/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)


