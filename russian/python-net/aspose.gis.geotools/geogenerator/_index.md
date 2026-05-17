---
title: "GeoGenerator Класс"
type: docs
weight: 30
url: /ru/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Создает новый перечислитель ILineString с заданным числом случайных элементов, все они находятся в заданном диапазоне. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Создает массив точек, принадлежащих указанной области. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Создает новый перечислитель IPolygon с заданным числом случайных элементов, все они находятся в заданном диапазоне. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Создает массив звёзд, все они находятся в заданном диапазоне. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Создает новый перечислитель ILineString с заданным числом случайных элементов, все они находятся в заданном диапазоне.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Указанная область (см. <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Параметры создания линии (см. <see cref="T:Aspose.Gis.GeoTools.LineGeneratorOptions">LineGeneratorOptions</see>) |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Массив линий (см. перечисление <see cref="T:Aspose.Gis.Geometries.ILineString">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Создает массив точек, принадлежащих указанной области.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Указанная область (см. <see cref="T:Aspose.Gis.Extent">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Параметры создания точки (см. <see cref="T:Aspose.Gis.GeoTools.PointGeneratorOptions">PointGeneratorOptions</see>). |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Массив точек (см. перечисление <see cref="T:Aspose.Gis.Geometries.IGeometry">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Создает новый перечислитель IPolygon с заданным числом случайных элементов, все они находятся в заданном диапазоне.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Указанная область (см. <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Параметры создания полигона (см. <see cref="T:Aspose.Gis.GeoTools.PolygonGeneratorOptions">PolygonGeneratorOptions</see>) |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Массив полигонов (см. перечисление <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Создает массив звёзд, все они находятся в заданном диапазоне.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Указанная область (см. <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Параметры создания полигонов (см. <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Массив звёзд (см. перечисление <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


