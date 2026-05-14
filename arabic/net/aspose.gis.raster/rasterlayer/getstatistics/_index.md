---
title: "RasterLayer.GetStatistics"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة RasterLayer. احسب إحصاءات الملخص التي تتكون من العدد والمجموع والمتوسط والحد الأدنى والحد الأقصى"
type: docs
weight: 160
url: /ar/net/aspose.gis.raster/rasterlayer/getstatistics/
---
## RasterLayer.GetStatistics method

احسب الإحصاءات الملخصة التي تتضمن العدد، المجموع، المتوسط، الحد الأدنى، الحد الأقصى.

```csharp
public RasterStatistics GetStatistics(int bandIndex = 0, bool excludeNodataValue = true)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| bandIndex | Int32 | فهرس النطاق. يبدأ الترقيم من 0. |
| excludeNodataValue | Boolean | يسمح باستبعاد قيم 'nodata'. إذا تم تعيين 'excludeNodataValue' إلى false، فسيتم اعتبار جميع البكسلات. |

### قيمة الإرجاع

إحصاءات الملخص.

### انظر أيضًا

* class [RasterStatistics](../../rasterstatistics/)
* class [RasterLayer](../)
* namespace [Aspose.Gis.Raster](../../rasterlayer/)
* assembly [Aspose.GIS](../../../)


