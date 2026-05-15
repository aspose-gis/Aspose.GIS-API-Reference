---
title: "KmlGroundOverlayInfo 类"
type: docs
weight: 20
url: /zh/python-net/aspose.gis.formats.kml.specificfields/kmlgroundoverlayinfo/
---

**Summary:** Specifies object from Kml 'GroundOverlay' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlGroundOverlayInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | 获取子节点。 |
| draw_order | double | r/w | DrawOrder 的 'GroundOverlay' 节点。 |
| icon | [IconInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/iconinfo) | r/w | IconPath 的 'GroundOverlay' 节点。 |
| lat_lon_box | [KmlLatLonBox](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllatlonbox) | r/w | 指定来自 Kml 'LatLonAltBox' 节点的对象。 |
| 名称 | string | r/w | Ground Overlay 的名称 |
| name_without_prefix | string | r | 获取没有前缀的名称。 |
| node_name | string | r/w | 获取或设置名称。 |
| node_value | string | r/w | 获取或设置值。 |
| 前缀 | string | r | 获取前缀。 |
| visibility | bool | r/w | Ground Overlay 的可见性 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | 添加子节点。 |
| [as_bool()](#as_bool__2) | 返回转换为 bool 的值 |
| [as_double()](#as_double__3) | 返回转换为 double 的值。 |
| [as_int()](#as_int__4) | 返回转换为 int 的值。 |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | 按名称查找 XML 节点 |
| [get_node_by_name(name)](#get_node_by_name_name_6) | 通过名称获取节点。请注意，此方法将返回找到的第一个 Node。<br/>无论在何层级找到都无关紧要。 |
| [get_node_content()](#get_node_content__7) | 获取节点的内容。 |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | 获取具有指定名称的所有节点。<br/>无论在何层级找到都无关紧要。 |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

添加子节点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | 子节点。 |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

返回转换为 bool 的值

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 节点的 bool 值 |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

返回转换为 double 的值。

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 节点的 double 值 |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

返回转换为 int 的值。

**Returns**

| 类型 | 描述 |
| :- | :- |
| int | 节点的 int 值 |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

按名称查找 XML 节点

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 节点的名称 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | 按名称的 XML 节点数组 |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

通过名称获取节点。请注意，此方法将返回找到的第一个 Node。<br/>无论在何层级找到都无关紧要。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 要查找的节点名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | 使用 NodeLink API 找到的节点 |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

获取节点的内容。

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 节点的内容 |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

获取具有指定名称的所有节点。<br/>无论在何层级找到都无关紧要。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 这些名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | 找到的节点数组。 |


