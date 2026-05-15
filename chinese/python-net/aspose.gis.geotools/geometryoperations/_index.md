---
title: "GeometryOperations 类"
type: docs
weight: 40
url: /zh/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | 为多边形构建中心线图 |
| [build_centerline(sites)](#build_centerline_sites_2) | 为点集合（站点）构建中心线图 |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | 在需要时闭合环中的几何线段。 |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | 通过在每个线段的中间添加新点来创建中点。 |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | 删除彼此过于接近的点。 |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | 从图层中提取几何集合 |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | 获取中心线长度 |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | 获取中心线长度 |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | 为点集合（站点）构建 “Voronoi” 图 |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | 按类型将几何集合排序为四个集合（点、线、面和其他类型） |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | 删除位于同一线段上的点。 |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

为多边形构建中心线图

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | 中心线图的多边形 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | 中心线边缘集合 |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

为点集合（站点）构建中心线图

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 站点 | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | 点集合（站点） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | 中心线边缘集合 |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

在需要时闭合环中的几何线段。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 用于闭合的几何体。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 闭合后的几何体。 |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

通过在每个线段的中间添加新点来创建中点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 用于处理的几何。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 处理后的几何。 |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

删除彼此过于接近的点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 用于删除最近点的几何。 |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | 删除最近点的选项。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 删除最近点后的几何。 |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

从图层中提取几何集合

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 输入图层 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 该集合包含输入图层的所有几何。 |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

获取中心线长度

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | 中心线图的多边形 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 中心线边的长度 |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

获取中心线长度

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 站点 | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | 点集合（站点） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 中心线边的长度 |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

为点集合（站点）构建 “Voronoi” 图

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 站点 | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | 点集合（站点） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Voronoi 图的边集合 |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

按类型将几何集合排序为四个集合（点、线、面和其他类型）

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 用于排序的几何集合 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 该集合包含四个集合（点、线、多边形和其他类型） |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

删除位于同一线段上的点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 用于删除多余点的几何 |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | 删除多余点的选项 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 删除多余点后的几何 |


