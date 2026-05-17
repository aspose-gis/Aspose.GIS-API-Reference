---
title: "Clase GeoGenerator"
type: docs
weight: 30
url: /es/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Crea un nuevo enumerador ILineString con un número dado de elementos aleatorios, todos dentro de una extensión dada. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Crea una matriz de puntos pertenecientes al área especificada. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Crea un nuevo enumerador IPolygon con un número dado de elementos aleatorios, todos dentro de una extensión dada. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Crea una matriz de estrellas, todas dentro de una extensión dada. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Crea un nuevo enumerador ILineString con un número dado de elementos aleatorios, todos dentro de una extensión dada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Área especificada (ver <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Opciones de creación de líneas (ver <see cref=\"T:Aspose.Gis.GeoTools.LineGeneratorOptions\">LineGeneratorOptions</see>) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Matriz de líneas (ver enumeración de <see cref=\"T:Aspose.Gis.Geometries.ILineString\">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Crea una matriz de puntos pertenecientes al área especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Área especificada (ver <see cref=\"T:Aspose.Gis.Extent\">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Opciones de creación de puntos (ver <see cref=\"T:Aspose.Gis.GeoTools.PointGeneratorOptions\">PointGeneratorOptions</see>). |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Matriz de puntos (ver enumeración de <see cref=\"T:Aspose.Gis.Geometries.IGeometry\">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Crea un nuevo enumerador IPolygon con un número dado de elementos aleatorios, todos dentro de una extensión dada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Área especificada (ver <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Opciones de creación de polígonos (ver <see cref=\"T:Aspose.Gis.GeoTools.PolygonGeneratorOptions\">PolygonGeneratorOptions</see>) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Matriz de polígonos (ver enumeración de <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Crea una matriz de estrellas, todas dentro de una extensión dada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Área especificada (ver <see cref=\"T:Aspose.Gis.Extent\">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Opciones de creación de polígonos (ver <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Matriz de estrellas (ver enumeración de <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


