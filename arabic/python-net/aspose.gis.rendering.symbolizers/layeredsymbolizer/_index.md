---
title: "فئة LayeredSymbolizer"
type: docs
weight: 20
url: /ar/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | ينشئ نسخة جديدة. |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | ينشئ نسخة جديدة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | يقوم [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) بعدم رسم أي شيء ويتخطى فعلياً رسم الهندسة التي يُطبق عليها. |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | يحدد ترتيب العرض.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            عرض جميع الرموز للميزة، ثم الانتقال إلى الميزة التالية. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            عرض جميع الميزات باستخدام الرمز، ثم الانتقال إلى الرمز التالي. </li><br/>            </ul> |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | يضيف الرمز المحدد. |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

ينشئ نسخة جديدة.

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

ينشئ نسخة جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | يحدد ترتيب العرض.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            عرض الميزة بجميع الرموز، ثم الانتقال إلى الميزة التالية. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            عرض جميع الميزات باستخدام رمز واحد، ثم المتابعة برسم الميزات إلى الرمز التالي. </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

يضيف الرمز المحدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | الرمز المراد إضافته. |

