---
title: "KmlDriver 클래스"
type: docs
weight: 50
url: /ko/python-net/aspose.gis.formats.kml/kmldriver/
---

**Summary:** A driver for the KML format

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | 이 드라이버가 데이터 세트를 생성할 수 있는지 여부를 나타내는 값을 가져옵니다. |
| can_create_layers | bool | r | 이 드라이버가 벡터 레이어를 생성할 수 있는지 여부를 나타내는 값을 가져옵니다. |
| can_open_datasets | bool | r | 이 드라이버가 데이터 세트를 열 수 있는지 여부를 나타내는 값을 가져옵니다. |
| can_open_layers | bool | r | 이 드라이버가 벡터 레이어를 열 수 있는지 여부를 나타내는 값을 가져옵니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | 데이터 세트를 생성합니다. |
| [create_dataset(path)](#create_dataset_path_2) | 데이터 세트를 생성합니다. |
| [create_dataset(path, options)](#create_dataset_path_options_3) | 데이터 세트를 생성합니다. |
| [create_dataset(path, options)](#create_dataset_path_options_4) | 데이터 세트를 생성합니다. |
| [create_layer(path)](#create_layer_path_5) | 레이어를 생성하고 추가를 위해 엽니다. |
| [create_layer(path)](#create_layer_path_6) | 레이어를 생성하고 추가를 위해 엽니다. |
| [create_layer(path, options)](#create_layer_path_options_7) | 새 레이어를 만들고 새 피처를 추가하기 위해 엽니다. |
| [create_layer(path, options)](#create_layer_path_options_8) | 새 레이어를 만들고 새 피처를 추가하기 위해 엽니다. |
| [create_layer(path, options)](#create_layer_path_options_9) | 새 레이어를 만들고 새 피처를 추가하기 위해 엽니다. |
| [create_layer(path, options)](#create_layer_path_options_10) | 새 레이어를 만들고 새 피처를 추가하기 위해 엽니다. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | 새 레이어를 만들고 새 피처를 추가하기 위해 엽니다. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | 새 레이어를 만들고 새 피처를 추가하기 위해 엽니다. |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | 새 레이어를 만들고 새 피처를 추가하기 위해 엽니다. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | 레이어를 생성하고 추가를 위해 엽니다. |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | 레이어를 생성하고 추가를 위해 엽니다. |
| [edit_layer(path, options)](#edit_layer_path_options_16) | 편집을 위해 레이어를 엽니다. |
| [edit_layer(path, options)](#edit_layer_path_options_17) | 편집을 위해 레이어를 엽니다. |
| [open_as_kml_layer(path, options)](#open_as_kml_layer_path_options_18) | Kml 레이어를 읽기 위해 엽니다. |
| [open_dataset(path)](#open_dataset_path_19) | 데이터세트를 엽니다. |
| [open_dataset(path)](#open_dataset_path_20) | 데이터세트를 엽니다. |
| [open_dataset(path, options)](#open_dataset_path_options_21) | 데이터세트를 엽니다. |
| [open_dataset(path, options)](#open_dataset_path_options_22) | 데이터세트를 엽니다. |
| [open_layer(path)](#open_layer_path_23) | 읽기를 위해 레이어를 엽니다. |
| [open_layer(path)](#open_layer_path_24) | 읽기를 위해 레이어를 엽니다. |
| [open_layer(path, options)](#open_layer_path_options_25) | 읽기를 위해 레이어를 엽니다. |
| [open_layer(path, options)](#open_layer_path_options_26) | 읽기를 위해 레이어를 엽니다. |
| [open_layer(path, options)](#open_layer_path_options_27) | 읽기를 위해 레이어를 엽니다. |
| [open_layer(path, options)](#open_layer_path_options_28) | 읽기를 위해 레이어를 엽니다. |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_29) | 지정된 공간 참조 시스템이 드라이버에서 지원되는지 여부를 결정합니다. |


### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

데이터 세트를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 데이터세트 경로. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

데이터 세트를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 데이터세트 경로. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

데이터 세트를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 데이터세트 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

데이터 세트를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 데이터세트 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

새 레이어를 만들고 새 피처를 추가하기 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

새 레이어를 만들고 새 피처를 추가하기 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

새 레이어를 만들고 새 피처를 추가하기 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

새 레이어를 만들고 새 피처를 추가하기 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

새 레이어를 만들고 새 피처를 추가하기 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

새 레이어를 만들고 새 피처를 추가하기 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | 드라이버별 옵션. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

새 레이어를 만들고 새 피처를 추가하기 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


```
 create_layer(path, spatial_reference_system) 
```

레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


```
 create_layer(path, spatial_reference_system) 
```

레이어를 생성하고 추가를 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


```
 edit_layer(path, options) 
```

편집을 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


```
 edit_layer(path, options) 
```

편집을 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_as_kml_layer(path, options) {#open_as_kml_layer_path_options_18}


```
 open_as_kml_layer(path, options) 
```

Kml 레이어를 읽기 위해 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [KmlLayer](/psd/python-net/aspose.gis.formats.kml/kmllayer) | 특정 필드가 있는 KmlLayer |


### Method: open_dataset(path) {#open_dataset_path_19}


```
 open_dataset(path) 
```

데이터세트를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 데이터세트 경로. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path) {#open_dataset_path_20}


```
 open_dataset(path) 
```

데이터세트를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 데이터세트 경로. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


```
 open_dataset(path, options) 
```

데이터세트를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 데이터세트 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_dataset(path, options) {#open_dataset_path_options_22}


```
 open_dataset(path, options) 
```

데이터세트를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 데이터세트 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | 다음의 인스턴스: [Dataset](/psd/python-net/aspose.gis/dataset/). |


### Method: open_layer(path) {#open_layer_path_23}


```
 open_layer(path) 
```

읽기를 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path) {#open_layer_path_24}


```
 open_layer(path) 
```

읽기를 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

읽기를 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

읽기를 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

읽기를 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 파일 경로. |
| options | [KmlOptions](/psd/python-net/aspose.gis.formats.kml/kmloptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: open_layer(path, options) {#open_layer_path_options_28}


```
 open_layer(path, options) 
```

읽기를 위해 레이어를 엽니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 파일 경로. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | 드라이버별 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 다음의 인스턴스: [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_29}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

지정된 공간 참조 시스템이 드라이버에서 지원되는지 여부를 결정합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | 공간 참조 시스템. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 지정된 공간 참조 시스템이 드라이버에서 지원되는지 여부를 나타내는 부울 값. |


