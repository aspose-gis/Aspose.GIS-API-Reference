---
title: "Clase GeometryOperations"
type: docs
weight: 40
url: /es/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Construir diagrama de línea central para polígono |
| [build_centerline(sites)](#build_centerline_sites_2) | Construir diagrama de línea central para colección de puntos (sitios) |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Cierra segmentos geométricos en anillos si es necesario. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Crear puntos medios añadiendo un nuevo punto en el medio a cada segmento. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Eliminar puntos que están demasiado cerca unos de otros. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Extraer colección de geometrías de la capa |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Obtener longitud de la línea central |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Obtener longitud de la línea central |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Construir diagrama "Voronoi" para colección de puntos (sitios) |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Ordenar la colección de geometría por tipo en cuatro colecciones (punto, línea, polígono y otro tipo) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Eliminar puntos que se encuentran en el mismo segmento. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Construir diagrama de línea central para polígono

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polígono para diagrama de línea central |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Colección de bordes de línea central |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Construir diagrama de línea central para colección de puntos (sitios)

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sitios | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Colección de puntos (sitios) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Colección de bordes de línea central |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Cierra segmentos geométricos en anillos si es necesario.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometría para cerrar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometría después del cierre. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Crear puntos medios añadiendo un nuevo punto en el medio a cada segmento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometría para procesar. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometría después del procesamiento. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Eliminar puntos que están demasiado cerca unos de otros.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometría para eliminar los puntos más cercanos. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | Opciones para eliminar los puntos más cercanos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometría después de eliminar el punto más cercano. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Extraer colección de geometrías de la capa

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Capa de entrada |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La colección contiene todas las geometrías de la capa de entrada |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Obtener longitud de la línea central

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Polígono para diagrama de línea central |

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | Longitud de los bordes de la línea central |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Obtener longitud de la línea central

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sitios | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Colección de puntos (sitios) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | Longitud de los bordes de la línea central |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Construir diagrama "Voronoi" para colección de puntos (sitios)

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| sitios | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Colección de puntos (sitios) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Colección de bordes del diagrama de Voronoi |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Ordenar la colección de geometría por tipo en cuatro colecciones (punto, línea, polígono y otro tipo)

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Colección de geometrías para orden |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La colección contiene cuatro colecciones (punto, línea, polígono y otro tipo) |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Eliminar puntos que se encuentran en el mismo segmento.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometría para eliminar punto extra |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Opciones para eliminar punto extra |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | La geometría después de eliminar punto extra |


