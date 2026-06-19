---
title: "فئة RasterMapLayer"
type: docs
weight: 250
url: /ar/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | ينشئ مثلاً جديداً. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | مُلوّن لاستخدامه في عرض خلايا الصورة النقطية. |
| opacity | double | قراءة/كتابة | شفافية الطبقة. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | يحدد خيارات التشويه للطبقة على الخريطة. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

ينشئ مثلاً جديداً.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | طبقة نقطية. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | مُرمّز لاستخدامه في عرض الطبقة. إذا كان <see langword=\"null\" />، سيتم استخدام المُلوّن الافتراضي. |
| keep_open | bool | <see langword=\"true\" /> لترك الطبقة مفتوحة بعد التخلص من كائن [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); وإلا، <see langword=\"false\" />. |

