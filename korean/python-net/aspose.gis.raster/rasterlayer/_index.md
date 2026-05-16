---
title: "RasterLayer 클래스"
type: docs
weight: 70
url: /ko/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| band_count | int | r | 래스터 레이어의 밴드 수를 가져옵니다. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | 래스터 경계를 가져옵니다. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | 래스터의 셀 또는 픽셀 크기를 가져옵니다. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | 이 레이어를 인스턴스화한 [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/)를 가져옵니다. |
| 높이 | int | r | 래스터의 높이를 픽셀 단위로 가져옵니다. 또한 행 수라고도 합니다. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | 래스터의 배경 또는 '데이터 없음'을 나타내는 값을 가져옵니다. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | 래스터의 공간 참조 시스템을 가져옵니다.<br/>            알 수 없는 경우 <see langword="null" />일 수 있습니다. |
| upper_left_x | double | r | 래스터 왼쪽 위 모서리의 x 좌표를 가져옵니다. |
| upper_left_y | double | r | 래스터 왼쪽 위 모서리의 y 좌표를 가져옵니다. |
| width | int | r | 래스터의 너비를 픽셀 단위로 가져옵니다. 또한 열 수라고도 합니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | 형태 폼(및 밴드 마스크)을 사용하여 래스터 레이어를 자릅니다. |
| [crop(masks)](#crop_masks_2) | 밴드 마스크를 사용하여 래스터 레이어를 자릅니다). |
| [get_band(index)](#get_band_index_3) | 지정된 인덱스로 밴드를 가져옵니다. |
| [get_extent()](#get_extent__4) | 이 레이어의 공간 범위를 계산합니다. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | 지정된 열과 행을 공간 좌표로 변환합니다. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | 카운트, 합계, 평균, 최소값, 최대값으로 구성된 요약 통계를 계산합니다. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | 지정된 셀의 값을 읽습니다. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | 지정된 블록의 값을 1차원 배열로 읽습니다. |
| [warp(options)](#warp_options_9) | 래스터 레이어를 다른 레이어로 워프합니다. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

형태 폼(및 밴드 마스크)을 사용하여 래스터 레이어를 자릅니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 기하학은 형태 폼을 나타냅니다. |
| 마스크 | double | 크롭 레이어용 마스크 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 잘린 래스터 레이어입니다. 교차점이 없으면 <see langword=\"null\" />을 반환합니다. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

밴드 마스크를 사용하여 래스터 레이어를 자릅니다).

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 마스크 | double | 크롭 레이어용 마스크 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 잘린 래스터 레이어입니다. 교차점이 없으면 <see langword=\"null\" />을 반환합니다. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

지정된 인덱스로 밴드를 가져옵니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| index | int | 밴드 번호는 0부터 시작하며, 지정되지 않으면 밴드는 0으로 간주됩니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | 래스터 밴드에 대한 기본 메타 데이터를 반환합니다. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

이 레이어의 공간 범위를 계산합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 이 레이어의 공간 범위. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

지정된 열과 행을 공간 좌표로 변환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| cell_x | int | 열( x좌표) 값입니다. 번호는 0부터 시작합니다. |
| cell_y | int | 행( y좌표) 값입니다. 번호는 0부터 시작합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 열과 행을 지정하면 왼쪽 위 모서리의 x좌표를 반환합니다. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

카운트, 합계, 평균, 최소값, 최대값으로 구성된 요약 통계를 계산합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| band_index | int | 밴드의 인덱스입니다. 번호는 0부터 시작합니다. |
| exclude_nodata_value | bool | 'nodata' 값을 제외하도록 허용합니다. 'excludeNodataValue'가 false로 설정되면 모든 픽셀이 고려됩니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | 요약 통계. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

지정된 셀의 값을 읽습니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| cell_x | int | 열( x좌표) 값입니다. 번호는 0부터 시작합니다. |
| cell_y | int | 행( y좌표) 값입니다. 번호는 0부터 시작합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | 래스터 값. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

지정된 블록의 값을 1차원 배열로 읽습니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | 덤프가 읽히는 래스터 셀 블록. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | 값들의 덤프. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

래스터 레이어를 다른 레이어로 워프합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | 재투영 절차에 대한 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 워프 래스터 레이어. |


