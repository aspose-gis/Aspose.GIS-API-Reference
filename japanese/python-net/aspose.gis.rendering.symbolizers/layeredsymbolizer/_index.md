---
title: "LayeredSymbolizer クラス"
type: docs
weight: 20
url: /ja/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | 新しいインスタンスを作成します。 |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) は何も描画せず、適用されたジオメトリの描画を実質的にスキップします。 |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | レンダリング順序を決定します。<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            機能のすべてのシンボライザを描画し、次の機能へ進みます。 </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            シンボライザで全ての機能を描画し、次のシンボライザへ進みます。 </li><br/>            </ul> |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | 指定されたシンボライザを追加します。 |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

新しいインスタンスを作成します。

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | レンダリング順序を決定します。<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            機能をすべてのシンボライザで描画し、次の機能へ進みます。 </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            シンボライザで全ての機能を描画し、次のシンボライザへ描画を続けます。 </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

指定されたシンボライザを追加します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | 追加するシンボライザ。 |

