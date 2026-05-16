---
title: "GeoGenerator 클래스"
type: docs
weight: 30
url: /ko/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | 주어진 범위 내에서 무작위 항목을 지정된 수만큼 포함하는 새로운 ILineString 열거자를 생성합니다. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | 지정된 영역에 속하는 포인트 배열을 생성합니다. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | 주어진 범위 내에서 무작위 항목을 지정된 수만큼 포함하는 새로운 IPolygon 열거자를 생성합니다. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | 주어진 범위 내에 있는 별들의 배열을 생성합니다. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

주어진 범위 내에서 무작위 항목을 지정된 수만큼 포함하는 새로운 ILineString 열거자를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 지정된 영역 (see <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | 선 생성 옵션 (see <see cref="T:Aspose.Gis.GeoTools.LineGeneratorOptions">LineGeneratorOptions</see>) |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | 선 배열 (see enumeration of <see cref="T:Aspose.Gis.Geometries.ILineString">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

지정된 영역에 속하는 포인트 배열을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 지정된 영역 (see <see cref="T:Aspose.Gis.Extent">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | 포인트 생성 옵션 (see <see cref="T:Aspose.Gis.GeoTools.PointGeneratorOptions">PointGeneratorOptions</see>). |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | 포인트 배열 (see enumeration of <see cref="T:Aspose.Gis.Geometries.IGeometry">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

주어진 범위 내에서 무작위 항목을 지정된 수만큼 포함하는 새로운 IPolygon 열거자를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 지정된 영역 (see <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | 폴리곤 생성 옵션 (see <see cref="T:Aspose.Gis.GeoTools.PolygonGeneratorOptions">PolygonGeneratorOptions</see>) |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | 다각형 배열 (다음 열거형 <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see> 참조) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

주어진 범위 내에 있는 별들의 배열을 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | 지정된 영역 (see <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | 다각형 생성 옵션 (다음 <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see> 참조) |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | 별 배열 (다음 열거형 <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see> 참조) |


