---
title: "RasterImageMarker 类"
type: docs
weight: 80
url: /zh/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/
---

**Summary:** This symbolizer renders a provided raster image.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RasterImageMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_1) | 初始化 [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) 类的新实例。 |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_2) | 初始化 [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) 类的新实例。 |
| [RasterImageMarker(other)](#RasterImageMarker_other_3) | 初始化 [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定标记的高度。 |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | 指定标记形状的哪一侧将在水平上与点位置对齐。 |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定从点位置到形状锚点的水平偏移。 |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | 该 [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) 不绘制任何内容，并有效地跳过对其所应用的几何体的渲染。 |
| 不透明度 | double | r/w | 图层的不透明度。默认值为 1.0。 |
| 旋转 | double | r/w | 指定符号围绕其中心点的旋转角度，单位为十进制度数。<br/>            正值表示顺时针旋转，负值表示逆时针旋转。 |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | 指定标记形状的哪一侧将在垂直方向上与点位置对齐。 |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定从点位置到形状锚点的垂直偏移。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定标记的宽度。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |


### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_1}


```
 RasterImageMarker(image_path) 
```

初始化 [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_path | string | 文件的路径。 |

### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_2}


```
 RasterImageMarker(image_path) 
```

初始化 [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 文件的路径。 |

### Constructor: RasterImageMarker(other) {#RasterImageMarker_other_3}


```
 RasterImageMarker(other) 
```

初始化 [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | 另一个 [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) 用于复制数据。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | 此实例的克隆。 |


