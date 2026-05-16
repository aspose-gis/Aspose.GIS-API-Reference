---
title: "GeoGenerator クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | 指定された範囲内にあるランダムな項目を指定数だけ持つ新しい ILineString 列挙子を作成します。 |
| [produce_points(rect, options)](#produce_points_rect_options_2) | 指定された領域に属するポイントの配列を作成します。 |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | 指定された範囲内にあるランダムな項目を指定数だけ持つ新しい IPolygon 列挙子を作成します。 |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | 指定された範囲内にある星の配列を作成します。 |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

指定された範囲内にあるランダムな項目を指定数だけ持つ新しい ILineString 列挙子を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 指定領域（<see cref="T:Aspose.Gis.Extent">Extent</see> を参照） |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | ライン作成オプション（<see cref="T:Aspose.Gis.GeoTools.LineGeneratorOptions">LineGeneratorOptions</see> を参照） |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | ラインの配列（<see cref="T:Aspose.Gis.Geometries.ILineString">ILineString</see> の列挙を参照） |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

指定された領域に属するポイントの配列を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 指定領域（<see cref="T:Aspose.Gis.Extent">Extent</see> を参照）。 |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | ポイント作成オプション（<see cref="T:Aspose.Gis.GeoTools.PointGeneratorOptions">PointGeneratorOptions</see> を参照）。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | ポイントの配列（<see cref="T:Aspose.Gis.Geometries.IGeometry">IGeometry</see> の列挙を参照）。 |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

指定された範囲内にあるランダムな項目を指定数だけ持つ新しい IPolygon 列挙子を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 指定領域（<see cref="T:Aspose.Gis.Extent">Extent</see> を参照） |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | ポリゴン作成オプション（<see cref="T:Aspose.Gis.GeoTools.PolygonGeneratorOptions">PolygonGeneratorOptions</see> を参照） |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | ポリゴンの配列（<see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see> の列挙を参照） |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

指定された範囲内にある星の配列を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 指定領域（<see cref="T:Aspose.Gis.Extent">Extent</see> を参照） |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | ポリゴン作成オプション（<see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see> を参照） |

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | 星の配列（<see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see> の列挙を参照） |


