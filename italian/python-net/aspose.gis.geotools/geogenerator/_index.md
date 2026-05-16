---
title: "Classe GeoGenerator"
type: docs
weight: 30
url: /it/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Crea un nuovo enumeratore ILineString con un numero specificato di elementi casuali, tutti all'interno di un'estensione data. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Crea un array di punti appartenenti all'area specificata. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Crea un nuovo enumeratore IPolygon con un numero specificato di elementi casuali, tutti all'interno di un'estensione data. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Crea un array di stelle, tutte all'interno di un'estensione data. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Crea un nuovo enumeratore ILineString con un numero specificato di elementi casuali, tutti all'interno di un'estensione data.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Area specificata (vedi <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Opzioni di creazione della linea (vedi <see cref="T:Aspose.Gis.GeoTools.LineGeneratorOptions">LineGeneratorOptions</see>) |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Array di linee (vedi l'enumerazione di <see cref="T:Aspose.Gis.Geometries.ILineString">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Crea un array di punti appartenenti all'area specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Area specificata (vedi <see cref="T:Aspose.Gis.Extent">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Opzioni di creazione del punto (vedi <see cref="T:Aspose.Gis.GeoTools.PointGeneratorOptions">PointGeneratorOptions</see>). |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Array di punti (vedi l'enumerazione di <see cref="T:Aspose.Gis.Geometries.IGeometry">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Crea un nuovo enumeratore IPolygon con un numero specificato di elementi casuali, tutti all'interno di un'estensione data.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Area specificata (vedi <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Opzioni di creazione del poligono (vedi <see cref="T:Aspose.Gis.GeoTools.PolygonGeneratorOptions">PolygonGeneratorOptions</see>) |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array di poligoni (vedi l'enumerazione di <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Crea un array di stelle, tutte all'interno di un'estensione data.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Area specificata (vedi <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Opzioni di creazione del poligono (vedi <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array di stelle (vedi l'enumerazione di <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


