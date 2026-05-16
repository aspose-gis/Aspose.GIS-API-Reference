---
title: "Kelas GeoGenerator"
type: docs
weight: 30
url: /id/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | Membuat Enumerator ILineString baru dengan sejumlah item acak yang diberikan, semuanya berada dalam rentang tertentu. |
| [produce_points(rect, options)](#produce_points_rect_options_2) | Membuat array titik yang termasuk dalam area yang ditentukan. |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | Membuat Enumerator IPolygon baru dengan sejumlah item acak yang diberikan, semuanya berada dalam rentang tertentu. |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | Membuat array bintang, semuanya berada dalam rentang tertentu. |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

Membuat Enumerator ILineString baru dengan sejumlah item acak yang diberikan, semuanya berada dalam rentang tertentu.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Area yang ditentukan (see <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | Opsi pembuatan garis (see <see cref="T:Aspose.Gis.GeoTools.LineGeneratorOptions">LineGeneratorOptions</see>) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | Array garis (see enumeration of <see cref="T:Aspose.Gis.Geometries.ILineString">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

Membuat array titik yang termasuk dalam area yang ditentukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Area yang ditentukan (see <see cref="T:Aspose.Gis.Extent">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | Opsi pembuatan titik (see <see cref="T:Aspose.Gis.GeoTools.PointGeneratorOptions">PointGeneratorOptions</see>). |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | Array titik (see enumeration of <see cref="T:Aspose.Gis.Geometries.IGeometry">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

Membuat Enumerator IPolygon baru dengan sejumlah item acak yang diberikan, semuanya berada dalam rentang tertentu.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Area yang ditentukan (see <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | Opsi pembuatan poligon (see <see cref="T:Aspose.Gis.GeoTools.PolygonGeneratorOptions">PolygonGeneratorOptions</see>) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array poligon (lihat enumerasi dari <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

Membuat array bintang, semuanya berada dalam rentang tertentu.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | Area yang ditentukan (see <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | Opsi pembuatan poligon (lihat <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | Array bintang (lihat enumerasi dari <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see>) |


