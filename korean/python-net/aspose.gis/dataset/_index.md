---
title: "Dataset 클래스"
type: docs
weight: 590
url: /ko/python-net/aspose.gis/dataset/
---

**Summary:** A dataset is the collection of [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) instances.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Dataset

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | 이 데이터셋이 벡터 레이어를 생성할 수 있는지 여부를 나타내는 값을 가져옵니다. |
| can_remove_layers | bool | r | 이 데이터셋이 벡터 레이어를 제거할 수 있는지 여부를 나타내는 값을 가져옵니다. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | 이 데이터셋을 인스턴스화한 [Dataset.driver](/psd/python-net/aspose.gis/dataset/)를 가져옵니다. |
| layers_count | int | r | 이 데이터셋의 레이어 수를 가져옵니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | 데이터 세트를 생성합니다. |
| [create(path, driver)](#create_path_driver_2) | 데이터 세트를 생성합니다. |
| [create(path, driver, options)](#create_path_driver_options_3) | 데이터 세트를 생성합니다. |
| [create(path, driver, options)](#create_path_driver_options_4) | 데이터 세트를 생성합니다. |
| [create_layer()](#create_layer__5) | 새 벡터 레이어를 생성하고 추가를 위해 엽니다. |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | 지정된 이름으로 새 벡터 레이어를 생성하고 추가를 위해 엽니다. |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | 지정된 이름으로 새 벡터 레이어를 생성하고 추가를 위해 엽니다. |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | 새 벡터 레이어를 생성하고 추가를 위해 엽니다. |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | 새 벡터 레이어를 생성하고 추가를 위해 엽니다. |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | 지정된 이름의 레이어를 편집을 위해 엽니다. |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | 지정된 이름의 레이어를 편집을 위해 엽니다. |
| [get_layer_name(index)](#get_layer_name_index_12) | 지정된 인덱스에 있는 레이어의 이름을 가져옵니다. |
| [has_layer_with_name(name)](#has_layer_with_name_name_13) | 현재 데이터셋에 특정 이름의 레이어가 있는지 확인합니다. |
| [open(path, driver)](#open_path_driver_14) | 데이터세트를 엽니다. |
| [open(path, driver)](#open_path_driver_15) | 데이터세트를 엽니다. |
| [open(path, driver, options)](#open_path_driver_options_16) | 데이터세트를 엽니다. |
| [open(path, driver, options)](#open_path_driver_options_17) | 데이터세트를 엽니다. |
| [open_layer(name, options)](#open_layer_name_options_18) | 지정된 이름의 레이어를 읽기를 위해 엽니다. |
| [open_layer_at(index, options)](#open_layer_at_index_options_19) | 지정된 인덱스에 있는 레이어를 읽기를 위해 엽니다. |
| [remove_layer(name)](#remove_layer_name_20) | 지정된 이름의 벡터 레이어를 제거합니다. |
| [remove_layer_at(index)](#remove_layer_at_index_21) | 지정된 인덱스에 있는 벡터 레이어를 제거합니다. |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_22) | 데이터셋에서 레이어 이름을 바꿉니다. |


### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

데이터 세트를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 데이터세트 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

데이터 세트를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 데이터세트 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

데이터 세트를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 데이터세트 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

데이터 세트를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 데이터세트 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

새 벡터 레이어를 생성하고 추가를 위해 엽니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 쓰기용으로 열린 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)입니다. |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

지정된 이름으로 새 벡터 레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 레이어의 이름입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 열기 옵션입니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 새 레이어의 공간 참조 시스템입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 쓰기용으로 열린 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)입니다. |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

지정된 이름으로 새 벡터 레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 레이어의 이름입니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 새 레이어의 공간 참조 시스템입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 쓰기용으로 열린 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)입니다. |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

새 벡터 레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 열기 옵션입니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 새 레이어의 공간 참조 시스템입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 쓰기용으로 열린 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)입니다. |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

새 벡터 레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 새 레이어의 공간 참조 시스템입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 쓰기용으로 열린 [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)입니다. |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

지정된 이름의 레이어를 편집을 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 편집할 레이어의 이름입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 열기 옵션입니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 새 기하학에 대한 공간 참조 시스템입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 편집을 위해 열린 레이어입니다. |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

지정된 이름의 레이어를 편집을 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | int | 편집할 레이어의 인덱스입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 열기 옵션입니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 새 기하학에 대한 공간 참조 시스템입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 편집을 위해 열린 레이어입니다. |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

지정된 인덱스에 있는 레이어의 이름을 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | int | 레이어의 인덱스입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 레이어의 이름입니다. |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_13}


```
 has_layer_with_name(name) 
```

현재 데이터셋에 특정 이름의 레이어가 있는지 확인합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 레이어의 이름 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | <see langword=\"true\" />, 데이터셋에 이 이름의 레이어가 있으면; 그렇지 않으면 <see langword=\"false\" /> |


### Method: open(path, driver)  [static] {#open_path_driver_14}


```
 open(path, driver) 
```

데이터세트를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 데이터세트 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

데이터세트를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 데이터세트 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_16}


```
 open(path, driver, options) 
```

데이터세트를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 데이터세트 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

데이터세트를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 데이터세트 경로. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | 사용할 드라이버입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(name, options) {#open_layer_name_options_18}


```
 open_layer(name, options) 
```

지정된 이름의 레이어를 읽기를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 열 레이어의 이름입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 열기 옵션입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 읽기를 위해 열린 레이어입니다. |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_19}


```
 open_layer_at(index, options) 
```

지정된 인덱스에 있는 레이어를 읽기를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | int | 열 레이어의 인덱스입니다. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 열기 옵션입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 읽기를 위해 열린 레이어입니다. |


### Method: remove_layer(name) {#remove_layer_name_20}


```
 remove_layer(name) 
```

지정된 이름의 벡터 레이어를 제거합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 레이어의 이름 |

### Method: remove_layer_at(index) {#remove_layer_at_index_21}


```
 remove_layer_at(index) 
```

지정된 인덱스에 있는 벡터 레이어를 제거합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | int | 레이어 인덱스 |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_22}


```
 rename_layer(current_name, new_name) 
```

데이터셋에서 레이어 이름을 바꿉니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| current_name | string | 레이어의 현재 이름 |
| new_name | string | 레이어의 새 이름 |

