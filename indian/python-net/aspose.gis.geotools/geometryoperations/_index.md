---
title: "GeometryOperations क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | बहुभुज के लिए सेंटरलाइन आरेख बनाएं |
| [build_centerline(sites)](#build_centerline_sites_2) | बिंदुओं (साइट्स) के संग्रह के लिए सेंटरलाइन आरेख बनाएं |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | यदि आवश्यक हो तो रिंग्स में ज्यामितीय खंडों को बंद करता है। |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | प्रत्येक खंड के मध्य में एक नया बिंदु जोड़कर मध्य बिंदु बनाएं। |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | एक-दूसरे के बहुत निकट बिंदुओं को हटाएं। |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | लेयर से ज्यामिति संग्रह निकालें |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | सेंटरलाइन की लंबाई प्राप्त करें |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | सेंटरलाइन की लंबाई प्राप्त करें |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Build "Voronoi" आरेख बनाएं बिंदुओं (साइट्स) के संग्रह के लिए |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | ज्यामिति संग्रह को प्रकार के अनुसार चार संग्रहों में क्रमबद्ध करें (बिंदु, रेखा, बहुभुज और अन्य प्रकार) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | एक ही खंड पर स्थित बिंदुओं को हटाएं। |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

बहुभुज के लिए सेंटरलाइन आरेख बनाएं

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | सेंटरलाइन आरेख के लिए बहुभुज |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | सेंटरलाइन किनारों का संग्रह |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

बिंदुओं (साइट्स) के संग्रह के लिए सेंटरलाइन आरेख बनाएं

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| साइट्स | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | बिंदुओं (साइट्स) का संग्रह |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | सेंटरलाइन किनारों का संग्रह |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

यदि आवश्यक हो तो रिंग्स में ज्यामितीय खंडों को बंद करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | बंद करने के लिए ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | बंद करने के बाद की ज्यामिति। |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

प्रत्येक खंड के मध्य में एक नया बिंदु जोड़कर मध्य बिंदु बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | प्रसंस्करण के लिए ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | प्रसंस्करण के बाद की ज्यामिति। |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

एक-दूसरे के बहुत निकट बिंदुओं को हटाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | निकटतम बिंदुओं को हटाने के लिए ज्यामिति। |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | निकटतम बिंदुओं को हटाने के विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | निकटतम बिंदु हटाने के बाद की ज्यामिति। |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

लेयर से ज्यामिति संग्रह निकालें

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | इनपुट लेयर |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | संग्रह में इनपुट लेयर की सभी ज्यामितियां शामिल हैं |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

सेंटरलाइन की लंबाई प्राप्त करें

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | सेंटरलाइन आरेख के लिए बहुभुज |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double | केंद्ररेखा किनारों की लंबाई |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

सेंटरलाइन की लंबाई प्राप्त करें

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| साइट्स | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | बिंदुओं (साइट्स) का संग्रह |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double | केंद्ररेखा किनारों की लंबाई |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Build "Voronoi" आरेख बनाएं बिंदुओं (साइट्स) के संग्रह के लिए

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| साइट्स | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | बिंदुओं (साइट्स) का संग्रह |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | वोरोनॉई आरेख के किनारों का संग्रह |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

ज्यामिति संग्रह को प्रकार के अनुसार चार संग्रहों में क्रमबद्ध करें (बिंदु, रेखा, बहुभुज और अन्य प्रकार)

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | क्रम के लिए ज्यामिति संग्रह |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | संग्रह में चार उपसंग्रह (बिंदु, रेखा, बहुभुज और अन्य प्रकार) शामिल हैं |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

एक ही खंड पर स्थित बिंदुओं को हटाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | अतिरिक्त बिंदु हटाने के लिए ज्यामिति |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | अतिरिक्त बिंदु हटाने के विकल्प |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | अतिरिक्त बिंदु हटाने के बाद की ज्यामिति |


