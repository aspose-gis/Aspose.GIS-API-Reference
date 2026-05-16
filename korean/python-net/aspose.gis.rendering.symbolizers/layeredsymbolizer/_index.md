---
title: "LayeredSymbolizer 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---

**Summary:** A symbolizer that renders several other symbolizers.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.LayeredSymbolizer

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LayeredSymbolizer()](#LayeredSymbolizer__1) | 새 인스턴스를 생성합니다. |
| [LayeredSymbolizer(rendering_order)](#LayeredSymbolizer_rendering_order_2) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | 해당 [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) 은 아무것도 그리지 않으며 적용된 기하학의 렌더링을 효과적으로 건너뜁니다. |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | r/w | 렌더링 순서를 결정합니다.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            해당 피처에 대한 모든 심볼라이저를 렌더링한 후 다음 피처로 진행합니다. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            심볼라이저를 사용하여 모든 피처를 렌더링한 후 다음 심볼라이저로 진행합니다. </li><br/>            </ul> |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(symbolizer)](#add_symbolizer_1) | 지정된 심볼라이저를 추가합니다. |


### Constructor: LayeredSymbolizer() {#LayeredSymbolizer__1}


```
 LayeredSymbolizer() 
```

새 인스턴스를 생성합니다.

### Constructor: LayeredSymbolizer(rendering_order) {#LayeredSymbolizer_rendering_order_2}


```
 LayeredSymbolizer(rendering_order) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rendering_order | [RenderingOrder](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder) | 렌더링 순서를 결정합니다.<br/>            <ul><br/>            <li>[RenderingOrder.BY_FEATURES](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            모든 심볼라이저를 사용하여 피처를 렌더링한 후 다음 피처로 진행합니다. </li><br/>            <li>[RenderingOrder.BY_LAYERS](/psd/python-net/aspose.gis.rendering.symbolizers/renderingorder/) -<br/>            심볼라이저 하나로 모든 피처를 렌더링한 후 다음 심볼라이저로 피처 그리기를 진행합니다. </li><br/>            </ul> |

### Method: add(symbolizer) {#add_symbolizer_1}


```
 add(symbolizer) 
```

지정된 심볼라이저를 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer) | 추가할 심볼라이저. |

