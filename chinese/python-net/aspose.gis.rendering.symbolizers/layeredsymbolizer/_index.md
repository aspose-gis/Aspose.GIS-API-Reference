---
title: "LayeredSymbolizer 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | 创建新实例。 |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | 此 [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) 不绘制任何内容，并有效地跳过对其所应用的几何体的渲染。 |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | 确定渲染顺序。<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            为该要素渲染所有符号器，然后继续下一个要素。 </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            使用该符号器渲染所有要素，然后继续下一个符号器。 </li><br/>            </ul> |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | 添加指定的符号器。 |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

创建新实例。

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | 确定渲染顺序。<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            使用所有符号器渲染要素，然后继续下一个要素。 </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            使用一个符号器渲染所有要素，然后继续绘制要素到下一个符号器。 </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

添加指定的符号器。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | 要添加的符号器。 |

