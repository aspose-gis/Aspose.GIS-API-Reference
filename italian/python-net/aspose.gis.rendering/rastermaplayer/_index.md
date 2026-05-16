---
title: "Classe RasterMapLayer"
type: docs
weight: 250
url: /it/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | Colorizzatore da utilizzare per renderizzare le celle del raster. |
| opacità | double | r/w | Opacità del livello. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | Specifica le opzioni di deformazione del livello su una mappa. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

Crea una nuova istanza.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Livello raster. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Simbolizzatore da utilizzare per renderizzare il livello. Se <see langword=\"null\" />, verrà usato il colorizzatore predefinito. |
| keep_open | bool | <see langword=\"true\" /> per lasciare il livello aperto dopo che l'oggetto [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) è stato eliminato; altrimenti, <see langword=\"false\" />. |

