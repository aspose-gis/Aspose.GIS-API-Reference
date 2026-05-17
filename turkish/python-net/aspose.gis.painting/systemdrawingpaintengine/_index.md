---
title: "SystemDrawingPaintEngine Sınıfı"
type: docs
weight: 190
url: /tr/python-net/aspose.gis.painting/systemdrawingpaintengine/
---

**Summary:** 

**Module:** [aspose.gis.painting](/psd/python-net/aspose.gis.painting/)

**Full Name:** aspose.gis.painting.SystemDrawingPaintEngine

**Inheritance:** PaintEngine

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| rounded_height | double | r |  |
| rounded_width | double | r |  |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| close() |  |
| draw_characters(text_path) |  |
| draw_ellipse(center, rx, ry) |  |
| draw_image(image_path, width, height, opacity) |  |
| draw_polyline(polyline) |  |
| draw_rectangle(rectangle) |  |
| draw_shape(shape) |  |
| draw_text(bottom_left, text) |  |
| [measure_text(text, text_font)](#measure_text_text_text_font_1) |    |
| [measure_text_characters(text, text_font)](#measure_text_characters_text_text_font_2) |    |
| start_new_layer(new_options) |  |
| update_state(state) |  |


### Method: measure_text(text, text_font) {#measure_text_text_text_font_1}


```
 measure_text(text, text_font) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | string |  |
| text_font | System.Drawing.Font |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Size](/psd/python-net/aspose.gis.common/size/) |  |


### Method: measure_text_characters(text, text_font) {#measure_text_characters_text_text_font_2}


```
 measure_text_characters(text, text_font) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | string |  |
| text_font | System.Drawing.Font |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Common.Size> |  |


