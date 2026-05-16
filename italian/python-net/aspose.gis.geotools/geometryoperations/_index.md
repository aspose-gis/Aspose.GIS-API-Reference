---
title: "Classe GeometryOperations"
type: docs
weight: 40
url: /it/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Crea diagramma della linea centrale per il poligono |
| [build_centerline(sites)](#build_centerline_sites_2) | Crea diagramma della linea centrale per una collezione di punti (siti) |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Chiude i segmenti geometrici negli anelli se necessario. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Crea punti medi aggiungendo un nuovo punto al centro di ogni segmento. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Elimina i punti che sono troppo vicini tra loro. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Estrai la collezione geometrica dal livello |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Ottieni la lunghezza della linea centrale |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Ottieni la lunghezza della linea centrale |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Crea diagramma "Voronoi" per una collezione di punti (siti) |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Ordina la collezione geometrica per tipo in quattro collezioni (punto, linea, poligono e altri tipi) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Elimina i punti che giacciono sullo stesso segmento. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Crea diagramma della linea centrale per il poligono

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Poligono per il diagramma della linea centrale |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Collezione di spigoli della linea centrale |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Crea diagramma della linea centrale per una collezione di punti (siti)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| siti | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Collezione di punti (siti) |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Collezione di spigoli della linea centrale |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Chiude i segmenti geometrici negli anelli se necessario.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometria per la chiusura. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometria dopo la chiusura. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Crea punti medi aggiungendo un nuovo punto al centro di ogni segmento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometria per l'elaborazione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometria dopo l'elaborazione. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Elimina i punti che sono troppo vicini tra loro.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometria per l'eliminazione dei punti più vicini. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | Opzioni per l'eliminazione dei punti più vicini. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometria dopo l'eliminazione del punto più vicino. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Estrai la collezione geometrica dal livello

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Layer di input |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La collezione contiene tutte le geometrie del layer di input. |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Ottieni la lunghezza della linea centrale

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Poligono per il diagramma della linea centrale |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | Lunghezza dei bordi della linea centrale. |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Ottieni la lunghezza della linea centrale

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| siti | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Collezione di punti (siti) |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | Lunghezza dei bordi della linea centrale. |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Crea diagramma "Voronoi" per una collezione di punti (siti)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| siti | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Collezione di punti (siti) |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Collezione dei bordi del diagramma di Voronoi. |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Ordina la collezione geometrica per tipo in quattro collezioni (punto, linea, poligono e altri tipi)

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Collezione di geometrie per ordine. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La collezione contiene quattro collezioni (punto, linea, poligono e altro tipo). |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Elimina i punti che giacciono sullo stesso segmento.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometria per l'eliminazione del punto extra. |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Opzioni per l'eliminazione del punto extra. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometria dopo l'eliminazione del punto extra. |


