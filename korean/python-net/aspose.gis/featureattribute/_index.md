---
title: "FeatureAttribute 클래스"
type: docs
weight: 840
url: /ko/python-net/aspose.gis/featureattribute/
---

**Summary:** An attribute of a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeatureAttribute

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FeatureAttribute(name, data_type)](#FeatureAttribute_name_data_type_1) | 새로운 [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) 클래스 인스턴스를 초기화합니다. |
| [FeatureAttribute(name, data_type, can_be_null)](#FeatureAttribute_name_data_type_can_be_null_2) | 새로운 [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_be_null | bool | r/w | 이 인스턴스가 null일 수 있는지 여부를 나타내는 값을 가져옵니다. |
| can_be_unset | bool | r/w | 이 속성의 값이 생략될 수 있는지 여부를 나타내는 값을 가져오거나 설정합니다. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | r/w | 속성의 데이터 유형을 가져옵니다. |
| default_value | object | r/w | 누락된 데이터를 나타내는 속성 값을 가져오거나 설정합니다. |
| has_custom_default_value | bool | r | 이 속성에 대한 사전 정의된 기본값이 사용자 지정 값으로 재정의되었는지 여부를 나타내는 값을 가져옵니다. |
| is_locked | bool | r | 이 속성이 잠겨 있는지 여부를 나타내는 값을 가져옵니다. |
| 이름 | string | r/w | 속성의 이름을 가져옵니다. |
| precision | Nullable<int> | r/w | 저장할 최대 소수 자리수를 가져오거나 설정합니다. |
| type_name | string | r/w | 속성의 형식 이름입니다. |
| width | Nullable<int> | r/w | 속성의 문자 표현에 허용되는 최대 너비를 가져오거나 설정합니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| lock() | 이 속성을 잠급니다. |


### Constructor: FeatureAttribute(name, data_type) {#FeatureAttribute_name_data_type_1}


```
 FeatureAttribute(name, data_type) 
```

새로운 [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 속성의 이름입니다. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 속성의 데이터 유형입니다. |

### Constructor: FeatureAttribute(name, data_type, can_be_null) {#FeatureAttribute_name_data_type_can_be_null_2}


```
 FeatureAttribute(name, data_type, can_be_null) 
```

새로운 [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 속성의 이름입니다. |
| data_type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | 속성의 데이터 유형입니다. |
| can_be_null | bool | 이 인스턴스가 null일 수 있으면 <see langword=\"true\" />; 그렇지 않으면 <see langword=\"false\" />. |

