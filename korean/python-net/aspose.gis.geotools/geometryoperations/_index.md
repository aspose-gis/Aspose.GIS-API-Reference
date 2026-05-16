---
title: "GeometryOperations 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | 폴리곤에 대한 중심선 다이어그램을 구축합니다 |
| [build_centerline(sites)](#build_centerline_sites_2) | 점(사이트) 컬렉션에 대한 중심선 다이어그램을 구축합니다 |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | 필요한 경우 링의 기하학적 세그먼트를 닫습니다. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | 각 세그먼트의 중간에 새로운 점을 추가하여 중간점을 생성합니다. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | 너무 가깝게 위치한 점들을 삭제합니다. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | 레이어에서 기하학 컬렉션을 추출합니다 |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | 중심선 길이를 가져옵니다 |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | 중심선 길이를 가져옵니다 |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | 점(사이트) 컬렉션에 대한 "Voronoi" 다이어그램을 구축합니다 |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | 기하학 컬렉션을 유형별로 정렬하여 네 개의 컬렉션(점, 선, 폴리곤 및 기타 유형)으로 나눕니다 |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | 같은 세그먼트에 위치한 점들을 삭제합니다. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

폴리곤에 대한 중심선 다이어그램을 구축합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | 중심선 다이어그램용 폴리곤 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | 중심선 엣지 컬렉션 |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

점(사이트) 컬렉션에 대한 중심선 다이어그램을 구축합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 사이트 | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | 점(사이트) 컬렉션 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | 중심선 엣지 컬렉션 |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

필요한 경우 링의 기하학적 세그먼트를 닫습니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 닫기를 위한 기하학. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 닫은 후의 기하학. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

각 세그먼트의 중간에 새로운 점을 추가하여 중간점을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 처리를 위한 기하학. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 처리 후의 기하학. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

너무 가깝게 위치한 점들을 삭제합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 가장 가까운 점들을 삭제하기 위한 기하학. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | 가장 가까운 점들을 삭제하기 위한 옵션. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 가장 가까운 점을 삭제한 후의 기하학. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

레이어에서 기하학 컬렉션을 추출합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 입력 레이어 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 컬렉션에는 입력 레이어의 모든 기하학이 포함됩니다. |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

중심선 길이를 가져옵니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | 중심선 다이어그램용 폴리곤 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| double | 중심선 가장자리 길이 |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

중심선 길이를 가져옵니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 사이트 | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | 점(사이트) 컬렉션 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| double | 중심선 가장자리 길이 |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

점(사이트) 컬렉션에 대한 "Voronoi" 다이어그램을 구축합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 사이트 | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | 점(사이트) 컬렉션 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | 보로노이 다이어그램의 엣지 컬렉션 |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

기하학 컬렉션을 유형별로 정렬하여 네 개의 컬렉션(점, 선, 폴리곤 및 기타 유형)으로 나눕니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 정렬을 위한 기하학 컬렉션 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 컬렉션에는 네 개의 컬렉션(점, 선, 폴리곤 및 기타 유형)이 포함됩니다 |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

같은 세그먼트에 위치한 점들을 삭제합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 추가 점을 삭제하기 위한 기하학 |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | 추가 점을 삭제하기 위한 옵션 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 추가 점을 삭제한 후의 기하학 |


