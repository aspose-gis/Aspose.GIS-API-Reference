---
title: "GeoGenerator-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Skapar en ny ILineString-enumerator med ett givet antal slumpmässiga element, alla inom ett givet omfång. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Skapar en array av punkter som tillhör det angivna området. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Skapar en ny IPolygon-enumerator med ett givet antal slumpmässiga element, alla inom ett givet omfång. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Skapar en array av stjärnor, alla inom ett givet omfång. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Skapar en ny ILineString-enumerator med ett givet antal slumpmässiga element, alla inom ett givet omfång.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Angivet område (se <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Alternativ för linjeskapande (se <see cref=\"T:Aspose.Gis.GeoTools.LineGeneratorOptions\">LineGeneratorOptions</see>) |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Array av linjer (se uppräkning av <see cref=\"T:Aspose.Gis.Geometries.ILineString\">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Skapar en array av punkter som tillhör det angivna området.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Angivet område (se <see cref=\"T:Aspose.Gis.Extent\">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Alternativ för punktgenerering (se <see cref=\"T:Aspose.Gis.GeoTools.PointGeneratorOptions\">PointGeneratorOptions</see>). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Array av punkter (se uppräkning av <see cref=\"T:Aspose.Gis.Geometries.IGeometry\">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Skapar en ny IPolygon-enumerator med ett givet antal slumpmässiga element, alla inom ett givet omfång.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Angivet område (se <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Alternativ för polygongenerering (se <see cref=\"T:Aspose.Gis.GeoTools.PolygonGeneratorOptions\">PolygonGeneratorOptions</see>) |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array av polygoner (se uppräkning av <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Skapar en array av stjärnor, alla inom ett givet omfång.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Angivet område (se <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Alternativ för polygon‑skapande (se <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array av stjärnor (se uppräkning av <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


