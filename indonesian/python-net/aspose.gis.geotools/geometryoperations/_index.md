---
title: "Kelas GeometryOperations"
type: docs
weight: 40
url: /id/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Bangun diagram garis tengah untuk poligon |
| [build_centerline(sites)](#build_centerline_sites_2) | Bangun diagram garis tengah untuk koleksi titik (situs) |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Menutup segmen geometris dalam cincin jika diperlukan. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Buat titik tengah dengan menambahkan titik baru di tengah setiap segmen. |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Hapus titik yang terlalu dekat satu sama lain. |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Ekstrak koleksi geometri dari lapisan |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Dapatkan Panjang garis tengah |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Dapatkan Panjang garis tengah |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Bangun diagram "Voronoi" untuk koleksi titik (situs) |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Urutkan koleksi geometri berdasarkan tipe menjadi empat koleksi (titik, garis, poligon, dan tipe lainnya) |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Hapus titik yang berada pada segmen yang sama. |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Bangun diagram garis tengah untuk poligon

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Poligon untuk diagram garis tengah |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Koleksi tepi garis tengah |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Bangun diagram garis tengah untuk koleksi titik (situs)

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| situs | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Koleksi titik (situs) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Koleksi tepi garis tengah |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Menutup segmen geometris dalam cincin jika diperlukan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri untuk penutupan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri setelah penutupan. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Buat titik tengah dengan menambahkan titik baru di tengah setiap segmen.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri untuk pemrosesan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri setelah pemrosesan. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Hapus titik yang terlalu dekat satu sama lain.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri untuk menghapus titik terdekat. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | Opsi untuk menghapus titik terdekat. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri setelah menghapus titik terdekat. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Ekstrak koleksi geometri dari lapisan

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Lapisan input |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Koleksi berisi semua geometri lapisan input |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Dapatkan Panjang garis tengah

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Poligon untuk diagram garis tengah |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Panjang tepi garis tengah |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Dapatkan Panjang garis tengah

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| situs | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Koleksi titik (situs) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double | Panjang tepi garis tengah |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Bangun diagram "Voronoi" untuk koleksi titik (situs)

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| situs | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Koleksi titik (situs) |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Koleksi tepi diagram Voronoi |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Urutkan koleksi geometri berdasarkan tipe menjadi empat koleksi (titik, garis, poligon, dan tipe lainnya)

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Koleksi geometri untuk urutan |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Koleksi berisi empat koleksi (titik, garis, poligon, dan tipe lainnya) |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Hapus titik yang berada pada segmen yang sama.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri untuk menghapus titik ekstra |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Opsi untuk menghapus titik ekstra |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometri setelah menghapus titik ekstra |


