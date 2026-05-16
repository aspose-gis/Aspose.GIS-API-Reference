---
title: "VectorLayer 클래스"
type: docs
weight: 4060
url: /ko/python-net/aspose.gis/vectorlayer/
---

**Summary:** Represents a vector layer.<br/>            A vector layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.VectorLayer

**Inheritance:** FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | 이 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)의 피처에 대한 사용자 정의 속성 컬렉션을 가져옵니다. |
| 카운트 | int | r | 이 레이어의 피처 수를 가져옵니다. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | 이 레이어를 인스턴스화한 [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/)를 가져옵니다. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | 레이어의 기하학 유형을 가져옵니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | 이 피처 시퀀스의 공간 참조 시스템을 가져옵니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(feature)](#add_feature_1) | 레이어에 새 피처를 추가합니다, [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/)가 지원되는 경우. |
| [add(feature, style)](#add_feature_style_2) | 지정된 스타일을 가진 새 피처를 레이어에 추가합니다, [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/)가 지원되는 경우. |
| [as_in_memory()](#as_in_memory__3) | InMemory 형식으로 레이어 복제본을 생성합니다. |
| [construct_feature()](#construct_feature__4) | 새 피처를 생성하지만 레이어에 추가하지는 않으며, 이 레이어의 속성 컬렉션과 일치하는 속성을 가집니다.<br/>            피처에 대한 데이터 설정이 완료되면, [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/)를 사용하여 피처를 레이어에 추가합니다. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | 레이어를 다른 형식으로 변환합니다. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | 레이어를 다른 형식으로 변환합니다. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | 레이어를 다른 형식으로 변환합니다. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | 레이어를 다른 형식으로 변환합니다. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | 다른 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)의 속성을 이 레이어에 복사합니다. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | 다른 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)의 속성을 이 레이어에 복사합니다. |
| [create(path, driver)](#create_path_driver_11) | 레이어를 생성하고 새 피처를 추가할 수 있도록 엽니다. |
| [create(path, driver)](#create_path_driver_12) | 레이어를 생성하고 새 피처를 추가할 수 있도록 엽니다. |
| [create(path, driver, options)](#create_path_driver_options_13) | 레이어를 생성하고 새 피처를 추가할 수 있도록 엽니다. |
| [create(path, driver, options)](#create_path_driver_options_14) | 레이어를 생성하고 새 피처를 추가할 수 있도록 엽니다. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | 레이어를 생성하고 추가를 위해 엽니다. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | 레이어를 생성하고 추가를 위해 엽니다. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | 레이어를 생성하고 추가를 위해 엽니다. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | 레이어를 생성하고 추가를 위해 엽니다. |
| [get_extent()](#get_extent__19) | 이 레이어의 공간 범위를 가져옵니다. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | 기하학을 사용하여 레이어를 현재 레이어와 교차시킵니다. |
| [join(layer, options)](#join_layer_options_21) | 레이어를 현재 레이어에 조인합니다. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | 기하학을 사용하여 레이어를 현재 레이어에 조인합니다. |
| [nearest_to(point)](#nearest_to_point_23) | 제공된 점에 가장 가까운 피처를 가져옵니다. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | 제공된 좌표에 가장 가까운 피처를 가져옵니다. |
| [open(path, driver)](#open_path_driver_25) | 읽기 위해 레이어를 엽니다. |
| [open(path, driver)](#open_path_driver_26) | 읽기 위해 레이어를 엽니다. |
| [open(path, driver, options)](#open_path_driver_options_27) | 읽기 위해 레이어를 엽니다. |
| [open(path, driver, options)](#open_path_driver_options_28) | 읽기 위해 레이어를 엽니다. |
| [remove_at(index)](#remove_at_index_29) | 지정된 인덱스에 있는 [Feature](/psd/python-net/aspose.gis/feature/)을 제거합니다. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | 지정된 인덱스에 있는 [Feature](/psd/python-net/aspose.gis/feature/)을 교체합니다. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | 피처 시퀀스를 레이어에 저장합니다. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | 피처 시퀀스를 레이어에 저장합니다. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | 피처 시퀀스를 레이어에 저장합니다. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | 피처 시퀀스를 레이어에 저장합니다. |
| [split_to()](#split_to__35) | 피처를 기하학 유형별로 분할합니다. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | 필터 메서드(Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) 등)에서 속성 값으로 필터링을 가속하기 위해 속성 인덱스를 로드합니다.<br/>            인덱스가 존재하지 않으면 먼저 생성합니다. <paramref name=\"forceRebuild\" />를 사용하여 인덱스 재생성을 강제합니다. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | 필터 메서드(Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) 등)에서 속성 값으로 필터링을 가속하기 위해 속성 인덱스를 로드합니다.<br/>            인덱스가 존재하지 않으면 먼저 생성합니다. <paramref name=\"forceRebuild\" />를 사용하여 인덱스 재생성을 강제합니다. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | 필터 메서드(Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) 및 Aspose.Gis.VectorLayer.NearestTo(float,float) 등)에서 속성 값으로 필터링을 가속하기 위해 공간 인덱스를 로드합니다.<br/>            인덱스가 존재하지 않으면 먼저 생성합니다. <paramref name=\"forceRebuild\" />를 사용하여 인덱스 재생성을 강제합니다. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | 필터 메서드(Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) 및 Aspose.Gis.VectorLayer.NearestTo(float,float) 등)에서 속성 값으로 필터링을 가속하기 위해 공간 인덱스를 로드합니다.<br/>            인덱스가 존재하지 않으면 먼저 생성합니다. <paramref name=\"forceRebuild\" />를 사용하여 인덱스 재생성을 강제합니다. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | 제공된 값과 동일한 속성 값을 가진 피처를 선택합니다. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | 제공된 값보다 큰 속성 값을 가진 피처를 선택합니다. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | 제공된 값보다 크거나 같은 속성 값을 가진 피처를 선택합니다. |
| [where_intersects(extent)](#where_intersects_extent_43) | 범위에 따라 피처를 필터링합니다. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | 제공된 지오메트리를 기준으로 피처를 필터링합니다. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | 다른 피처 시퀀스의 모든 지오메트리의 합집합을 기준으로 피처를 필터링합니다. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | 속성 값이 제공된 값과 같지 않은 피처를 선택합니다. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | 속성이 null이 아닌 피처를 선택합니다. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | 속성이 null인 피처를 선택합니다. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | 속성이 설정된 피처를 선택합니다. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | 속성 값이 제공된 값보다 작은 피처를 선택합니다. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | 속성 값이 제공된 값보다 작거나 같은 피처를 선택합니다. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | 지정된 속성이 설정되지 않은 피처를 선택합니다. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

레이어에 새 피처를 추가합니다, [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/)가 지원되는 경우.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | 추가할 피처. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

지정된 스타일을 가진 새 피처를 레이어에 추가합니다, [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/)가 지원되는 경우.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | 추가할 피처. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | 피처 스타일. 누락된 스타일을 나타내려면 <see langword=\"null\" />를 사용하십시오. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

InMemory 형식으로 레이어 복제본을 생성합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | InMemory 레이어. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

새 피처를 생성하지만 레이어에 추가하지는 않으며, 이 레이어의 속성 컬렉션과 일치하는 속성을 가집니다.<br/>            피처에 대한 데이터 설정이 완료되면, [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/)를 사용하여 피처를 레이어에 추가합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | 새 피처. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

레이어를 다른 형식으로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_path | string | 변환될 레이어의 경로. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 소스 레이어의 포맷 드라이버. |
| destination_path | string | 변환 결과로 생성될 레이어의 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 대상 레이어의 포맷 드라이버. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

레이어를 다른 형식으로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 변환될 레이어의 경로. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 소스 레이어의 포맷 드라이버. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 변환 결과로 생성될 레이어의 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 대상 레이어의 포맷 드라이버. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

레이어를 다른 형식으로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_path | string | 변환될 레이어의 경로. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 소스 레이어의 포맷 드라이버. |
| destination_path | string | 변환 결과로 생성될 레이어의 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 대상 레이어의 포맷 드라이버. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | 변환 절차 옵션. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

레이어를 다른 형식으로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 변환될 레이어의 경로. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 소스 레이어의 포맷 드라이버. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 변환 결과로 생성될 레이어의 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 대상 레이어의 포맷 드라이버. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | 변환 절차 옵션. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

다른 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)의 속성을 이 레이어에 복사합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 속성을 복사할 피처 시퀀스. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

다른 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)의 속성을 이 레이어에 복사합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | 속성을 복사할 피처 시퀀스. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | 속성을 하나씩 처리할 사용자 정의 [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) 인스턴스. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

레이어를 생성하고 새 피처를 추가할 수 있도록 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 쓰기 전용 레이어. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

레이어를 생성하고 새 피처를 추가할 수 있도록 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 쓰기 전용 레이어. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

레이어를 생성하고 새 피처를 추가할 수 있도록 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 쓰기 전용 레이어. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

레이어를 생성하고 새 피처를 추가할 수 있도록 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 쓰기 전용 레이어. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

이 레이어의 공간 범위를 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 이 레이어의 공간 범위. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

기하학을 사용하여 레이어를 현재 레이어와 교차시킵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 교차할 레이어. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 두 레이어를 교차한 결과 생성된 새 레이어. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

레이어를 현재 레이어에 조인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 조인할 레이어. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | 조인 매개변수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 두 레이어를 조인한 결과 생성된 새 레이어. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

기하학을 사용하여 레이어를 현재 레이어에 조인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 조인할 레이어. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | 조인 매개변수. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 두 레이어를 조인한 결과 생성된 새 레이어. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

제공된 점에 가장 가까운 피처를 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 점. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | 제공된 점에 가장 가까운 피처. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

제공된 좌표에 가장 가까운 피처를 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| x | double | 좌표의 X. |
| y | double | 좌표의 Y. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | 제공된 좌표에 가장 가까운 피처. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

읽기 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 읽기 전용 레이어. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

읽기 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 읽기 전용 레이어. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

읽기 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 읽기 전용 레이어. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

읽기 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 읽기 전용 레이어. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

지정된 인덱스에 있는 [Feature](/psd/python-net/aspose.gis/feature/)을 제거합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | int | 피처의 인덱스. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

지정된 인덱스에 있는 [Feature](/psd/python-net/aspose.gis/feature/)을 교체합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | int | 피처의 인덱스. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | 설정할 피처. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

피처 시퀀스를 레이어에 저장합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| destination_path | string | 출력 레이어 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 출력 레이어의 포맷 드라이버. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

피처 시퀀스를 레이어에 저장합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 출력 레이어 경로. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 출력 레이어의 포맷 드라이버. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


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

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


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

### Method: split_to() {#split_to__35}


```
 split_to() 
```

피처를 기하학 유형별로 분할합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | 동일한 기하 유형을 가진 레이어. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

필터 메서드(Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) 등)에서 속성 값으로 필터링을 가속하기 위해 속성 인덱스를 로드합니다.<br/>            인덱스가 존재하지 않으면 먼저 생성합니다. <paramref name=\"forceRebuild\" />를 사용하여 인덱스 재생성을 강제합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index_path | string | 인덱스 파일 경로. |
| attribute_name | string | 인덱스를 구축할 속성 이름. |
| force_rebuild | bool | 인덱스가 이미 존재하더라도 재생성할지 여부. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

필터 메서드(Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) 등)에서 속성 값으로 필터링을 가속하기 위해 속성 인덱스를 로드합니다.<br/>            인덱스가 존재하지 않으면 먼저 생성합니다. <paramref name=\"forceRebuild\" />를 사용하여 인덱스 재생성을 강제합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 인덱스 파일 경로. |
| attribute_name | string | 인덱스를 구축할 속성 이름. |
| force_rebuild | bool | 인덱스가 이미 존재하더라도 재생성할지 여부. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

필터 메서드(Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) 및 Aspose.Gis.VectorLayer.NearestTo(float,float) 등)에서 속성 값으로 필터링을 가속하기 위해 공간 인덱스를 로드합니다.<br/>            인덱스가 존재하지 않으면 먼저 생성합니다. <paramref name=\"forceRebuild\" />를 사용하여 인덱스 재생성을 강제합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index_path | string | 인덱스 파일 경로. |
| force_rebuild | bool | 인덱스가 이미 존재하더라도 재생성할지 여부. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

필터 메서드(Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) 및 Aspose.Gis.VectorLayer.NearestTo(float,float) 등)에서 속성 값으로 필터링을 가속하기 위해 공간 인덱스를 로드합니다.<br/>            인덱스가 존재하지 않으면 먼저 생성합니다. <paramref name=\"forceRebuild\" />를 사용하여 인덱스 재생성을 강제합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 인덱스 파일 경로. |
| force_rebuild | bool | 인덱스가 이미 존재하더라도 재생성할지 여부. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


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


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


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


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


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


### Method: where_intersects(extent) {#where_intersects_extent_43}


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


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


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


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


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


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


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


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


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


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


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


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


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


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


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


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


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


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


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


