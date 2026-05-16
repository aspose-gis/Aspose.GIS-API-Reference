---
title: "GeometryOperations クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | ポリゴンの中心線図を作成 |
| [build_centerline(sites)](#build_centerline_sites_2) | ポイント（サイト）コレクションの中心線図を作成 |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | 必要に応じてリング内の幾何セグメントを閉じます。 |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | 各セグメントの中間に新しい点を追加して中点を作成します。 |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | 互いに近すぎる点を削除します。 |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | レイヤーからジオメトリコレクションを抽出 |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | 中心線の長さを取得 |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | 中心線の長さを取得 |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | ポイント（サイト）コレクションの「Voronoi」図を作成 |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | ジオメトリコレクションをタイプ別に並べ替えて、4つのコレクション（ポイント、ライン、ポリゴン、その他のタイプ）に分割します。 |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | 同じセグメント上にある点を削除します。 |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

ポリゴンの中心線図を作成

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | 中心線図のポリゴン |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | 中心線エッジのコレクション |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

ポイント（サイト）コレクションの中心線図を作成

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| サイト | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | ポイント（サイト）のコレクション |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | 中心線エッジのコレクション |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

必要に応じてリング内の幾何セグメントを閉じます。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 閉じるためのジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 閉鎖後のジオメトリです。 |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

各セグメントの中間に新しい点を追加して中点を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 処理用ジオメトリ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 処理後のジオメトリ。 |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

互いに近すぎる点を削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 最近傍点を削除するためのジオメトリ。 |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | 最近傍点を削除するオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 最近傍点を削除した後のジオメトリ。 |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

レイヤーからジオメトリコレクションを抽出

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | 入力レイヤー |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | このコレクションは入力レイヤーのすべてのジオメトリを含みます。 |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

中心線の長さを取得

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | 中心線図のポリゴン |

**Returns**

| 型 | 説明 |
| :- | :- |
| double | 中心線エッジの長さ |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

中心線の長さを取得

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| サイト | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | ポイント（サイト）のコレクション |

**Returns**

| 型 | 説明 |
| :- | :- |
| double | 中心線エッジの長さ |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

ポイント（サイト）コレクションの「Voronoi」図を作成

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| サイト | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | ポイント（サイト）のコレクション |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | ボロノイ図のエッジのコレクション |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

ジオメトリコレクションをタイプ別に並べ替えて、4つのコレクション（ポイント、ライン、ポリゴン、その他のタイプ）に分割します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 順序のためのジオメトリコレクション |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | このコレクションは4つのコレクション（ポイント、ライン、ポリゴン、その他のタイプ）を含みます。 |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

同じセグメント上にある点を削除します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 余分な点を削除するためのジオメトリ。 |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | 余分な点を削除するオプション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | 余分な点を削除した後のジオメトリ。 |


