---
title: "SimpleMarker 类"
type: docs
weight: 130
url: /zh/python-net/aspose.gis.rendering.symbolizers/simplemarker/
---

**Summary:** Simple point symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [SimpleMarker()](#SimpleMarker__1) | 初始化 [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) 类的新实例。 |
| [SimpleMarker(other)](#SimpleMarker_other_2) | 初始化 [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| fill_color | System.Drawing.Color | r/w | 指定填充的颜色和透明度。 |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | 指定标记形状的哪一侧将水平对齐到点位置。 |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定从点位置到形状锚点的水平偏移。 |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | 此 [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) 不绘制任何内容，并有效地跳过对其所应用的几何体的渲染。 |
| 旋转 | double | r/w | 指定符号围绕其中心点的旋转角度，单位为十进制度数。<br/>            正值表示顺时针旋转，负值表示逆时针旋转。 |
| shape_type | [MarkerShapeType](/psd/python-net/aspose.gis.rendering.symbolizers/markershapetype) | r/w | 指定标记的形状。 |
| size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定标记的大小。 |
| stroke_color | System.Drawing.Color | r/w | 指定线条的颜色和透明度。 |
| stroke_dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定从线段起点到破折号模式起始处的距离。 |
| stroke_dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | 指定一个距离数组，用于指定交替的短划线和空格的长度<br/>            在虚线中。 |
| stroke_line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | 确定线段交叉处的线条渲染方式。 |
| stroke_style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | 指定符号线的绘制方式。 |
| stroke_width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定线条的宽度。 |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | 指定标记形状的哪一侧将垂直对齐到点位置。 |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定从点位置到形状锚点的垂直偏移。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |


### Constructor: SimpleMarker() {#SimpleMarker__1}


```
 SimpleMarker() 
```

初始化 [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) 类的新实例。

### Constructor: SimpleMarker(other) {#SimpleMarker_other_2}


```
 SimpleMarker(other) 
```

初始化 [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | 要从中复制数据的另一个 [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/)。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | 此实例的克隆。 |


