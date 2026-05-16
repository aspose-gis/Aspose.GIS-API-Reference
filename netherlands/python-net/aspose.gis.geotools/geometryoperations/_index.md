---
title: "GeometryOperations klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Bouw middenlijn diagram voor polygoon |
| [build_centerline(sites)](#build_centerline_sites_2) | Bouw middenlijn diagram voor verzameling punten (sites) |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Sluit geometrische segmenten in ringen indien nodig. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Maak middenpunten door een nieuw punt in het midden van elk segment toe te voegen. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Verwijder punten die te dicht bij elkaar liggen. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Extraheer geometrieverzameling uit laag |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Haal middenlijnlengte op |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Haal middenlijnlengte op |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Bouw "Voronoi" diagram voor verzameling punten (sites) |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Orden geometrieverzameling op type in vier verzamelingen (punt, lijn, polygoon en ander type) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Verwijder punten die op hetzelfde segment liggen. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Bouw middenlijn diagram voor polygoon

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polygoon voor middenlijn diagram |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Verzameling van middenlijnranden |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Bouw middenlijn diagram voor verzameling punten (sites)

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| locaties | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Verzameling van punten (sites) |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Verzameling van middenlijnranden |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Sluit geometrische segmenten in ringen indien nodig.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie voor sluiten. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | De geometrie na het sluiten. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Maak middenpunten door een nieuw punt in het midden van elk segment toe te voegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie voor verwerking. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | De geometrie na verwerking. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Verwijder punten die te dicht bij elkaar liggen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie voor het verwijderen van de dichtstbijzijnde punten. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | Opties voor het verwijderen van de dichtstbijzijnde punten. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | De geometrie na het verwijderen van het dichtstbijzijnde punt. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Extraheer geometrieverzameling uit laag

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Invoerlagen |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | De collectie bevat alle geometrieën van de invoerlagen. |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Haal middenlijnlengte op

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polygoon voor middenlijn diagram |

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | Lengte van de middenlijnranden. |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Haal middenlijnlengte op

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| locaties | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Verzameling van punten (sites) |

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | Lengte van de middenlijnranden. |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Bouw "Voronoi" diagram voor verzameling punten (sites)

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| locaties | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Verzameling van punten (sites) |

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Collectie van randen van het Voronoi-diagram. |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Orden geometrieverzameling op type in vier verzamelingen (punt, lijn, polygoon en ander type)

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrieverzameling voor volgorde. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | De collectie bevat vier verzamelingen (punt, lijn, polygoon en ander type). |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Verwijder punten die op hetzelfde segment liggen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometrie voor het verwijderen van extra punt. |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Opties voor het verwijderen van extra punt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | De geometrie na het verwijderen van extra punt. |


