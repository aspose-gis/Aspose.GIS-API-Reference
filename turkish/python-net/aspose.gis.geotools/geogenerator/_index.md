---
title: "GeoGenerator Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Verilen bir sayıda rastgele öğe ile yeni bir ILineString Enumerator oluşturur, tümü verilen bir kapsam içinde olur. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Belirtilen alana ait bir nokta dizisi oluşturur. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Verilen bir sayıda rastgele öğe ile yeni bir IPolygon Enumerator oluşturur, tümü verilen bir kapsam içinde olur. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Verilen bir kapsam içinde tüm yıldızları içeren bir dizi oluşturur. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Verilen bir sayıda rastgele öğe ile yeni bir ILineString Enumerator oluşturur, tümü verilen bir kapsam içinde olur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Belirtilen alan (bkz. <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Çizgi oluşturma seçenekleri (bkz. <see cref="T:Aspose.Gis.GeoTools.LineGeneratorOptions">LineGeneratorOptions</see>) |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Çizgi dizisi (bkz. <see cref="T:Aspose.Gis.Geometries.ILineString">ILineString</see> enumerasyonu) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Belirtilen alana ait bir nokta dizisi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Belirtilen alan (bkz. <see cref="T:Aspose.Gis.Extent">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Nokta oluşturma seçenekleri (bkz. <see cref="T:Aspose.Gis.GeoTools.PointGeneratorOptions">PointGeneratorOptions</see>). |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Nokta dizisi (bkz. <see cref="T:Aspose.Gis.Geometries.IGeometry">IGeometry</see> enumerasyonu). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Verilen bir sayıda rastgele öğe ile yeni bir IPolygon Enumerator oluşturur, tümü verilen bir kapsam içinde olur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Belirtilen alan (bkz. <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Poligon oluşturma seçenekleri (bkz. <see cref="T:Aspose.Gis.GeoTools.PolygonGeneratorOptions">PolygonGeneratorOptions</see>) |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Poligonların dizisi (bkz. <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Verilen bir kapsam içinde tüm yıldızları içeren bir dizi oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Belirtilen alan (bkz. <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Poligon oluşturma seçenekleri (bkz. <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Yıldızların dizisi (bkz. <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


