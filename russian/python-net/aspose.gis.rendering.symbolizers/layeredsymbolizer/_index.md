---
title: "Класс LayeredSymbolizer"
type: docs
weight: 20
url: /ru/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | Создаёт новый экземпляр. |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | Создаёт новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Элемент [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ничего не рисует и фактически пропускает отрисовку геометрии, к которой он применён. |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | Определяет порядок отрисовки.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            отрисовывать все символизаторы для объекта, затем переходить к следующему объекту. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            отрисовывать все объекты с символизатором, затем переходить к следующему символизатору. </li><br/>            </ul> |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | Добавляет указанный символизатор. |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

Создаёт новый экземпляр.

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | Определяет порядок отрисовки.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            отрисовывать объект со всеми символизаторами, затем переходить к следующему объекту. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            отрисовывать все объекты с символизатором, затем продолжать отрисовку объектов со следующим символизатором. </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

Добавляет указанный символизатор.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | Символизатор для добавления. |

