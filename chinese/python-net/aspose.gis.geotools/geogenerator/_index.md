---
title: "GeoGenerator 类"
type: docs
weight: 30
url: /zh/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **描述** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | 创建一个新的 ILineString 枚举器，具有指定数量的随机项，所有项均位于给定范围内。 |
| [produce_points(rect, options)](#produce_points_rect_options_2) | 创建一个属于指定区域的点数组。 |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | 创建一个新的 IPolygon 枚举器，具有指定数量的随机项，所有项均位于给定范围内。 |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | 创建一个星形数组，所有星形均位于给定范围内。 |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

创建一个新的 ILineString 枚举器，具有指定数量的随机项，所有项均位于给定范围内。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 指定区域（参见 <see cref=\"T:Aspose.Gis.Extent\">Extent</see>） |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | 线创建选项（参见 <see cref=\"T:Aspose.Gis.GeoTools.LineGeneratorOptions\">LineGeneratorOptions</see>） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | 线数组（参见 <see cref=\"T:Aspose.Gis.Geometries.ILineString\">ILineString</see> 的枚举） |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

创建一个属于指定区域的点数组。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 指定区域（参见 <see cref=\"T:Aspose.Gis.Extent\">Extent</see>）。 |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | 点创建选项（参见 <see cref=\"T:Aspose.Gis.GeoTools.PointGeneratorOptions\">PointGeneratorOptions</see>）。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | 点数组（参见 <see cref=\"T:Aspose.Gis.Geometries.IGeometry\">IGeometry</see> 的枚举）。 |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

创建一个新的 IPolygon 枚举器，具有指定数量的随机项，所有项均位于给定范围内。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 指定区域（参见 <see cref=\"T:Aspose.Gis.Extent\">Extent</see>） |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | 多边形创建选项（参见 <see cref=\"T:Aspose.Gis.GeoTools.PolygonGeneratorOptions\">PolygonGeneratorOptions</see>） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | 多边形数组（参见 <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see> 的枚举） |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

创建一个星形数组，所有星形均位于给定范围内。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 指定区域（参见 <see cref=\"T:Aspose.Gis.Extent\">Extent</see>） |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | 多边形创建选项（参见 <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>） |

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | 星形数组（参见 <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see> 的枚举） |


