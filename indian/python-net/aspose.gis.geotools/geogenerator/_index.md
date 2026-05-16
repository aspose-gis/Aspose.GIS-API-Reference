---
title: "GeoGenerator क्लास"
type: docs
weight: 30
url: /hi/python-net/aspose.gis.geotools/geogenerator/
---

**Summary:** Generator of random points, lines and polygons on given planes.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeoGenerator

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [produce_lines(rect, options)](#produce_lines_rect_options_1) | दिए गए विस्तार के भीतर सभी रैंडम आइटमों की एक निर्दिष्ट संख्या के साथ एक नया ILineString Enumerator बनाता है। |
| [produce_points(rect, options)](#produce_points_rect_options_2) | निर्दिष्ट क्षेत्र से संबंधित बिंदुओं की एक एरे बनाता है। |
| [produce_polygons(rect, options)](#produce_polygons_rect_options_3) | दिए गए विस्तार के भीतर सभी रैंडम आइटमों की एक निर्दिष्ट संख्या के साथ एक नया IPolygon Enumerator बनाता है। |
| [produce_stars(rect, options)](#produce_stars_rect_options_4) | दिए गए विस्तार के भीतर सभी सितारों की एक एरे बनाता है। |


### Method: produce_lines(rect, options)  [static] {#produce_lines_rect_options_1}


```
 produce_lines(rect, options) 
```

दिए गए विस्तार के भीतर सभी रैंडम आइटमों की एक निर्दिष्ट संख्या के साथ एक नया ILineString Enumerator बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | निर्दिष्ट क्षेत्र (see <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [LineGeneratorOptions](/psd/python-net/aspose.gis.geotools/linegeneratoroptions) | लाइन निर्माण विकल्प (see <see cref="T:Aspose.Gis.GeoTools.LineGeneratorOptions">LineGeneratorOptions</see>) |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.ILineString> | रेखाओं की एरे (see enumeration of <see cref="T:Aspose.Gis.Geometries.ILineString">ILineString</see>) |


### Method: produce_points(rect, options)  [static] {#produce_points_rect_options_2}


```
 produce_points(rect, options) 
```

निर्दिष्ट क्षेत्र से संबंधित बिंदुओं की एक एरे बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | निर्दिष्ट क्षेत्र (see <see cref="T:Aspose.Gis.Extent">Extent</see>). |
| options | [PointGeneratorOptions](/psd/python-net/aspose.gis.geotools/pointgeneratoroptions) | बिंदु निर्माण विकल्प (see <see cref="T:Aspose.Gis.GeoTools.PointGeneratorOptions">PointGeneratorOptions</see>). |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IGeometry> | बिंदुओं की एरे (see enumeration of <see cref="T:Aspose.Gis.Geometries.IGeometry">IGeometry</see>). |


### Method: produce_polygons(rect, options)  [static] {#produce_polygons_rect_options_3}


```
 produce_polygons(rect, options) 
```

दिए गए विस्तार के भीतर सभी रैंडम आइटमों की एक निर्दिष्ट संख्या के साथ एक नया IPolygon Enumerator बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | निर्दिष्ट क्षेत्र (see <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [PolygonGeneratorOptions](/psd/python-net/aspose.gis.geotools/polygongeneratoroptions) | बहुभुज निर्माण विकल्प (see <see cref="T:Aspose.Gis.GeoTools.PolygonGeneratorOptions">PolygonGeneratorOptions</see>) |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | बहुभुजों की सरणी (देखें <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see> की सूची) |


### Method: produce_stars(rect, options)  [static] {#produce_stars_rect_options_4}


```
 produce_stars(rect, options) 
```

दिए गए विस्तार के भीतर सभी सितारों की एक एरे बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| rect | [Extent](/psd/python-net/aspose.gis/extent) | निर्दिष्ट क्षेत्र (see <see cref="T:Aspose.Gis.Extent">Extent</see>) |
| options | [StarGeneratorOptions](/psd/python-net/aspose.gis.geotools/stargeneratoroptions) | बहुभुज निर्माण विकल्प (देखें <see cref="T:Aspose.Gis.GeoTools.StarGeneratorOptions">StarGeneratorOptions</see>) |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPolygon> | सितारों की सरणी (देखें <see cref="T:Aspose.Gis.Geometries.IPolygon">IPolygon</see> की सूची) |


