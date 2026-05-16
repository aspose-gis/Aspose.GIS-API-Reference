---
title: "Classe RTree"
type: docs
weight: 10
url: /it/python-net/aspose.gis.indexing.rtree/rtree/
---

**Summary:** 

**Module:** [aspose.gis.indexing.rtree](/psd/python-net/aspose.gis.indexing.rtree/)

**Full Name:** aspose.gis.indexing.rtree.RTree

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| is_new | bool | r |  |
## **Methods**
| **Name** | **Descrizione** |
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

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| list[int] |  |


### Method: open(filename, options)  [static] {#open_filename_options_2}


```
 open(filename, options) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| filename | string |  |
| options | [RTreeOptions](/psd/python-net/aspose.gis.indexing.rtree/rtreeoptions) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: open(path, max_values_per_node)  [static] {#open_path_max_values_per_node_3}


```
 open(path, max_values_per_node) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal/) |  |
| max_values_per_node | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: open(path, options)  [static] {#open_path_options_4}


```
 open(path, options) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal/) |  |
| options | [RTreeOptions](/psd/python-net/aspose.gis.indexing.rtree/rtreeoptions) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: open_in_memory(max_values_per_node)  [static] {#open_in_memory_max_values_per_node_5}


```
 open_in_memory(max_values_per_node) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| max_values_per_node | int |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: where_intersects(search_rectangle) {#where_intersects_search_rectangle_6}


```
 where_intersects(search_rectangle) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| search_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle/) |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| list[int] |  |


