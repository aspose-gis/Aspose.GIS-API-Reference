---
title: "Classe GeoGenerator"
type: docs
weight: 30
url: /fr/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Crée un nouvel énumérateur ILineString avec un nombre donné d'éléments aléatoires, tous situés dans une étendue donnée. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Crée un tableau de points appartenant à la zone spécifiée. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Crée un nouvel énumérateur IPolygon avec un nombre donné d'éléments aléatoires, tous situés dans une étendue donnée. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Crée un tableau d'étoiles, toutes situées dans une étendue donnée. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Crée un nouvel énumérateur ILineString avec un nombre donné d'éléments aléatoires, tous situés dans une étendue donnée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Zone spécifiée (voir <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Options de création de ligne (voir <see cref="T:Aspose.Gis.GeoTools.LineGeneratorOptions">LineGeneratorOptions</see>) |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Tableau de lignes (voir l'énumération de <see cref="T:Aspose.Gis.Geometries.ILineString">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Crée un tableau de points appartenant à la zone spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Zone spécifiée (voir <see cref="T:Aspose.Gis.Extent">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Options de création de point (voir <see cref="T:Aspose.Gis.GeoTools.PointGeneratorOptions">PointGeneratorOptions</see>). |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Tableau de points (voir l'énumération de <see cref="T:Aspose.Gis.Geometries.IGeometry">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Crée un nouvel énumérateur IPolygon avec un nombre donné d'éléments aléatoires, tous situés dans une étendue donnée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Zone spécifiée (voir <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Options de création de polygone (voir <see cref="T:Aspose.Gis.GeoTools.PolygonGeneratorOptions">PolygonGeneratorOptions</see>) |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Tableau de polygones (voir l'énumération de <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Crée un tableau d'étoiles, toutes situées dans une étendue donnée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Zone spécifiée (voir <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Options de création de polygone (voir <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Tableau d'étoiles (voir l'énumération de <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


