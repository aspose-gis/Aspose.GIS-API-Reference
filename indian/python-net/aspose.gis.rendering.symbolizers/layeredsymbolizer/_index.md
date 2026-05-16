---
title: "LayeredSymbolizer क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | नया इंस्टेंस बनाता है। |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | नया इंस्टेंस बनाता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) कुछ नहीं बनाता और प्रभावी रूप से उस ज्योमेट्री की रेंडरिंग को छोड़ देता है जिस पर यह लागू किया गया है। |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | रेंडरिंग क्रम निर्धारित करता है.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            फ़ीचर के लिए सभी सिम्बोलाइज़र रेंडर करता है, फिर अगले फ़ीचर पर आगे बढ़ें। </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            सिम्बोलाइज़र के साथ सभी फ़ीचर रेंडर करता है, फिर अगले सिम्बोलाइज़र पर आगे बढ़ें। </li><br/>            </ul> |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | निर्दिष्ट सिम्बोलाइज़र जोड़ता है। |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

नया इंस्टेंस बनाता है।

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | रेंडरिंग क्रम निर्धारित करता है.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            फ़ीचर को सभी सिम्बोलाइज़र के साथ रेंडर करता है, फिर अगले फ़ीचर पर आगे बढ़ें। </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            सिम्बोलाइज़र के साथ सभी फ़ीचर रेंडर करता है, फिर अगले सिम्बोलाइज़र पर फ़ीचर ड्रॉइंग जारी रखें। </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

निर्दिष्ट सिम्बोलाइज़र जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | जोड़ने के लिए सिम्बोलाइज़र। |

