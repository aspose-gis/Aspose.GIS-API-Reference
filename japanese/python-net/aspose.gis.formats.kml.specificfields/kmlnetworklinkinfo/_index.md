---
title: "KmlNetworkLinkInfo クラス"
type: docs
weight: 60
url: /ja/python-net/aspose.gis.formats.kml.specificfields/kmlnetworklinkinfo/
---

**Summary:** Specifies object from Kml 'NetworkLink' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlNetworkLinkInfo

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | 子要素を取得します。 |
| link | [LinkInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/linkinfo) | r/w |    |
| name_without_prefix | string | r | プレフィックスなしの名前を取得します。 |
| node_name | string | 読み/書き | 名前を取得または設定します。 |
| node_value | string | 読み/書き | 値を取得または設定します。 |
| プレフィックス | string | r | プレフィックスを取得します。 |
| region | [KmlRegionInfo](/psd/python-net/aspose.gis.formats.kml.specificfields/kmlregioninfo) | r/w |    |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | 子要素を追加します。 |
| [as_bool()](#as_bool__2) | bool にキャストした値を返します |
| [as_double()](#as_double__3) | double にキャストした値を返します。 |
| [as_int()](#as_int__4) | int にキャストされた値を返します。 |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | 名前で XML ノードを検索します |
| [get_node_by_name(name)](#get_node_by_name_name_6) | 名前でノードを取得します。注意してください、このメソッドは最初に見つかった Node を返します。<br/>            見つかるレベルは関係ありません |
| [get_node_content()](#get_node_content__7) | ノードの内容を取得します。 |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | 指定された名前のすべてのノードを取得します。 <br/>            見つかるレベルは関係ありません |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

子要素を追加します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | 子要素です。 |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

bool にキャストした値を返します

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | ノードの bool 値 |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

double にキャストした値を返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| double | ノードの double 値 |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

int にキャストされた値を返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| int | ノードの int 値 |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

名前で XML ノードを検索します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | ノードの名前 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | 名前で取得する XML ノードの配列 |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

名前でノードを取得します。注意してください、このメソッドは最初に見つかった Node を返します。<br/>            見つかるレベルは関係ありません

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 見つけたいノードの名前です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | NodeLink API で見つかったノード |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

ノードの内容を取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| string | ノードの内容 |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

指定された名前のすべてのノードを取得します。 <br/>            見つかるレベルは関係ありません

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 名前です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | 見つかったノードの配列です。 |


