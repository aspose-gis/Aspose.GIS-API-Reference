---
title: "PaintEngine Класс"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.painting/paintengine/
---

**Summary:** 

**Module:** [aspose.gis.painting](/psd/python-net/aspose.gis.painting/)

**Full Name:** aspose.gis.painting.PaintEngine

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| rounded_height | double | r |  |
| rounded_width | double | r |  |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| close() |  |
| draw_characters(path) |  |
| draw_ellipse(center, rx, ry) |  |
| draw_image(stream, width, height, opacity) |  |
| draw_polyline(polyline) |  |
| draw_rectangle(rectangle) |  |
| draw_shape(shape) |  |
| draw_text(bottom_left, text) |  |
| [measure_text(text, font)](#measure_text_text_font_1) |    |
| [measure_text_characters(text, font)](#measure_text_characters_text_font_2) |    |
| start_new_layer(new_options) |  |
| update_state(state) |  |


### Method: measure_text(text, font) {#measure_text_text_font_1}


```
 measure_text(text, font) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string |  |
| шрифт | System.Drawing.Font |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [Size](/psd/python-net/aspose.gis.common/size/) |  |


### Method: measure_text_characters(text, font) {#measure_text_characters_text_font_2}


```
 measure_text_characters(text, font) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string |  |
| шрифт | System.Drawing.Font |  |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Common.Size> |  |


