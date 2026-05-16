---
title: "Kelas RasterMapLayer"
type: docs
weight: 250
url: /id/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | Membuat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | Colorizer yang digunakan untuk merender sel raster. |
| opasitas | double | r/w | Opasitas lapisan. |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | Menentukan opsi warp lapisan pada peta. |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Lapisan raster. |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Symbolizer yang digunakan untuk merender lapisan. Jika <see langword=\"null\" />, colorizer default akan digunakan. |
| keep_open | bool | <see langword=\"true\" /> untuk membiarkan lapisan tetap terbuka setelah objek [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) dibuang; jika tidak, <see langword=\"false\" />. |

