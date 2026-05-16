---
title: "LineLabelPlacement 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | 새 인스턴스를 생성합니다. |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | 새 인스턴스를 생성합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | 라벨이 선형 경로와 정렬되는 방식을 지정합니다. 기본값은 [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/)입니다. |
| max_angle_delta | double | r/w | [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/)와 함께 사용할 때, 곡선 라벨에서 두 문자 사이의 최대 각도를 도 단위로 설정합니다.<br/>            연속된 문자에 대해. 기본값은 25입니다. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 선형 경로에서의 오프셋.<br/>            양수 값은 선의 왼쪽으로, 음수 값은 오른쪽으로 오프셋됩니다. 기본값은 0입니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

새 인스턴스를 생성합니다.

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

새 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | 데이터를 복사할 다른 [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/)입니다. |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | 이 인스턴스의 복제본입니다. |


