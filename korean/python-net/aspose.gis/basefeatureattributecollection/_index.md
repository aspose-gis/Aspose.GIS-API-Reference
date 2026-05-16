---
title: "BaseFeatureAttributeCollection 클래스"
type: docs
weight: 90
url: /ko/python-net/aspose.gis/basefeatureattributecollection/
---

**Summary:** A [FeatureAttributeCollection](/psd/python-net/aspose.gis/featureattributecollection/) defines what attributes are available for a [Feature](/psd/python-net/aspose.gis/feature/).

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.BaseFeatureAttributeCollection

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r | 특정 [Feature](/psd/python-net/aspose.gis/feature/)의 속성 수를 가져옵니다. |
| is_locked | bool | r | 이 속성 컬렉션이 잠겨 있는지 여부를 나타내는 값을 가져옵니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(attribute)](#add_attribute_1) | 컬렉션에 속성을 추가합니다. |
| [contains(name)](#contains_name_2) | 속성 컬렉션에 지정된 이름의 속성이 포함되어 있는지 확인합니다. |
| [index_of(name)](#index_of_name_3) | 속성을 검색하고 해당 속성의 0부터 시작하는 인덱스를 반환합니다. |
| lock() | 추가 수정을 방지하기 위해 이 속성 컬렉션을 잠급니다. |
| [remove(index)](#remove_index_4) | 컬렉션에서 속성을 제거합니다. |
| [remove(name)](#remove_name_5) | 컬렉션에서 속성을 제거합니다. |


### Method: add(attribute) {#add_attribute_1}


```
 add(attribute) 
```

컬렉션에 속성을 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute | [FeatureAttribute](/psd/python-net/aspose.gis/featureattribute) | 추가할 속성. |

### Method: contains(name) {#contains_name_2}


```
 contains(name) 
```

속성 컬렉션에 지정된 이름의 속성이 포함되어 있는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 속성의 이름. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword="true" /> 지정된 이름의 속성이 속성 컬렉션에 포함되어 있으면; 그렇지 않으면 <see langword="false" />. |


### Method: index_of(name) {#index_of_name_3}


```
 index_of(name) 
```

속성을 검색하고 해당 속성의 0부터 시작하는 인덱스를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 속성의 이름. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| int | 컬렉션 내에서 속성을 찾은 경우 해당 속성의 0부터 시작하는 인덱스; 찾지 못한 경우 –1. |


### Method: remove(index) {#remove_index_4}


```
 remove(index) 
```

컬렉션에서 속성을 제거합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | int | 속성의 인덱스. |

### Method: remove(name) {#remove_name_5}


```
 remove(name) 
```

컬렉션에서 속성을 제거합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 속성의 이름. |

