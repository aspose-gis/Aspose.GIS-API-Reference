---
title: "Κατηγορία RasterMapLayer"
type: docs
weight: 250
url: /el/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | Δημιουργεί νέο αντικείμενο. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | Colorizer για χρήση στην απόδοση των κελιών του raster. |
| opacity | double | r/w | Διαφάνεια του στρώματος. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | Καθορίζει επιλογές παραμόρφωσης του στρώματος σε χάρτη. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

Δημιουργεί νέο αντικείμενο.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Στρώμα raster. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Symbolizer για χρήση στην απόδοση του στρώματος. Εάν <see langword="null" />, θα χρησιμοποιηθεί το προεπιλεγμένο colorizer. |
| keep_open | bool | <see langword="true" /> για να αφήσετε το στρώμα ανοιχτό μετά την απελευθέρωση του αντικειμένου [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/); διαφορετικά, <see langword="false" />. |

