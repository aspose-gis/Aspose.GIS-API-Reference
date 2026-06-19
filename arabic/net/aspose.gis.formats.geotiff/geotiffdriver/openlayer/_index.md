---
title: "GeoTiffDriver.OpenLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة GeoTiffDriver. يفتح الطبقة للقراءة"
type: docs
weight: 20
url: /ar/net/aspose.gis.formats.geotiff/geotiffdriver/openlayer/
---
## OpenLayer(AbstractPath, RasterDriverOptions) {#openlayer_2}

يفتح الطبقة للقراءة.

```csharp
public override RasterLayer OpenLayer(AbstractPath path, RasterDriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | RasterDriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثيل لـ [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/).

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
* class [GeoTiffDriver](../)
* namespace [Aspose.Gis.Formats.GeoTiff](../../geotiffdriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(string, GeoTiffOptions) {#openlayer_4}

يفتح طبقة للقراءة.

```csharp
public RasterLayer OpenLayer(string path, GeoTiffOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | المسار إلى الملف. |
| options | GeoTiffOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثيل لـ [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/).

### انظر أيضًا

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [GeoTiffOptions](../../geotiffoptions/)
* class [GeoTiffDriver](../)
* namespace [Aspose.Gis.Formats.GeoTiff](../../geotiffdriver/)
* assembly [Aspose.GIS](../../../)

---

## OpenLayer(AbstractPath, GeoTiffOptions) {#openlayer_1}

يفتح طبقة للقراءة.

```csharp
public RasterLayer OpenLayer(AbstractPath path, GeoTiffOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | المسار إلى الملف. |
| options | GeoTiffOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

مثيل لـ [`RasterLayer`](../../../aspose.gis.raster/rasterlayer/).

### انظر أيضًا

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [GeoTiffOptions](../../geotiffoptions/)
* class [GeoTiffDriver](../)
* namespace [Aspose.Gis.Formats.GeoTiff](../../geotiffdriver/)
* assembly [Aspose.GIS](../../../)


