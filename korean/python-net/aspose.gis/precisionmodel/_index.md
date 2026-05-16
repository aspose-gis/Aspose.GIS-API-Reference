---
title: "PrecisionModel 클래스"
type: docs
weight: 3200
url: /ko/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | 정확한 정밀도 모델을 반환합니다.<br/>            정확한 정밀도 모델에 따르면 double 값의 모든 자릿수가 유효합니다. |
| is_exact | bool | r | 이 정밀도 모델이 정확한지 여부를 나타내는 값을 가져옵니다. |
| is_rounding | bool | r | 이 정밀도 모델이 반올림인지 여부를 나타내는 값을 가져옵니다. |
| significant_digits | int | r | 반올림인 경우 정밀도 모델에서 유효한 자릿수의 개수를 가져옵니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | 반올림 정밀도 모델을 반환합니다.<br/>            반올림 정밀도 모델에 따르면 제한된 수의 자릿수만 유효합니다. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

반올림 정밀도 모델을 반환합니다.<br/>            반올림 정밀도 모델에 따르면 제한된 수의 자릿수만 유효합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| significant_digits | int | 유효 자릿수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | 반올림 정밀도 모델. |


