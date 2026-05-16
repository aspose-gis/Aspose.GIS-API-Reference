---
title: "NodeLink クラス"
type: docs
weight: 2800
url: /ja/python-net/aspose.gis/nodelink/
---

**Summary:** Node-based link to the parts of resources

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | 子要素を取得します。 |
| node_name | string | 読み/書き | 名前を取得または設定します。 |
| node_value | string | 読み/書き | 値を取得または設定します。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | 子要素を追加します。 |
| [as_bool()](#as_bool__2) | bool にキャストした値を返します |
| [as_double()](#as_double__3) | double にキャストした値を返します。 |
| [as_int()](#as_int__4) | int にキャストされた値を返します。 |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | 名前でノードを検索します。 |
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

名前でノードを検索します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | ノードの名前 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | 名前でフォーマットされたノードの配列 |


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


