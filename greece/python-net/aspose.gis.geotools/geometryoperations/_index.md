---
title: "GeometryOperations Κλάση"
type: docs
weight: 40
url: /el/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Δημιουργήστε διάγραμμα κεντρικής γραμμής για πολύγωνο |
| [build_centerline(sites)](#build_centerline_sites_2) | Δημιουργήστε διάγραμμα κεντρικής γραμμής για συλλογή σημείων (τοποθεσίες) |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Κλείνει γεωμετρικά τμήματα σε δακτυλίους εάν χρειάζεται. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Δημιουργήστε μεσαία σημεία προσθέτοντας ένα νέο σημείο στη μέση σε κάθε τμήμα. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Διαγράψτε σημεία που είναι πολύ κοντά μεταξύ τους. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Εξάγετε τη συλλογή γεωμετρίας από το στρώμα |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Λάβετε το μήκος της κεντρικής γραμμής |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Λάβετε το μήκος της κεντρικής γραμμής |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Δημιουργήστε διάγραμμα "Voronoi" για συλλογή σημείων (τοποθεσίες) |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Ταξινομήστε τη συλλογή γεωμετρίας κατά τύπο σε τέσσερις συλλογές (σημείο, γραμμή, πολύγωνο και άλλου τύπου) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Διαγράψτε σημεία που βρίσκονται στο ίδιο τμήμα. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Δημιουργήστε διάγραμμα κεντρικής γραμμής για πολύγωνο

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Πολύγωνο για διάγραμμα κεντρικής γραμμής |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Συλλογή ακμών κεντρικής γραμμής |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Δημιουργήστε διάγραμμα κεντρικής γραμμής για συλλογή σημείων (τοποθεσίες)

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| τοποθεσίες | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Συλλογή σημείων (τοποθεσίες) |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Συλλογή ακμών κεντρικής γραμμής |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Κλείνει γεωμετρικά τμήματα σε δακτυλίους εάν χρειάζεται.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Γεωμετρία για κλείσιμο. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Η γεωμετρία μετά το κλείσιμο. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Δημιουργήστε μεσαία σημεία προσθέτοντας ένα νέο σημείο στη μέση σε κάθε τμήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Γεωμετρία για επεξεργασία. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Η γεωμετρία μετά την επεξεργασία. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Διαγράψτε σημεία που είναι πολύ κοντά μεταξύ τους.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Γεωμετρία για διαγραφή των πλησιέστερων σημείων. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | Επιλογές για διαγραφή των πλησιέστερων σημείων. |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Η γεωμετρία μετά τη διαγραφή του πλησιέστερου σημείου. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Εξάγετε τη συλλογή γεωμετρίας από το στρώμα

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Στρώμα εισόδου |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Η συλλογή περιέχει όλες τις γεωμετρίες του στρώματος εισόδου |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Λάβετε το μήκος της κεντρικής γραμμής

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Πολύγωνο για διάγραμμα κεντρικής γραμμής |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Μήκος των ακμών κεντρικής γραμμής |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Λάβετε το μήκος της κεντρικής γραμμής

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| τοποθεσίες | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Συλλογή σημείων (τοποθεσίες) |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double | Μήκος των ακμών κεντρικής γραμμής |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Δημιουργήστε διάγραμμα "Voronoi" για συλλογή σημείων (τοποθεσίες)

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| τοποθεσίες | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Συλλογή σημείων (τοποθεσίες) |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Συλλογή ακμών διαγράμματος Voronoi |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Ταξινομήστε τη συλλογή γεωμετρίας κατά τύπο σε τέσσερις συλλογές (σημείο, γραμμή, πολύγωνο και άλλου τύπου)

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Συλλογή γεωμετριών για σειρά |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Η συλλογή περιέχει τέσσερις συλλογές (σημείο, γραμμή, πολύγωνο και άλλου τύπου) |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Διαγράψτε σημεία που βρίσκονται στο ίδιο τμήμα.

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Γεωμετρία για διαγραφή επιπλέον σημείου |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Επιλογές για διαγραφή επιπλέον σημείου |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Η γεωμετρία μετά τη διαγραφή επιπλέον σημείου |


