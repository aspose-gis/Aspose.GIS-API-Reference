---
title: "GeoGenerator Klasse"
type: docs
weight: 30
url: /de/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Erstellt einen neuen ILineString Enumerator mit einer angegebenen Anzahl zufälliger Elemente, die alle innerhalb eines angegebenen Ausdehnungsbereichs liegen. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Erstellt ein Array von Punkten, die zum angegebenen Bereich gehören. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Erstellt einen neuen IPolygon Enumerator mit einer angegebenen Anzahl zufälliger Elemente, die alle innerhalb eines angegebenen Ausdehnungsbereichs liegen. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Erstellt ein Array von Sternen, die alle innerhalb eines angegebenen Ausdehnungsbereichs liegen. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Erstellt einen neuen ILineString Enumerator mit einer angegebenen Anzahl zufälliger Elemente, die alle innerhalb eines angegebenen Ausdehnungsbereichs liegen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Angegebener Bereich (siehe <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Optionen zur Linenerstellung (siehe <see cref=\"T:Aspose.Gis.GeoTools.LineGeneratorOptions\">LineGeneratorOptions</see>) |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Array von Linien (siehe Aufzählung von <see cref=\"T:Aspose.Gis.Geometries.ILineString\">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Erstellt ein Array von Punkten, die zum angegebenen Bereich gehören.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Angegebener Bereich (siehe <see cref=\"T:Aspose.Gis.Extent\">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Optionen zur Punkterstellung (siehe <see cref=\"T:Aspose.Gis.GeoTools.PointGeneratorOptions\">PointGeneratorOptions</see>). |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Array von Punkten (siehe Aufzählung von <see cref=\"T:Aspose.Gis.Geometries.IGeometry\">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Erstellt einen neuen IPolygon Enumerator mit einer angegebenen Anzahl zufälliger Elemente, die alle innerhalb eines angegebenen Ausdehnungsbereichs liegen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Angegebener Bereich (siehe <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Optionen zur Polygonerstellung (siehe <see cref=\"T:Aspose.Gis.GeoTools.PolygonGeneratorOptions\">PolygonGeneratorOptions</see>) |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array von Polygonen (siehe Aufzählung von <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Erstellt ein Array von Sternen, die alle innerhalb eines angegebenen Ausdehnungsbereichs liegen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Angegebener Bereich (siehe <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Optionen zur Polygonerstellung (siehe <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array von Sternen (siehe Aufzählung von <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


