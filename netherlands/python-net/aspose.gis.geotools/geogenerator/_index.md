---
title: "GeoGenerator Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Maakt een nieuwe ILineString Enumerator met een opgegeven aantal willekeurige items, allemaal binnen een opgegeven extent. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Maakt een array van punten die tot het opgegeven gebied behoren. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Maakt een nieuwe IPolygon Enumerator met een opgegeven aantal willekeurige items, allemaal binnen een opgegeven extent. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Maakt een array van sterren, allemaal binnen een opgegeven extent. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Maakt een nieuwe ILineString Enumerator met een opgegeven aantal willekeurige items, allemaal binnen een opgegeven extent.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Gespecificeerd gebied (zie <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Opties voor het maken van lijnen (zie <see cref=\"T:Aspose.Gis.GeoTools.LineGeneratorOptions\">LineGeneratorOptions</see>) |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Array van lijnen (zie enumeratie van <see cref=\"T:Aspose.Gis.Geometries.ILineString\">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Maakt een array van punten die tot het opgegeven gebied behoren.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Gespecificeerd gebied (zie <see cref=\"T:Aspose.Gis.Extent\">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Opties voor het maken van punten (zie <see cref=\"T:Aspose.Gis.GeoTools.PointGeneratorOptions\">PointGeneratorOptions</see>). |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Array van punten (zie enumeratie van <see cref=\"T:Aspose.Gis.Geometries.IGeometry\">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Maakt een nieuwe IPolygon Enumerator met een opgegeven aantal willekeurige items, allemaal binnen een opgegeven extent.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Gespecificeerd gebied (zie <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Opties voor het maken van polygonen (zie <see cref=\"T:Aspose.Gis.GeoTools.PolygonGeneratorOptions\">PolygonGeneratorOptions</see>) |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array van polygonen (zie enumeratie van <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Maakt een array van sterren, allemaal binnen een opgegeven extent.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Gespecificeerd gebied (zie <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Opties voor het maken van polygonen (zie <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array van sterren (zie enumeratie van <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


