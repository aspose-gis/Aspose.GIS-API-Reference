---
title: "GeometryOperations Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.gis.geotools/geometryoperations/
---

**Summary:** The geometry operations class provides additional geoprocessing algorithms for geometries.

**Module:** [aspose.gis.geotools](/psd/python-net/aspose.gis.geotools/)

**Full Name:** aspose.gis.geotools.GeometryOperations

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [build_centerline(polygon)](#build_centerline_polygon_1) | Poligon için merkez çizgi diyagramı oluştur |
| [build_centerline(sites)](#build_centerline_sites_2) | Nokta (siteler) koleksiyonu için merkez çizgi diyagramı oluştur |
| [close_linear_ring(geometry)](#close_linear_ring_geometry_3) | Gerekirse halkalardaki geometrik segmentleri kapatır. |
| [create_midpoints(geometry)](#create_midpoints_geometry_4) | Her segmente ortada yeni bir nokta ekleyerek orta noktalar oluştur |
| [delete_near_points(geometry, options)](#delete_near_points_geometry_options_5) | Birbirine çok yakın olan noktaları sil |
| [extract_geometry_collection(layer)](#extract_geometry_collection_layer_6) | Katmandan geometri koleksiyonunu çıkar |
| [get_centerline_length(polygon)](#get_centerline_length_polygon_7) | Merkez çizgi uzunluğunu al |
| [get_centerline_length(sites)](#get_centerline_length_sites_8) | Merkez çizgi uzunluğunu al |
| [make_voronoi_graph(sites)](#make_voronoi_graph_sites_9) | Nokta (siteler) koleksiyonu için "Voronoi" diyagramı oluştur |
| [order_geometry_collection(geometry)](#order_geometry_collection_geometry_10) | Geometri koleksiyonunu tipe göre dört koleksiyona ayır (nokta, çizgi, poligon ve diğer tip). |
| [simplify_segments(geometry, options)](#simplify_segments_geometry_options_11) | Aynı segment üzerinde bulunan noktaları sil |


### Method: build_centerline(polygon)  [static] {#build_centerline_polygon_1}


```
 build_centerline(polygon) 
```

Poligon için merkez çizgi diyagramı oluştur

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Merkez çizgi diyagramı için poligon |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Merkez çizgi kenarlarının koleksiyonu |


### Method: build_centerline(sites)  [static] {#build_centerline_sites_2}


```
 build_centerline(sites) 
```

Nokta (siteler) koleksiyonu için merkez çizgi diyagramı oluştur

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| siteler | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Nokta (siteler) koleksiyonu |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Merkez çizgi kenarlarının koleksiyonu |


### Method: close_linear_ring(geometry)  [static] {#close_linear_ring_geometry_3}


```
 close_linear_ring(geometry) 
```

Gerekirse halkalardaki geometrik segmentleri kapatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Kapatma için geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Kapatma sonrası geometri. |


### Method: create_midpoints(geometry)  [static] {#create_midpoints_geometry_4}


```
 create_midpoints(geometry) 
```

Her segmente ortada yeni bir nokta ekleyerek orta noktalar oluştur

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | İşleme için geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | İşleme sonrasındaki geometri. |


### Method: delete_near_points(geometry, options)  [static] {#delete_near_points_geometry_options_5}


```
 delete_near_points(geometry, options) 
```

Birbirine çok yakın olan noktaları sil

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | En yakın noktaları silmek için geometri. |
| options | [NearPointsCleanerOptions](/psd/python-net/aspose.gis.geotools/nearpointscleaneroptions) | En yakın noktaları silme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | En yakın nokta silindikten sonraki geometri. |


### Method: extract_geometry_collection(layer)  [static] {#extract_geometry_collection_layer_6}


```
 extract_geometry_collection(layer) 
```

Katmandan geometri koleksiyonunu çıkar

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Girdi katmanı |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Koleksiyon, girdi katmanının tüm geometrilerini içerir. |


### Method: get_centerline_length(polygon)  [static] {#get_centerline_length_polygon_7}


```
 get_centerline_length(polygon) 
```

Merkez çizgi uzunluğunu al

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| polygon | [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Merkez çizgi diyagramı için poligon |

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Merkez hattı kenarlarının uzunluğu |


### Method: get_centerline_length(sites)  [static] {#get_centerline_length_sites_8}


```
 get_centerline_length(sites) 
```

Merkez çizgi uzunluğunu al

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| siteler | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.Point> | Nokta (siteler) koleksiyonu |

**Returns**

| Tür | Açıklama |
| :- | :- |
| double | Merkez hattı kenarlarının uzunluğu |


### Method: make_voronoi_graph(sites)  [static] {#make_voronoi_graph_sites_9}


```
 make_voronoi_graph(sites) 
```

Nokta (siteler) koleksiyonu için "Voronoi" diyagramı oluştur

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| siteler | System.Collections.Generic.IEnumerable<Aspose.Gis.Geometries.IPoint> | Nokta (siteler) koleksiyonu |

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.List<Aspose.Gis.Geometries.LineString> | Voronoi diyagramının kenarları koleksiyonu |


### Method: order_geometry_collection(geometry)  [static] {#order_geometry_collection_geometry_10}


```
 order_geometry_collection(geometry) 
```

Geometri koleksiyonunu tipe göre dört koleksiyona ayır (nokta, çizgi, poligon ve diğer tip).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Sıralama için geometri koleksiyonu |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Koleksiyon, dört koleksiyon içerir (nokta, çizgi, çokgen ve diğer tip). |


### Method: simplify_segments(geometry, options)  [static] {#simplify_segments_geometry_options_11}


```
 simplify_segments(geometry, options) 
```

Aynı segment üzerinde bulunan noktaları sil

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Ekstra noktayı silmek için geometri. |
| options | [SimplifySegmentsOptions](/psd/python-net/aspose.gis.geotools/simplifysegmentsoptions) | Ekstra nokta silme seçenekleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Ekstra nokta silindikten sonraki geometri. |


