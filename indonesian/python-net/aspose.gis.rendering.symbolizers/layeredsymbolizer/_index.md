---
title: "Kelas LayeredSymbolizer"
type: docs
weight: 20
url: /id/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | Membuat instance baru. |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | Membuat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) tidak menggambar apa pun dan secara efektif melewatkan perenderan geometri yang diterapkannya. |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | Menentukan urutan rendering.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            render semua simbolizer untuk fitur tersebut, kemudian lanjut ke fitur berikutnya. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            render semua fitur dengan simbolizer, kemudian lanjut ke simbolizer berikutnya. </li><br/>            </ul> |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | Menambahkan simbolizer yang ditentukan. |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

Membuat instance baru.

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | Menentukan urutan rendering.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            render fitur dengan semua simbolizer, kemudian lanjut ke fitur berikutnya. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            render semua fitur dengan sebuah simbolizer, kemudian lanjut menggambar fitur ke simbolizer berikutnya. </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

Menambahkan simbolizer yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Simbolizer yang akan ditambahkan. |

