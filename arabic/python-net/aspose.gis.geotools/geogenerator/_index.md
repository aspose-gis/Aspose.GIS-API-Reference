---
title: "فئة GeoGenerator"
type: docs
weight: 30
url: /ar/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | ينشئ عدّاد ILineString جديد بعدد معين من العناصر العشوائية، جميعها داخل مدى محدد. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | ينشئ مصفوفة من النقاط التي تنتمي إلى المنطقة المحددة. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | ينشئ عدّاد IPolygon جديد بعدد معين من العناصر العشوائية، جميعها داخل مدى محدد. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | ينشئ مصفوفة من النجوم، جميعها داخل مدى محدد. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

ينشئ عدّاد ILineString جديد بعدد معين من العناصر العشوائية، جميعها داخل مدى محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | المنطقة المحددة (انظر <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | خيارات إنشاء الخط (انظر <see cref=\"T:Aspose.Gis.GeoTools.LineGeneratorOptions\">LineGeneratorOptions</see>) |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | مصفوفة من الخطوط (انظر تعداد <see cref=\"T:Aspose.Gis.Geometries.ILineString\">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

ينشئ مصفوفة من النقاط التي تنتمي إلى المنطقة المحددة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | المنطقة المحددة (انظر <see cref=\"T:Aspose.Gis.Extent\">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | خيارات إنشاء النقطة (انظر <see cref=\"T:Aspose.Gis.GeoTools.PointGeneratorOptions\">PointGeneratorOptions</see>). |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | مصفوفة من النقاط (انظر تعداد <see cref=\"T:Aspose.Gis.Geometries.IGeometry\">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

ينشئ عدّاد IPolygon جديد بعدد معين من العناصر العشوائية، جميعها داخل مدى محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | المنطقة المحددة (انظر <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | خيارات إنشاء المضلع (انظر <see cref=\"T:Aspose.Gis.GeoTools.PolygonGeneratorOptions\">PolygonGeneratorOptions</see>) |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | مصفوفة من المضلعات (انظر تعداد <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

ينشئ مصفوفة من النجوم، جميعها داخل مدى محدد.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | المنطقة المحددة (انظر <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | خيارات إنشاء المضلعات (انظر <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | مصفوفة من النجوم (انظر تعداد <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


