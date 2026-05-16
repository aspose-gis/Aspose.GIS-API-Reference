---
title: "FeaturesSequence 클래스"
type: docs
weight: 870
url: /ko/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | 이 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)의 피처에 대한 사용자 정의 속성 컬렉션을 가져옵니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | 이 피처 시퀀스의 공간 참조 시스템을 가져옵니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_extent()](#get_extent__1) | 이 레이어의 공간 범위를 가져옵니다. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | 피처 시퀀스를 레이어에 저장합니다. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | 피처 시퀀스를 레이어에 저장합니다. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | 피처 시퀀스를 레이어에 저장합니다. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | 피처 시퀀스를 레이어에 저장합니다. |
| [split_to()](#split_to__6) | 피처를 기하학 유형별로 분할합니다. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | 제공된 값과 동일한 속성 값을 가진 피처를 선택합니다. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | 제공된 값보다 큰 속성 값을 가진 피처를 선택합니다. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | 제공된 값보다 크거나 같은 속성 값을 가진 피처를 선택합니다. |
| [where_intersects(extent)](#where_intersects_extent_10) | 범위에 따라 피처를 필터링합니다. |
| [where_intersects(geometry)](#where_intersects_geometry_11) | 제공된 지오메트리를 기준으로 피처를 필터링합니다. |
| [where_intersects(sequence)](#where_intersects_sequence_12) | 다른 피처 시퀀스의 모든 지오메트리의 합집합을 기준으로 피처를 필터링합니다. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | 속성 값이 제공된 값과 같지 않은 피처를 선택합니다. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | 속성이 null이 아닌 피처를 선택합니다. |
| [where_null(attribute_name)](#where_null_attribute_name_15) | 속성이 null인 피처를 선택합니다. |
| [where_set(attribute_name)](#where_set_attribute_name_16) | 속성이 설정된 피처를 선택합니다. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | 속성 값이 제공된 값보다 작은 피처를 선택합니다. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | 속성 값이 제공된 값보다 작거나 같은 피처를 선택합니다. |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | 지정된 속성이 설정되지 않은 피처를 선택합니다. |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

이 레이어의 공간 범위를 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 이 레이어의 공간 범위. |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

피처 시퀀스를 레이어에 저장합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| destination_path | string | 출력 레이어 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 출력 레이어의 포맷 드라이버. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

피처 시퀀스를 레이어에 저장합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 출력 레이어 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 출력 레이어의 포맷 드라이버. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

피처 시퀀스를 레이어에 저장합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| destination_path | string | 출력 레이어 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 출력 레이어의 포맷 드라이버. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | 저장 절차 옵션. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

피처 시퀀스를 레이어에 저장합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 출력 레이어 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 출력 레이어의 포맷 드라이버. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | 저장 절차 옵션. |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

피처를 기하학 유형별로 분할합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | 동일한 기하 유형을 가진 레이어. |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

제공된 값과 동일한 속성 값을 가진 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |
| 값 | object | 비교할 값. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 속성 값이 제공된 값과 같은 피처. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

제공된 값보다 큰 속성 값을 가진 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |
| 값 | object | 비교할 값. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 속성 값이 제공된 값보다 큰 피처. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

제공된 값보다 크거나 같은 속성 값을 가진 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |
| 값 | object | 비교할 값. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 속성 값이 제공된 값보다 크거나 같은 피처. |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

범위에 따라 피처를 필터링합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 필터 범위. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 제공된 기하학과 교차하는 피처. |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

제공된 지오메트리를 기준으로 피처를 필터링합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 필터 기하학. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 제공된 기하학과 교차하는 피처. |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

다른 피처 시퀀스의 모든 지오메트리의 합집합을 기준으로 피처를 필터링합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 다른 피처 시퀀스. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 다른 피처 시퀀스의 모든 기하학의 합집합과 교차하는 피처. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

속성 값이 제공된 값과 같지 않은 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |
| 값 | object | 비교할 값. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 제공된 값과 같지 않은 속성 값을 가진 피처. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

속성이 null이 아닌 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | null과 같지 않은 속성 값을 가진 피처. |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

속성이 null인 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | null과 같은 속성 값을 가진 피처. |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

속성이 설정된 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 설정된 속성 값을 가진 피처. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

속성 값이 제공된 값보다 작은 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |
| 값 | object | 비교할 값. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 제공된 값보다 작은 속성 값을 가진 피처. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

속성 값이 제공된 값보다 작거나 같은 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |
| 값 | object | 비교할 값. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 제공된 값보다 작거나 같은 속성 값을 가진 피처. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

지정된 속성이 설정되지 않은 피처를 선택합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| attribute_name | string | 필터링할 속성. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 설정되지 않은 속성 값을 가진 피처. |


