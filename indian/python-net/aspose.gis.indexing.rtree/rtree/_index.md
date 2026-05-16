---
title: "RTree क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.gis.indexing.rtree/rtree/
---

**Summary:** 

**Module:** [aspose.gis.indexing.rtree](/psd/python-net/aspose.gis.indexing.rtree/)

**Full Name:** aspose.gis.indexing.rtree.RTree

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| is_new | bool | r |  |
## **Methods**
| **नाम** | **विवरण** |
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

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [Coordinate](/psd/python-net/aspose.gis.common/coordinate/) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| list[int] |  |


### Method: open(filename, options)  [static] {#open_filename_options_2}


```
 open(filename, options) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| filename | string |  |
| options | [RTreeOptions](/psd/python-net/aspose.gis.indexing.rtree/rtreeoptions) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: open(path, max_values_per_node)  [static] {#open_path_max_values_per_node_3}


```
 open(path, max_values_per_node) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal/) |  |
| max_values_per_node | इंट |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: open(path, options)  [static] {#open_path_options_4}


```
 open(path, options) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal/) |  |
| options | [RTreeOptions](/psd/python-net/aspose.gis.indexing.rtree/rtreeoptions) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: open_in_memory(max_values_per_node)  [static] {#open_in_memory_max_values_per_node_5}


```
 open_in_memory(max_values_per_node) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| max_values_per_node | इंट |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [RTree](/psd/python-net/aspose.gis.indexing.rtree/rtree) |  |


### Method: where_intersects(search_rectangle) {#where_intersects_search_rectangle_6}


```
 where_intersects(search_rectangle) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| search_rectangle | [BoundingRectangle](/psd/python-net/aspose.gis.common/boundingrectangle/) |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| list[int] |  |


