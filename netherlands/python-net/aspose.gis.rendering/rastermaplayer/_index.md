---
title: "RasterMapLayer Klasse"
type: docs
weight: 250
url: /nl/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | Creëert een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | Colorizer die gebruikt wordt om cellen van de raster weer te geven. |
| opacity | double | r/w | Doorzichtigheid van de laag. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | Specificeert vervormingsopties van de laag op een kaart. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

Creëert een nieuw exemplaar.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Rasterlaag. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Symbolizer die gebruikt wordt om de laag weer te geven. Als <see langword=\"null\" />, wordt de standaard colorizer gebruikt. |
| keep_open | bool | <see langword=\"true\" /> om de laag open te laten nadat het [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) object is vrijgegeven; anders, <see langword=\"false\" />. |

