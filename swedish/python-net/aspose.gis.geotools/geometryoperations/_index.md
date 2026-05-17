---
title: "GeometryOperations Klass"
type: docs
weight: 40
url: /sv/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Bygg centrumlinjediagram för polygon. |
| [build_centerline(sites)](#build_centerline_sites_2) | Bygg centrumlinjediagram för en samling punkter (platser). |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Stänger geometriska segment i ringar om det behövs. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Skapa mittpunkter genom att lägga till en ny punkt i mitten av varje segment. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Ta bort punkter som ligger för nära varandra. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Extrahera geometrisamling från lager. |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Hämta centrumlinjens längd. |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Hämta centrumlinjens längd. |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Bygg "Voronoi"-diagram för en samling punkter (platser). |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Sortera geometrisamling efter typ till fyra samlingar (punkt, linje, polygon och annan typ). |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Ta bort punkter som ligger på samma segment. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Bygg centrumlinjediagram för polygon.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polygon för centrumlinjediagram. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Samling av centrumlinjekanter. |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Bygg centrumlinjediagram för en samling punkter (platser).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| platser | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Samling av punkter (platser). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Samling av centrumlinjekanter. |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Stänger geometriska segment i ringar om det behövs.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri för stängning. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrin efter stängning. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Skapa mittpunkter genom att lägga till en ny punkt i mitten av varje segment.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri för bearbetning. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrin efter bearbetning. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Ta bort punkter som ligger för nära varandra.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri för att ta bort de närmaste punkterna. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | Alternativ för att ta bort de närmaste punkterna. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrin efter att ha tagit bort den närmaste punkten. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Extrahera geometrisamling från lager.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ingångslager |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Samlingen innehåller alla geometrier i ingångslagret |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Hämta centrumlinjens längd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polygon för centrumlinjediagram. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Längd på centrallinjens kanter |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Hämta centrumlinjens längd.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| platser | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Samling av punkter (platser). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Längd på centrallinjens kanter |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Bygg "Voronoi"-diagram för en samling punkter (platser).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| platser | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Samling av punkter (platser). |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Samling av kanter i Voronoidiagrammet |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Sortera geometrisamling efter typ till fyra samlingar (punkt, linje, polygon och annan typ).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri-samling för ordning |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Samlingen innehåller fyra samlingar (punkt, linje, polygon och annan typ) |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Ta bort punkter som ligger på samma segment.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri för att ta bort extra punkt |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Alternativ för att ta bort extra punkt |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrin efter att ha tagit bort extra punkt |


