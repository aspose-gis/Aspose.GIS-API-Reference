---
title: "RasterMapLayer.RasterMapLayer"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "منشئ RasterMapLayer. ينشئ نسخة جديدة"
type: docs
weight: 10
url: /ar/net/aspose.gis.rendering/rastermaplayer/rastermaplayer/
---
## RasterMapLayer constructor

ينشئ نسخة جديدة.

```csharp
public RasterMapLayer(RasterLayer layer, RasterColorizer colorizer = null, bool keepOpen = false)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الطبقة | RasterLayer | طبقة Raster. |
| ملون | RasterColorizer | Symbolizer لاستخدامه في تصيير الطبقة. إذا كان `null`، سيتم استخدام colorizer الافتراضي. |
| keepOpen | Boolean | `true` لترك الطبقة مفتوحة بعد التخلص من كائن [`VectorMapLayer`](../../vectormaplayer/); وإلا، `false`. |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | الطبقة هي `null`. |

### انظر أيضًا

* class [RasterLayer](../../../aspose.gis.raster/rasterlayer/)
* class [RasterColorizer](../../../aspose.gis.rendering.colorizers/rastercolorizer/)
* class [RasterMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../rastermaplayer/)
* assembly [Aspose.GIS](../../../)


