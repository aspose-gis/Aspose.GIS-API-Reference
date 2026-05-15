---
title: "RasterMapLayer Klasse"
type: docs
weight: 250
url: /de/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | Erstellt eine neue Instanz. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | Colorizer, der zum Rendern der Zellen des Rasters verwendet wird. |
| Deckkraft | double | r/w | Deckkraft der Ebene. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | Gibt Verzerrungsoptionen der Ebene auf einer Karte an. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

Erstellt eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Rasterebene. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Symbolizer, der zum Rendern der Ebene verwendet wird. Wenn <see langword="null" />, wird der Standard‑Colorizer verwendet. |
| keep_open | bool | <see langword="true" /> um die Ebene nach dem Entsorgen des [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) Objekts offen zu lassen; andernfalls, <see langword="false" />. |

