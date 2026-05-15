---
title: "GeoGenerator Κλάση"
type: docs
weight: 30
url: /el/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Δημιουργεί έναν νέο ILineString Enumerator με δεδομένο αριθμό τυχαίων στοιχείων, όλα εντός ενός δεδομένου εύρους. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Δημιουργεί έναν πίνακα σημείων που ανήκουν στην καθορισμένη περιοχή. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Δημιουργεί έναν νέο IPolygon Enumerator με δεδομένο αριθμό τυχαίων στοιχείων, όλα εντός ενός δεδομένου εύρους. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Δημιουργεί έναν πίνακα αστεριών, όλα εντός ενός δεδομένου εύρους. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Δημιουργεί έναν νέο ILineString Enumerator με δεδομένο αριθμό τυχαίων στοιχείων, όλα εντός ενός δεδομένου εύρους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Καθορισμένη περιοχή (see <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Επιλογές δημιουργίας γραμμής (see <see cref=\"T:Aspose.Gis.GeoTools.LineGeneratorOptions\">LineGeneratorOptions</see>) |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Πίνακας γραμμών (see enumeration of <see cref=\"T:Aspose.Gis.Geometries.ILineString\">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Δημιουργεί έναν πίνακα σημείων που ανήκουν στην καθορισμένη περιοχή.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Καθορισμένη περιοχή (see <see cref=\"T:Aspose.Gis.Extent\">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Επιλογές δημιουργίας σημείου (see <see cref=\"T:Aspose.Gis.GeoTools.PointGeneratorOptions\">PointGeneratorOptions</see>). |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Πίνακας σημείων (see enumeration of <see cref=\"T:Aspose.Gis.Geometries.IGeometry\">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Δημιουργεί έναν νέο IPolygon Enumerator με δεδομένο αριθμό τυχαίων στοιχείων, όλα εντός ενός δεδομένου εύρους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Καθορισμένη περιοχή (see <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Επιλογές δημιουργίας πολυγώνου (see <see cref=\"T:Aspose.Gis.GeoTools.PolygonGeneratorOptions\">PolygonGeneratorOptions</see>) |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Πίνακας πολυγώνων (δείτε την απαρίθμηση του <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Δημιουργεί έναν πίνακα αστεριών, όλα εντός ενός δεδομένου εύρους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Καθορισμένη περιοχή (see <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Επιλογές δημιουργίας πολυγώνου (δείτε <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Πίνακας αστεριών (δείτε την απαρίθμηση του <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


