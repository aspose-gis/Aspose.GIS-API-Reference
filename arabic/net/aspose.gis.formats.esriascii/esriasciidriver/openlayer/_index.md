---
title: "EsriAsciiDriver.OpenLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة EsriAsciiDriver. يفتح الطبقة للقراءة"
type: docs
weight: 20
url: /ar/net/aspose.gis.formats.esriascii/esriasciidriver/openlayer/
---
## OpenLayer(AbstractPath, RasterDriverOptions) {#openlayer_2}

يفتح الطبقة للقراءة.

```csharp
public override RasterLayer OpenLayer(AbstractPath path, RasterDriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | AbstractPath | المسار إلى الملف. |
| الخيارات | RasterDriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثال من [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| ArgumentNullException | المسار هو `null`. |
| IOException | حدث خطأ في الإدخال/الإخراج. |
| NotSupportedException | السائق لا يمكنه فتح طبقات الراستر (انظر [`CanOpenLayers`](../canopenlayers/)). |

### انظر أيضًا

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [RasterDriverOptions](../../../aspose.gis/rasterdriveroptions/)
* class [EsriAsciiDriver](../)
* namespace [Aspose.Gis.Formats.EsriAscii](../../esriasciidriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(string, EsriAsciiOptions) {#openlayer_4}

يفتح طبقة للقراءة.

```csharp
public RasterLayer OpenLayer(string path, EsriAsciiOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | String | المسار إلى الملف. |
| الخيارات | EsriAsciiOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثال من [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/).

### انظر أيضًا

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [EsriAsciiOptions](../../esriasciioptions/)
* class [EsriAsciiDriver](../)
* namespace [Aspose.Gis.Formats.EsriAscii](../../esriasciidriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath, EsriAsciiOptions) {#openlayer_1}

يفتح طبقة للقراءة.

```csharp
public RasterLayer OpenLayer(AbstractPath path, EsriAsciiOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| المسار | AbstractPath | المسار إلى الملف. |
| الخيارات | EsriAsciiOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثال من [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/).

### انظر أيضًا

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [EsriAsciiOptions](../../esriasciioptions/)
* class [EsriAsciiDriver](../)
* namespace [Aspose.Gis.Formats.EsriAscii](../../esriasciidriver/)
* assembly [Aspose.GIS](../../../)


