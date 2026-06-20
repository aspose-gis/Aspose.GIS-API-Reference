---
title: "KmlLatLonAltBox 类"
type: docs
weight: 30
url: /zh/python-net/aspose.gis.formats.kml.specificfields/kmllatlonaltbox/
---

**Summary:** KmlLatLonAltBox Node Wrapper

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlLatLonAltBox

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | 获取子节点。 |
| 东 | double | r/w | ‘LatLonBox’ 节点的东侧。 |
| max_altitude | Nullable<double> | r/w | ‘LatLonBox’ 节点的 MaxAltitude。 |
| min_altitude | Nullable<double> | r/w | ‘LatLonBox’ 节点的 MinAltitude。 |
| name_without_prefix | string | r | 获取不带前缀的名称。 |
| node_name | string | r/w | 获取或设置名称。 |
| node_value | string | r/w | 获取或设置值。 |
| 北 | double | r/w | ‘LatLonBox’ 节点的北侧。 |
| 前缀 | string | r | 获取前缀。 |
| 旋转 | Nullable<double> | r/w | ‘LatLonBox’ 节点的 Rotation。 |
| 南 | double | r/w | ‘LatLonBox’ 节点的南侧。 |
| 西 | double | r/w | ‘LatLonBox’ 节点的西侧。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | 添加子节点。 |
| [as_bool()](#as_bool__2) | 返回转换为布尔值的结果 |
| [as_double()](#as_double__3) | 返回转换为 double 的结果。 |
| [as_int()](#as_int__4) | 返回转换为 int 的值。 |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | 按名称查找 XML 节点 |
| [get_node_by_name(name)](#get_node_by_name_name_6) | 按名称获取节点。请注意，此方法将返回找到的第一个 Node。<br/>            无论在何层级被找到都不影响。 |
| [get_node_content()](#get_node_content__7) | 获取节点的内容。 |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | 获取所有具有指定名称的节点。<br/>            无论在何层级被找到都不影响。 |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

添加子节点。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | 子项。 |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

返回转换为布尔值的结果

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 节点的布尔值 |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

返回转换为 double 的结果。

**Returns**

| 类型 | 描述 |
| :- | :- |
| double | 节点的双精度值 |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

返回转换为 int 的值。

**Returns**

| 类型 | 描述 |
| :- | :- |
| 整数 | 节点的整数值 |


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

按名称获取节点。请注意，此方法将返回找到的第一个 Node。<br/>            无论在何层级被找到都不影响。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 您想要查找的节点名称。 |

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

获取所有具有指定名称的节点。<br/>            无论在何层级被找到都不影响。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 名称 | string | 名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | 找到的节点数组。 |


