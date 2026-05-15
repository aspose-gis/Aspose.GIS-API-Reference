---
title: "Classe RasterMapLayer"
type: docs
weight: 250
url: /fr/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | Crée une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | Coloriseur à utiliser pour rendre les cellules du raster. |
| opacité | double | r/w | Opacité de la couche. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | Spécifie les options de déformation de la couche sur une carte. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Couche raster. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Symboliseur à utiliser pour rendre la couche. Si <see langword=\"null\" />, le coloriseur par défaut sera utilisé. |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche ouverte après que l'objet [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) soit libéré ; sinon, <see langword=\"false\" />. |

