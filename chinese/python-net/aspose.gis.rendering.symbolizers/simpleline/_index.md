---
title: "SimpleLine 类"
type: docs
weight: 120
url: /zh/python-net/aspose.gis.rendering.symbolizers/simpleline/
---

**Summary:** Simple line symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleLine

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [SimpleLine()](#SimpleLine__1) | 创建新实例。 |
| [SimpleLine(other)](#SimpleLine_other_2) | 初始化 [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) 类的新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| cap_style | [CapStyle](/psd/python-net/aspose.gis.rendering/capstyle) | r/w | 指定线段在端点的渲染方式。 |
| 颜色 | System.Drawing.Color | r/w | 指定线条的颜色和透明度。 |
| dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定从线段起点到破折号模式起始处的距离。 |
| dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | 指定一个距离数组，用于指定交替的短划线和空格的长度<br/>            在虚线中。 |
| line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | 确定线段交叉处的线条渲染方式。 |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | 此 [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) 不绘制任何内容，并有效地跳过对其所应用的几何体的渲染。 |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定相对于原始线的偏移。<br/>            对于正距离，偏移将在输入线的左侧（相对于线的方向）。<br/>            对于负距离，偏移将在右侧。 |
| style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | 指定符号线的绘制方式。 |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 指定线条的宽度。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |


### Constructor: SimpleLine() {#SimpleLine__1}


```
 SimpleLine() 
```

创建新实例。

### Constructor: SimpleLine(other) {#SimpleLine_other_2}


```
 SimpleLine(other) 
```

初始化 [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) 类的新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | 要从中复制数据的另一个 [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) 。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | 此实例的克隆。 |


