---
title: "IGeometry.AsImage"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة IGeometry. صدّر هذه الهندسة إلى تمثيل صورة"
type: docs
weight: 110
url: /ar/net/aspose.gis.geometries/igeometry/asimage/
---
## AsImage(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_1}

يصدّر هذه الـ geometry إلى تمثيل صورة.

```csharp
public void AsImage(AbstractPath outputPath, Measurement width, Measurement height, 
    Renderer renderer, VectorSymbolizer symbolizer = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| outputPath | AbstractPath | المسار إلى صورة الإخراج. |
| العرض | القياس | عرض الخريطة. |
| الارتفاع | القياس | ارتفاع الخريطة. |
| renderer | Renderer | Renderer للاستخدام. |
| symbolizer | VectorSymbolizer | symbolizer للاستخدام في العرض. إذا كان `null`، يُستخدم symbolizer الافتراضي. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [GisException](../../../aspose.gis/gisexception/) | خطأ أثناء معالجة أو قراءة بيانات نظام المعلومات الجغرافية (GIS). |
| ArgumentException | وحدة العرض أو الارتفاع هي !:SpatialReferencing.Unit.MapUnits. |
| ArgumentOutOfRangeException | العرض أو الارتفاع سالب أو صفر. |

### انظر أيضًا

* class [AbstractPath](../../../aspose.gis/abstractpath/)
* struct [Measurement](../../../aspose.gis.rendering/measurement/)
* class [Renderer](../../../aspose.gis.rendering/renderer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## AsImage(string, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_2}

يصدّر هذه الـ geometry إلى تمثيل صورة.

```csharp
public void AsImage(string outputPath, Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| outputPath | String | المسار إلى صورة الإخراج. |
| العرض | القياس | عرض الخريطة. |
| الارتفاع | القياس | ارتفاع الخريطة. |
| renderer | Renderer | Renderer للاستخدام. |
| symbolizer | VectorSymbolizer | symbolizer للاستخدام في العرض. إذا كان `null`، يُستخدم symbolizer الافتراضي. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [GisException](../../../aspose.gis/gisexception/) | خطأ أثناء معالجة أو قراءة بيانات نظام المعلومات الجغرافية (GIS). |
| ArgumentException | وحدة العرض أو الارتفاع هي !:SpatialReferencing.Unit.MapUnits. |
| ArgumentOutOfRangeException | العرض أو الارتفاع سالب أو صفر. |

### انظر أيضًا

* struct [Measurement](../../../aspose.gis.rendering/measurement/)
* class [Renderer](../../../aspose.gis.rendering/renderer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)

---

## AsImage(Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage}

يصدّر هذه الـ geometry إلى تمثيل صورة.

```csharp
public Stream AsImage(Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | القياس | عرض الخريطة. |
| الارتفاع | القياس | ارتفاع الخريطة. |
| renderer | Renderer | Renderer للاستخدام. |
| symbolizer | VectorSymbolizer | symbolizer للاستخدام في العرض. إذا كان `null`، يُستخدم symbolizer الافتراضي. |

### قيمة الإرجاع

الصورة كتيار

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [GisException](../../../aspose.gis/gisexception/) | خطأ أثناء معالجة أو قراءة بيانات نظام المعلومات الجغرافية (GIS). |
| ArgumentException | وحدة العرض أو الارتفاع هي !:SpatialReferencing.Unit.MapUnits. |
| ArgumentOutOfRangeException | العرض أو الارتفاع سالب أو صفر. |

### انظر أيضًا

* struct [Measurement](../../../aspose.gis.rendering/measurement/)
* class [Renderer](../../../aspose.gis.rendering/renderer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* interface [IGeometry](../)
* namespace [Aspose.Gis.Geometries](../../igeometry/)
* assembly [Aspose.GIS](../../../)


