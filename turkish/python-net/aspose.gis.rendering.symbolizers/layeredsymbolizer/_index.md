---
title: "LayeredSymbolizer Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | Yeni bir örnek oluşturur. |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | Yeni bir örnek oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) hiçbir şey çizmez ve uygulandığı geometriyi etkili bir şekilde renderlamayı atlar. |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | Renderleme sırasını belirler.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            özelliğin tüm sembolizörlerini render eder, ardından bir sonraki özelliğe geçer. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            sembolizör ile tüm özellikleri render eder, ardından bir sonraki sembolizöre geçer. </li><br/>            </ul> |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | Belirtilen sembolizörü ekler. |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

Yeni bir örnek oluşturur.

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

Yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | Renderleme sırasını belirler.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            özelliği tüm sembolizörlerle render eder, ardından bir sonraki özelliğe geçer. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            bir sembolizör ile tüm özellikleri render eder, ardından bir sonraki sembolizöre geçmek için özellik çizmeye devam eder. </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

Belirtilen sembolizörü ekler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Eklenecek sembolizör. |

