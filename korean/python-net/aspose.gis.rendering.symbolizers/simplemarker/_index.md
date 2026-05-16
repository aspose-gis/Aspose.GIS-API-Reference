---
title: "SimpleMarker 클래스"
type: docs
weight: 130
url: /ko/python-net/aspose.gis.rendering.symbolizers/simplemarker/
---

**Summary:** Simple point symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleMarker()](#SimpleMarker__1) | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) 클래스의 새 인스턴스를 초기화합니다. |
| [SimpleMarker(other)](#SimpleMarker_other_2) | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| fill_color | System.Drawing.Color | r/w | 채우기 색상 및 투명도를 지정합니다. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | 마커 모양의 어느 쪽이 포인트 위치와 수평으로 정렬될지 지정합니다. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 점 위치에서 형태 고정점까지의 수평 오프셋을 지정합니다. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | 해당 [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) 은 아무것도 그리지 않으며 적용된 기하학의 렌더링을 효과적으로 건너뜁니다. |
| 회전 | double | r/w | 심볼을 중심점 기준으로 회전시킵니다(십진도).<br/>            양수 값은 시계 방향 회전을 나타내고, 음수 값은 반시계 방향 회전을 나타냅니다. |
| shape_type | [MarkerShapeType](/psd/python-net/aspose.gis.rendering.symbolizers/markershapetype) | r/w | 마커의 모양을 지정합니다. |
| size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 마커의 크기를 지정합니다. |
| stroke_color | System.Drawing.Color | r/w | 선에 적용되는 색상 및 투명도를 지정합니다. |
| stroke_dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 선 시작점부터 대시 패턴 시작점까지의 거리를 지정합니다. |
| stroke_dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | 교차하는 대시와 공백의 길이를 지정하는 거리 배열을 지정합니다.<br/>            대시선에서. |
| stroke_line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | 선분이 교차하는 지점에서 선이 렌더링되는 방식을 결정합니다. |
| stroke_style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | 심볼 라인이 어떻게 그려져야 하는지 지정합니다. |
| stroke_width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 선의 너비를 지정합니다. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | 마커 형태의 어느 쪽이 점 위치와 수직으로 정렬될지 지정합니다. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 점 위치에서 형태 고정점까지의 수직 오프셋을 지정합니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |


### Constructor: SimpleMarker() {#SimpleMarker__1}


```
 SimpleMarker() 
```

[SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) 클래스의 새 인스턴스를 초기화합니다.

### Constructor: SimpleMarker(other) {#SimpleMarker_other_2}


```
 SimpleMarker(other) 
```

[SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/) 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | 데이터를 복사할 다른 [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/)입니다. |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | 이 인스턴스의 복제본입니다. |


