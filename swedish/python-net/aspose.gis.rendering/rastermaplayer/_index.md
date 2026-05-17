---
title: "RasterMapLayer klass"
type: docs
weight: 250
url: /sv/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | Skapar ny instans. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | Colorizer att använda för att rendera rasterceller. |
| opacitet | double | läs/skriv | Opacitet för lagret. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | Anger warp-alternativ för lagret på en karta. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

Skapar ny instans.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Rasterlager. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Symbolizer att använda för att rendera lagret. Om <see langword="null" />, används standard‑colorizer. |
| keep_open | bool | <see langword="true" /> för att lämna lagret öppet efter att [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/)-objektet har frigjorts; annars <see langword="false" />. |

