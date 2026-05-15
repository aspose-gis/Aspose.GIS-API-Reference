---
title: "GeometryOperations Klasse"
type: docs
weight: 40
url: /de/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Zentralenlinien-Diagramm für Polygon erstellen |
| [build_centerline(sites)](#build_centerline_sites_2) | Zentralenlinien-Diagramm für eine Sammlung von Punkten (Standorte) erstellen |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Schließt geometrische Segmente in Ringen, falls erforderlich. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Erstelle Mittelpunkte, indem zu jedem Segment ein neuer Punkt in der Mitte hinzugefügt wird. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Lösche Punkte, die zu nahe beieinander liegen. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Geometriesammlung aus Ebene extrahieren |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Zentralenlinienlänge erhalten |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Zentralenlinienlänge erhalten |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | \"Voronoi\"-Diagramm für eine Sammlung von Punkten (Standorte) erstellen |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Ordne Geometriesammlung nach Typ in vier Sammlungen (Punkt, Linie, Polygon und anderer Typ) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Lösche Punkte, die auf demselben Segment liegen. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Zentralenlinien-Diagramm für Polygon erstellen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polygon für Zentralenlinien-Diagramm |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Sammlung von Zentralenlinienkanten |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Zentralenlinien-Diagramm für eine Sammlung von Punkten (Standorte) erstellen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Standorte | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Sammlung von Punkten (Standorte) |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Sammlung von Zentralenlinienkanten |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Schließt geometrische Segmente in Ringen, falls erforderlich.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie zum Schließen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Die Geometrie nach dem Schließen. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Erstelle Mittelpunkte, indem zu jedem Segment ein neuer Punkt in der Mitte hinzugefügt wird.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie zur Verarbeitung. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Die Geometrie nach der Verarbeitung. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Lösche Punkte, die zu nahe beieinander liegen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie zum Löschen der nächsten Punkte. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | Optionen zum Löschen der nächsten Punkte. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Die Geometrie nach dem Löschen des nächsten Punktes. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Geometriesammlung aus Ebene extrahieren

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eingabelayer |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Die Sammlung enthält alle Geometrien des Eingabelayers |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Zentralenlinienlänge erhalten

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polygon für Zentralenlinien-Diagramm |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Länge der Mittelachsenkanten |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Zentralenlinienlänge erhalten

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Standorte | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Sammlung von Punkten (Standorte) |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double | Länge der Mittelachsenkanten |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

\"Voronoi\"-Diagramm für eine Sammlung von Punkten (Standorte) erstellen

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Standorte | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Sammlung von Punkten (Standorte) |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Sammlung von Kanten des Voronoi-Diagramms |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Ordne Geometriesammlung nach Typ in vier Sammlungen (Punkt, Linie, Polygon und anderer Typ)

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometriemenge für die Reihenfolge |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Die Sammlung enthält vier Sammlungen (Punkt, Linie, Polygon und anderer Typ) |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Lösche Punkte, die auf demselben Segment liegen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie zum Löschen eines zusätzlichen Punktes |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Optionen zum Löschen eines zusätzlichen Punktes |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Die Geometrie nach dem Löschen des zusätzlichen Punktes |


