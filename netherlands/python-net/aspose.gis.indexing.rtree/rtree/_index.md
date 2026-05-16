---
title: "RTree Klasse"
type: docs
weight: 10
url: /nl/python-net/aspose.gis.indexing.rtree/rtree/
---

**Summary:** 

**Module:** [aspose.gis.indexing.rtree](/psd/python-net/aspose.gis.indexing.rtree/)

**Full Name:** aspose.gis.indexing.rtree.RTree

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| is_new | bool | r |  |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| insert(data_extent, data_id) |  |
| [nearest_candidate_to(point)](#nearest_candidate_to_point_1) |    |
| [open(filename, options)](#open_filename_options_2) |    |
| [open(path, max_values_per_node)](#open_path_max_values_per_node_3) |    |
| [open(path, options)](#open_path_options_4) |    |
| [open_in_memory(max_values_per_node)](#open_in_memory_max_values_per_node_5) |    |
| [where_intersects(search_rectangle)](#where_intersects_search_rectangle_6) |    |


### Method: nearest_candidate_to(point) {#nearest_candidate_to_point_1}


```
 nearest_candidate_to(point) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| list[int] |  |


### Method: open(filename, options)  [static] {#open_filename_options_2}


```
 open(filename, options) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| filename | string |  |
| options | [RTreeOptions](/psd/python-net/aspose.gis.indexing.rtree/rtreeoptions) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: open(path, max_values_per_node)  [static] {#open_path_max_values_per_node_3}


```
 open(path, max_values_per_node) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal/) |  |
| max_values_per_node | int |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: open(path, options)  [static] {#open_path_options_4}


```
 open(path, options) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal/) |  |
| options | [RTreeOptions](/psd/python-net/aspose.gis.indexing.rtree/rtreeoptions) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: open_in_memory(max_values_per_node)  [static] {#open_in_memory_max_values_per_node_5}


```
 open_in_memory(max_values_per_node) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| max_values_per_node | int |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: where_intersects(search_rectangle) {#where_intersects_search_rectangle_6}


```
 where_intersects(search_rectangle) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| search_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle/) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| list[int] |  |


