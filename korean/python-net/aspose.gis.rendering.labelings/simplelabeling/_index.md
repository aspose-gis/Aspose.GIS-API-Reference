---
title: "SimpleLabeling 클래스"
type: docs
weight: 80
url: /ko/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | 새로운 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 클래스 인스턴스를 초기화합니다. |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | 새로운 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 클래스 인스턴스를 초기화합니다. |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | 새로운 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | 텍스트 색상을 결정합니다. |
| font_family | string | r/w | 텍스트를 렌더링할 때 사용할 글꼴 패밀리입니다. 기본값은 시스템에 따라 달라집니다. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 텍스트 크기. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | 텍스트에 적용할 스타일. |
| halo_color | System.Drawing.Color | r/w | 텍스트 주변의 후광(스트로크) 색상. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 텍스트 주변의 후광(스트로크) 크기. |
| label_attribute | string | r/w | 레이블의 소스로 사용할 속성 이름입니다. [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/)이 설정된 경우 무시됩니다.<br/> 렌더링 전에 [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 또는 [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 중 하나가 설정되어야 합니다;<br/> 그렇지 않으면 InvalidOperationException이 발생합니다. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | 멀티파트 기하학에 대한 렌더링 동작을 지정합니다. 기본값은 [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/)입니다. |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | 다음의 인스턴스를 가져옵니다: [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | 레이블 배치는 레이블이 피처의 기하학에 상대적으로 어떻게 배치되는지를 지정합니다. |
| 우선순위 | int | r/w | 다른 레이블과 겹치는 경우 이 레이블의 우선순위를 나타냅니다. 우선순위가 낮은 레이블은 렌더링되지 않습니다.<br/> 기본값은 1000입니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | 이 인스턴스를 복제합니다. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

새로운 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 클래스 인스턴스를 초기화합니다.

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

새로운 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| label_attribute | string | 레이블의 소스로 사용할 속성 이름입니다. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

새로운 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | 복사할 데이터를 가져올 다른 [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/)입니다. |

### Method: clone() {#clone__1}


```
 clone() 
```

이 인스턴스를 복제합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | 이 인스턴스의 복제본입니다. |


