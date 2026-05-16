---
title: "SimpleLine 클래스"
type: docs
weight: 120
url: /ko/python-net/aspose.gis.rendering.symbolizers/simpleline/
---

**Summary:** Simple line symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleLine

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleLine()](#SimpleLine__1) | 새 인스턴스를 생성합니다. |
| [SimpleLine(other)](#SimpleLine_other_2) | [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cap_style | [CapStyle](/psd/python-net/aspose.gis.rendering/capstyle) | r/w | 선의 끝 부분이 어떻게 렌더링되는지 지정합니다. |
| color | System.Drawing.Color | r/w | 선에 적용되는 색상 및 투명도를 지정합니다. |
| dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 선 시작점부터 대시 패턴 시작점까지의 거리를 지정합니다. |
| dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | 교차하는 대시와 공백의 길이를 지정하는 거리 배열을 지정합니다.<br/>            대시선에서. |
| line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | 선분이 교차하는 지점에서 선이 렌더링되는 방식을 결정합니다. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | 해당 [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) 은 아무것도 그리지 않으며 적용된 기하학의 렌더링을 효과적으로 건너뜁니다. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 원본 라인으로부터 오프셋을 지정합니다.<br/>            양의 거리인 경우 오프셋은 입력 라인의 왼쪽(라인 방향을 기준) 에 위치합니다.<br/>            음의 거리인 경우 오른쪽에 위치합니다. |
| style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | 심볼 라인이 어떻게 그려져야 하는지 지정합니다. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 선의 너비를 지정합니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |


### Constructor: SimpleLine() {#SimpleLine__1}


```
 SimpleLine() 
```

새 인스턴스를 생성합니다.

### Constructor: SimpleLine(other) {#SimpleLine_other_2}


```
 SimpleLine(other) 
```

[SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | 복사할 다른 [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/). |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | 이 인스턴스의 복제본입니다. |


