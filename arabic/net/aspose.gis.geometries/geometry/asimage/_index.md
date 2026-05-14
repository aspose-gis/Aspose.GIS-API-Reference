---
title: "Geometry.AsImage"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Geometry. تصدير هذه الهندسة إلى تمثيل صورة"
type: docs
weight: 120
url: /ar/net/aspose.gis.geometries/geometry/asimage/
---
## AsImage(AbstractPath, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_1}

يصدّر هذه الهندسة إلى تمثيل صورة.

```csharp
public void AsImage(AbstractPath outputPath, Measurement width, Measurement height, 
    Renderer renderer, VectorSymbolizer symbolizer = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| outputPath | AbstractPath | المسار إلى صورة الإخراج. |
| العرض | القياس | عرض الخريطة. |
| الارتفاع | القياس | ارتفاع الخريطة. |
| renderer | Renderer | المُعالج المستخدم. |
| symbolizer | VectorSymbolizer | رمز لتحديد الشكل يُستخدم في التصيير. إذا كان `null`، يُستخدم رمز التحديد الافتراضي. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [GisException](../../../aspose.gis/gisexception/) | خطأ أثناء معالجة أو قراءة بيانات نظام المعلومات الجغرافية (GIS). |
| ArgumentException | وحدة العرض أو الارتفاع هي !:Unit.MapUnits. |
| ArgumentOutOfRangeException | العرض أو الارتفاع سالب أو صفر. |

### انظر أيضًا

* class [AbstractPath](../../../aspose.gis/abstractpath/)
* struct [Measurement](../../../aspose.gis.rendering/measurement/)
* class [Renderer](../../../aspose.gis.rendering/renderer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsImage(string, Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage_2}

يصدّر هذه الهندسة إلى تمثيل صورة.

```csharp
public void AsImage(string outputPath, Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| outputPath | String | المسار إلى صورة الإخراج. |
| العرض | القياس | عرض الخريطة. |
| الارتفاع | القياس | ارتفاع الخريطة. |
| renderer | Renderer | المُعالج المستخدم. |
| symbolizer | VectorSymbolizer | رمز لتحديد الشكل يُستخدم في التصيير. إذا كان `null`، يُستخدم رمز التحديد الافتراضي. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [GisException](../../../aspose.gis/gisexception/) | خطأ أثناء معالجة أو قراءة بيانات نظام المعلومات الجغرافية (GIS). |
| ArgumentException | وحدة العرض أو الارتفاع هي !:Unit.MapUnits. |
| ArgumentOutOfRangeException | العرض أو الارتفاع سالب أو صفر. |

### انظر أيضًا

* struct [Measurement](../../../aspose.gis.rendering/measurement/)
* class [Renderer](../../../aspose.gis.rendering/renderer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)

---

## AsImage(Measurement, Measurement, Renderer, VectorSymbolizer) {#asimage}

يصدّر هذه الهندسة إلى تمثيل صورة.

```csharp
public Stream AsImage(Measurement width, Measurement height, Renderer renderer, 
    VectorSymbolizer symbolizer = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| العرض | القياس | عرض الخريطة. |
| الارتفاع | القياس | ارتفاع الخريطة. |
| renderer | Renderer | المُعالج المستخدم. |
| symbolizer | VectorSymbolizer | رمز لتحديد الشكل يُستخدم في التصيير. إذا كان `null`، يُستخدم رمز التحديد الافتراضي. |

### قيمة الإرجاع

الصورة كتيار

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | أي وسيط `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| [GisException](../../../aspose.gis/gisexception/) | خطأ أثناء معالجة أو قراءة بيانات نظام المعلومات الجغرافية (GIS). |
| ArgumentException | وحدة العرض أو الارتفاع هي !:Unit.MapUnits. |
| ArgumentOutOfRangeException | العرض أو الارتفاع سالب أو صفر. |

### انظر أيضًا

* struct [Measurement](../../../aspose.gis.rendering/measurement/)
* class [Renderer](../../../aspose.gis.rendering/renderer/)
* class [VectorSymbolizer](../../../aspose.gis.rendering.symbolizers/vectorsymbolizer/)
* class [Geometry](../)
* namespace [Aspose.Gis.Geometries](../../geometry/)
* assembly [Aspose.GIS](../../../)


