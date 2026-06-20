---
title: "Painter 类"
type: docs
weight: 60
url: /zh/python-net/aspose.gis.painting/painter/
---

**Summary:** 

**Module:** [aspose.gis.painting](/psd/python-net/aspose.gis.painting/)

**Full Name:** aspose.gis.painting.Painter

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Painter(engine)](#Painter_engine_1) | 初始化 Painter 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| brush | [PainterBrush](/psd/python-net/aspose.gis.painting/painterbrush) | r/w |    |
| 字体 | System.Drawing.Font | r/w |  |
| pen | [PainterPen](/psd/python-net/aspose.gis.painting/painterpen) | r/w |    |
| rounded_height | double | r |  |
| rounded_width | double | r |  |
| tranformation | [MatrixTransformation](/psd/python-net/aspose.gis.common/matrixtransformation/) | r/w |    |
## **Methods**
| **Name** | **Description** |
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

初始化 Painter 类的新实例

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| engine | [PaintEngine](/psd/python-net/aspose.gis.painting/paintengine) |  |

### Method: measure_text(text, font) {#measure_text_text_font_1}


```
 measure_text(text, font) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | string |  |
| 字体 | System.Drawing.Font |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [Size](/psd/python-net/aspose.gis.common/size/) |  |


### Method: measure_text_characters(text, font) {#measure_text_characters_text_font_2}


```
 measure_text_characters(text, font) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| text | string |  |
| 字体 | System.Drawing.Font |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Common.Size> |  |


