---
title: "Classe GeometryOperations"
type: docs
weight: 40
url: /fr/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Construire le diagramme de ligne centrale pour un polygone |
| [build_centerline(sites)](#build_centerline_sites_2) | Construire le diagramme de ligne centrale pour une collection de points (sites) |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Ferme les segments géométriques dans les anneaux si nécessaire. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Créer des points milieux en ajoutant un nouveau point au centre de chaque segment. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Supprimer les points qui sont trop proches les uns des autres. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Extraire la collection de géométries depuis la couche |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Obtenir la longueur de la ligne centrale |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Obtenir la longueur de la ligne centrale |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Construire le diagramme "Voronoi" pour une collection de points (sites) |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Classer la collection de géométrie par type en quatre collections (point, ligne, polygone et autre type) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Supprimer les points se trouvant sur le même segment. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Construire le diagramme de ligne centrale pour un polygone

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polygone pour le diagramme de ligne centrale |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Collection d'arêtes de ligne centrale |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Construire le diagramme de ligne centrale pour une collection de points (sites)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sites | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Collection de points (sites) |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Collection d'arêtes de ligne centrale |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Ferme les segments géométriques dans les anneaux si nécessaire.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Géométrie pour la fermeture. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La géométrie après la fermeture. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Créer des points milieux en ajoutant un nouveau point au centre de chaque segment.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Géométrie pour le traitement. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La géométrie après le traitement. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Supprimer les points qui sont trop proches les uns des autres.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Géométrie pour supprimer les points les plus proches. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | Options pour supprimer les points les plus proches. |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La géométrie après la suppression du point le plus proche. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Extraire la collection de géométries depuis la couche

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Couche d'entrée |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La collection contient toutes les géométries de la couche d'entrée |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Obtenir la longueur de la ligne centrale

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polygone pour le diagramme de ligne centrale |

**Returns**

| Type | Description |
| :- | :- |
| double | Longueur des arêtes de la ligne centrale |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Obtenir la longueur de la ligne centrale

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sites | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Collection de points (sites) |

**Returns**

| Type | Description |
| :- | :- |
| double | Longueur des arêtes de la ligne centrale |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Construire le diagramme "Voronoi" pour une collection de points (sites)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sites | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Collection de points (sites) |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Collection des arêtes du diagramme de Voronoï |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Classer la collection de géométrie par type en quatre collections (point, ligne, polygone et autre type)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Collection de géométrie pour l'ordre |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La collection contient quatre collections (point, ligne, polygone et autre type) |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Supprimer les points se trouvant sur le même segment.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Géométrie pour supprimer le point supplémentaire |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Options pour supprimer le point supplémentaire |

**Returns**

| Type | Description |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La géométrie après la suppression du point supplémentaire |


