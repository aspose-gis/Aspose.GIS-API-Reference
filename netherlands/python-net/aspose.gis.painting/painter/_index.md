---
title: "Painter Klasse"
type: docs
weight: 60
url: /nl/python-net/aspose.gis.painting/painter/
---

**Summary:** 

**Module:** [aspose.gis.painting](/psd/python-net/aspose.gis.painting/)

**Full Name:** aspose.gis.painting.Painter

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [Painter(engine)](#Painter_engine_1) | Initialiseert een nieuw exemplaar van de Painter klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| brush | [PainterBrush](/psd/python-net/aspose.gis.painting/painterbrush) | r/w |    |
| lettertype | System.Drawing.Font | r/w |  |
| pen | [PainterPen](/psd/python-net/aspose.gis.painting/painterpen) | r/w |    |
| rounded_height | double | r |  |
| rounded_width | double | r |  |
| tranformation | [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation/) | r/w |    |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| draw_characters(path) |  |
| draw_ellipse(center, rx, ry) |  |
| draw_image(image_path, width, height, opacity) |  |
| draw_line(c0, c1) |  |
| draw_polyline(polyline) |  |
| draw_rectangle(rectangle) |  |
| draw_shape(shape) |  |
| draw_text(bottom_left, text) |  |
| [measure_text(text, font)](#measure_text_text_font_1) |    |
| [measure_text_characters(text, font)](#measure_text_characters_text_font_2) |    |
| rotate(cos, sin) |  |
| rotate(degrees) |  |
| scale(zoom_x, zoom_y) |  |
| start_new_layer(opacity) |  |
| start_new_layer(options) |  |
| translate(c) |  |
| translate(x, y) |  |


### Constructor: Painter(engine) {#Painter_engine_1}


```
 Painter(engine) 
```

Initialiseert een nieuw exemplaar van de Painter klasse

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| engine | [PaintEngine](/psd/python-net/aspose.gis.painting/paintengine) |  |

### Method: measure_text(text, font) {#measure_text_text_font_1}


```
 measure_text(text, font) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | string |  |
| lettertype | System.Drawing.Font |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Size](/psd/python-net/aspose.gis.common/size/) |  |


### Method: measure_text_characters(text, font) {#measure_text_characters_text_font_2}


```
 measure_text_characters(text, font) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| text | string |  |
| lettertype | System.Drawing.Font |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Common.Size> |  |


