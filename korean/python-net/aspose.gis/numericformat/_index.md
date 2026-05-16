---
title: "NumericFormat 클래스"
type: docs
weight: 2870
url: /ko/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | 숫자를 문자열로 변환하고, 해당 문자열이 동일한 숫자 값으로 다시 파싱될 수 있도록 보장하려고 시도합니다.<br/>             |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | 과학적 표기법 없이 숫자를 고정 소수점 텍스트로 변환합니다. |
| [general(precision)](#general_precision_2) | 숫자를 고정 소수점 또는 과학적 표기법 중 더 간결한 형태로 변환합니다,<br/>            숫자의 유형 및 정밀도 지정자가 있는지에 따라 결정됩니다. 사용을 권장합니다. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

과학적 표기법 없이 숫자를 고정 소수점 텍스트로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| significant_digits | int | 유효 숫자의 개수. 최대 사용 가능한 정밀도는 "308"입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | 반올림 정밀도 지정자. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

숫자를 고정 소수점 또는 과학적 표기법 중 더 간결한 형태로 변환합니다,<br/>            숫자의 유형 및 정밀도 지정자가 있는지에 따라 결정됩니다. 사용을 권장합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| precision | int | 정밀도는 결과 문자열에 나타날 수 있는 최대 유효 숫자 개수를 정의합니다.<br/>            정밀도가 0이면 값 "15"가 사용됩니다. 최대 사용 가능한 정밀도는 "17"입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | 일반 형식 지정자. |


