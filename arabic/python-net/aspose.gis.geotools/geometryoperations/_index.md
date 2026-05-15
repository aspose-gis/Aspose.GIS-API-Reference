---
title: "فئة GeometryOperations"
type: docs
weight: 40
url: /ar/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | إنشاء مخطط الخط المركزي للمضلع |
| [build_centerline(sites)](#build_centerline_sites_2) | إنشاء مخطط الخط المركزي لمجموعة من النقاط (المواقع) |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | يغلق المقاطع الهندسية في الحلقات إذا لزم الأمر. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | إنشاء نقاط وسطى بإضافة نقطة جديدة في الوسط لكل مقطع. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | حذف النقاط التي هي قريبة جدًا من بعضها البعض. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | استخراج مجموعة الهندسة من الطبقة |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | الحصول على طول الخط المركزي |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | الحصول على طول الخط المركزي |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | إنشاء مخطط "Voronoi" لمجموعة من النقاط (المواقع) |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | ترتيب مجموعة الهندسة حسب النوع إلى أربع مجموعات (نقطة، خط، مضلع ونوع آخر) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | حذف النقاط الواقعة على نفس المقطع. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

إنشاء مخطط الخط المركزي للمضلع

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | مضلع لمخطط الخط المركزي |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | مجموعة من حواف الخط المركزي |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

إنشاء مخطط الخط المركزي لمجموعة من النقاط (المواقع)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المواقع | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | مجموعة من النقاط (المواقع) |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | مجموعة من حواف الخط المركزي |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

يغلق المقاطع الهندسية في الحلقات إذا لزم الأمر.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | الهندسة للإغلاق. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | الهندسة بعد الإغلاق. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

إنشاء نقاط وسطى بإضافة نقطة جديدة في الوسط لكل مقطع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | الهندسة للمعالجة. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | الهندسة بعد المعالجة. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

حذف النقاط التي هي قريبة جدًا من بعضها البعض.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | الهندسة لحذف النقاط الأقرب. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | خيارات حذف النقاط الأقرب. |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | الهندسة بعد حذف أقرب نقطة. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

استخراج مجموعة الهندسة من الطبقة

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | طبقة الإدخال |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | المجموعة تحتوي على جميع الهندسات لطبقة الإدخال |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

الحصول على طول الخط المركزي

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | مضلع لمخطط الخط المركزي |

**Returns**

| نوع | الوصف |
| :- | :- |
| double | طول حواف الخط المركزي |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

الحصول على طول الخط المركزي

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المواقع | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | مجموعة من النقاط (المواقع) |

**Returns**

| نوع | الوصف |
| :- | :- |
| double | طول حواف الخط المركزي |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

إنشاء مخطط "Voronoi" لمجموعة من النقاط (المواقع)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المواقع | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | مجموعة من النقاط (المواقع) |

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | مجموعة حواف مخطط فوروينوي |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

ترتيب مجموعة الهندسة حسب النوع إلى أربع مجموعات (نقطة، خط، مضلع ونوع آخر)

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | مجموعة الهندسة للترتيب |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | المجموعة تحتوي على أربع مجموعات (نقطة، خط، مضلع ونوع آخر) |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

حذف النقاط الواقعة على نفس المقطع.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | الهندسة لحذف النقطة الزائدة |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | خيارات حذف النقطة الزائدة |

**Returns**

| نوع | الوصف |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | الهندسة بعد حذف النقطة الزائدة |


