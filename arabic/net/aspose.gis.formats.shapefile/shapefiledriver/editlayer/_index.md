---
title: "ShapefileDriver.EditLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة ShapefileDriver. تفتح طبقة للتحرير"
type: docs
weight: 50
url: /ar/net/aspose.gis.formats.shapefile/shapefiledriver/editlayer/
---
## EditLayer(AbstractPath, DriverOptions) {#editlayer}

يفتح طبقة للتحرير.

```csharp
public override VectorLayer EditLayer(AbstractPath path, DriverOptions options = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | AbstractPath | المسار إلى الملف. |
| الخيارات | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثيل من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../../aspose.gis/gisexception/) | خطأ في قراءة العنصر من الملف. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [DriverOptions](../../../aspose.gis/driveroptions/)
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
* assembly [Aspose.GIS](../../../)

---

## EditLayer(string, ShapefileOptions) {#editlayer_3}

يفتح طبقة للتحرير.

```csharp
public VectorLayer EditLayer(string path, ShapefileOptions options = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار إلى الملف. |
| الخيارات | ShapefileOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثيل من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [ShapefileOptions](../../shapefileoptions/)
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
* assembly [Aspose.GIS](../../../)

---

## EditLayer(AbstractPath, ShapefileOptions) {#editlayer_1}

يفتح طبقة للتحرير.

```csharp
public VectorLayer EditLayer(AbstractPath path, ShapefileOptions options = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | AbstractPath | المسار إلى الملف. |
| الخيارات | ShapefileOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثيل من [`VectorLayer`](../../../aspose.gis/vectorlayer/).

### انظر أيضًا

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [ShapefileOptions](../../shapefileoptions/)
* class [ShapefileDriver](../)
* namespace [Aspose.Gis.Formats.Shapefile](../../shapefiledriver/)
* assembly [Aspose.GIS](../../../)


