---
title: "Feature 클래스"
type: docs
weight: 830
url: /ko/python-net/aspose.gis/feature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | 피처의 기하학을 가져오거나 설정합니다.<br/>            <see langword="null" />일 수 없으며, 누락된 기하학을 나타내려면 [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/)를 사용하십시오. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | 다른 피처에서 속성 값을 복사합니다. |
| [get_value(attribute_name)](#get_value_attribute_name_2) | 속성의 값을 가져옵니다. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_3) | 속성의 값을 가져오거나, 값이 설정되지 않았거나 <c>null</c>인 경우 [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/)를 반환합니다. |
| [get_values(values, default_value)](#get_values_values_default_value_4) | 모든 속성의 값을 배열로 반환합니다. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_5) | 모든 속성의 값을 배열로 반환합니다. |
| [get_values_dump(default_value)](#get_values_dump_default_value_6) | 모든 속성의 값을 배열로 반환합니다.<br/>            추가 메모리 할당을 피하기 위해 Aspose.Gis.Feature.GetValues(int,System.Object) 메서드 사용을 고려하십시오. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_7) | 값 목록을 가져옵니다. 비제네릭 유사체인 List T GetValuesList |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_8) | 지정된 속성이 명시적으로 <c>null</c> 값으로 설정되었는지 확인합니다. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_9) | 이 기능에서 속성 값이 설정되어 있는지 확인합니다. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_10) | 값을 설정합니다. 비제네릭 유사체인 void SetValue (string attributeName, T value) |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_11) | 속성 값을 <c>null</c> 로 설정합니다. |
| [set_values(values)](#set_values_values_12) | 모든 속성에 대한 새 값을 설정합니다.<br/> 또한 한 번에 값을 설정하기 위해 [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) 메서드 사용을 고려하십시오. |
| [unset_value(attribute_name)](#unset_value_attribute_name_13) | 이 기능에서 속성 값을 제거합니다. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

다른 피처에서 속성 값을 복사합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | 값을 복사할 기능입니다. |

### Method: get_value(attribute_name) {#get_value_attribute_name_2}


```
 get_value(attribute_name) 
```

속성의 값을 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 속성의 이름. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| object | 속성의 값. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_3}


```
 get_value_or_default(attribute_name, default_value) 
```

속성의 값을 가져오거나, 값이 설정되지 않았거나 <c>null</c>인 경우 [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/)를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 속성의 이름. |
| default_value | object | 속성 값이 없을 경우 반환할 값입니다. 기본값은 <see langword=\"null\" />입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| object | 속성의 값. |


### Method: get_values(values, default_value) {#get_values_values_default_value_4}


```
 get_values(values, default_value) 
```

모든 속성의 값을 배열로 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| values | object |  |
| default_value | object | 속성 값이 없거나 설정되지 않은 경우 반환할 값입니다. 기본값은 <see langword=\"null\" />입니다.<br/> 'unset'와 '<see langword=\"null\" />' 값을 구분하기 위해 '.Value' 사용을 고려하십시오. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| int | 복사된 속성 수입니다. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_5}


```
 get_values(values_count, default_value) 
```

모든 속성의 값을 배열로 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| values_count | int | 값 개수입니다. |
| default_value | object | 속성 값이 없거나 설정되지 않은 경우 반환할 값입니다. 기본값은 <see langword=\"null\" />입니다.<br/> 'unset'와 '<see langword=\"null\" />' 값을 구분하기 위해 '.Value' 사용을 고려하십시오. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| object | 복사된 속성 수입니다. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_6}


```
 get_values_dump(default_value) 
```

모든 속성의 값을 배열로 반환합니다.<br/>            추가 메모리 할당을 피하기 위해 Aspose.Gis.Feature.GetValues(int,System.Object) 메서드 사용을 고려하십시오.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| default_value | object | 속성 값이 없거나 설정되지 않은 경우 반환할 값입니다. 기본값은 <see langword=\"null\" />입니다.<br/> 'unset'와 '<see langword=\"null\" />' 값을 구분하기 위해 '.Value' 사용을 고려하십시오. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| object | 속성 값을 복사할 새 배열입니다. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_7}


```
 get_values_list(attribute_name, separator, count) 
```

값 목록을 가져옵니다. 비제네릭 유사체인 List T GetValuesList

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 속성의 이름. |
| separator | string | 시퀀스의 속성 이름과 인덱스 값을 구분하는 데 사용되는 문자열입니다. |
| 카운트 | int | 반환할 값의 개수 (누락된 값은 null로 채워짐) |

**Returns**

| 형식 | 설명 |
| :- | :- |
| object | 시퀀스 인덱스 값에 따라 이름이 다른 속성들의 값 목록입니다. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_8}


```
 is_value_null(attribute_name) 
```

지정된 속성이 명시적으로 <c>null</c> 값으로 설정되었는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 속성의 이름. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" /> 속성 값이 <c>null</c>인 경우; 그렇지 않으면 <see langword=\"false\" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_9}


```
 is_value_set(attribute_name) 
```

이 기능에서 속성 값이 설정되어 있는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 속성의 이름. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" /> 지정된 속성에 대한 값이 설정된 경우; 그렇지 않으면 <see langword=\"false\" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_10}


```
 set_value(attribute_name, value) 
```

값을 설정합니다. 비제네릭 유사체인 void SetValue (string attributeName, T value)

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 속성의 이름입니다. |
| 값 | object | 속성의 값입니다. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_11}


```
 set_value_null(attribute_name) 
```

속성 값을 <c>null</c> 로 설정합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 속성의 이름입니다. |

### Method: set_values(values) {#set_values_values_12}


```
 set_values(values) 
```

모든 속성에 대한 새 값을 설정합니다.<br/> 또한 한 번에 값을 설정하기 위해 [Feature.copy_values(input_feature)](/psd/python-net/aspose.gis/feature/) 메서드 사용을 고려하십시오.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| values | object | 새 값들의 배열입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| int | 설정된 속성 값의 수. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_13}


```
 unset_value(attribute_name) 
```

이 기능에서 속성 값을 제거합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 속성의 이름. |

