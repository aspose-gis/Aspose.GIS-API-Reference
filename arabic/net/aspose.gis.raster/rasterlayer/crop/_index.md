---
title: "RasterLayer.Crop"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة RasterLayer. تقص طبقة الراستر باستخدام شكل وشبكة قنوات"
type: docs
weight: 110
url: /ar/net/aspose.gis.raster/rasterlayer/crop/
---
## Crop(IGeometry, double[]) {#crop}

يقص طبقة الراستر باستخدام شكل (و قناع القناة).

```csharp
public RasterLayer Crop(IGeometry geometry, double[] masks = null)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| هندسة | IGeometry | Geometry تم تمثيل الشكل. |
| أقنعة | Double[] | قناع لطبقة القص |

### قيمة الإرجاع

طبقة الراستر المقصوصة. إذا لم يتم العثور على تقاطعات تُعيد `null`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المعامل لا يمكن أن يكون فارغًا. اسم المعامل: geometry. |
| NotSupportedException | المعامل لا يمكن أن يكون مختلفًا عن مضلع أو سطح. اسم المعامل: geometry. |
| InvalidOperationException | الطبقة الأصلية لا يمكن أن تكون CropRasterLayer أخرى. |
| [GisException](../../../aspose.gis/gisexception/) | خطأ أثناء قص الطبقة. |

### انظر أيضًا

* interface [IGeometry](../../../aspose.gis.geometries/igeometry/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)

---

## Crop(double[]) {#crop_1}

يقص طبقة الراستر باستخدام قناع القناة).

```csharp
public RasterLayer Crop(double[] masks)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| أقنعة | Double[] | قناع لطبقة القص |

### قيمة الإرجاع

طبقة الراستر المقصوصة. إذا لم يتم العثور على تقاطعات تُعيد `null`.

### استثناءات

| استثناء | شرط |
| --- | --- |
| InvalidOperationException |  |

### انظر أيضًا

* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


