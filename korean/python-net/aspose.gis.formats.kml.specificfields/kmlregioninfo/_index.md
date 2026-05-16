---
title: "KmlRegionInfo 클래스"
type: docs
weight: 70
url: /ko/python-net/aspose.gis.formats.kml.specificfields/kmlregioninfo/
---

**Summary:** Specifies object from Kml 'Region' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlRegionInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | 자식들을 가져옵니다. |
| id | string | r/w | Id의 'Region' 노드. |
| lat_lon_alt_box | [KmlLatLonAltBox](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllatlonaltbox) | r/w | Kml 'LatLonAltBox' 노드에서 객체를 지정합니다. |
| lod | [KmlLodSettings](/psd/python-net/aspose.gis.formats.kml.specificfields/kmllodsettings) | r/w | Kml 'Lod' 노드에서 객체를 지정합니다. |
| name_without_prefix | string | r | 접두사 없이 이름을 가져옵니다. |
| node_name | string | r/w | 이름을 가져오거나 설정합니다. |
| node_value | string | r/w | 값을 가져오거나 설정합니다. |
| 접두사 | string | r | 접두사를 가져옵니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | 자식을 추가합니다. |
| [as_bool()](#as_bool__2) | 값을 bool로 변환하여 반환합니다. |
| [as_double()](#as_double__3) | 값을 double로 변환하여 반환합니다. |
| [as_int()](#as_int__4) | 정수형으로 형변환된 값을 반환합니다. |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | 이름으로 XML 노드를 찾습니다. |
| [get_node_by_name(name)](#get_node_by_name_name_6) | 이름으로 노드를 가져옵니다. 이 메서드는 첫 번째로 발견된 Node를 반환한다는 점에 유의하십시오.<br/>            레벨에 관계없이 |
| [get_node_content()](#get_node_content__7) | 노드의 내용을 가져옵니다. |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | 지정된 이름을 가진 모든 노드를 가져옵니다. <br/>            레벨에 관계없이 |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

자식을 추가합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | 자식. |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

값을 bool로 변환하여 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 노드의 bool 값 |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

값을 double로 변환하여 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| double | 노드의 double 값 |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

정수형으로 형변환된 값을 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| int | 노드의 int 값 |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

이름으로 XML 노드를 찾습니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 노드의 이름 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | 이름별 XML 노드 배열 |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

이름으로 노드를 가져옵니다. 이 메서드는 첫 번째로 발견된 Node를 반환한다는 점에 유의하십시오.<br/>            레벨에 관계없이

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름 | string | 찾고자 하는 노드의 이름입니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | NodeLink API를 사용해 찾은 노드 |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

노드의 내용을 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 노드의 내용 |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

지정된 이름을 가진 모든 노드를 가져옵니다. <br/>            레벨에 관계없이

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 이름들 | string | 이름들. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | 찾은 노드들의 배열. |


