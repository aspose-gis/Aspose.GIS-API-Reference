---
title: "RasterMapLayer Sınıfı"
type: docs
weight: 250
url: /tr/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | Yeni bir örnek oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | Raster hücrelerini renderlemek için kullanılacak renkleyici. |
| opaklık | double | r/w | Katmanın opaklığı. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | Harita üzerindeki katmanın bükülme seçeneklerini belirtir. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

Yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Raster katmanı. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Katmanı renderlemek için kullanılacak sembolleyici. Eğer <see langword=\"null\" /> ise, varsayılan renkleyici kullanılacaktır. |
| keep_open | bool | <see langword=\"true\" /> katmanı, [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) nesnesi serbest bırakıldıktan sonra açık bırakmak için; aksi takdirde <see langword=\"false\" />. |

