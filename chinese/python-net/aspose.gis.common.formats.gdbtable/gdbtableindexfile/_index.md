---
title: "GdbTableIndexFile 类"
type: docs
weight: 150
url: /zh/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.gdbtable](/psd/python-net/aspose.gis.common.formats.gdbtable/)

**Full Name:** aspose.gis.common.formats.gdbtable.GdbTableIndexFile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| blocks_count | 整数 | r |  |
| last_row_id | 整数 | r |  |
| next_row_id | 整数 | r |  |
| number_of_offsets_in_block | 整数 | r |  |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(offset)](#add_offset_1) |    |
| [create(path)](#create_path_2) |    |
| [create(path)](#create_path_3) |    |
| 删除(row_id) |  |
| [get_offset(row_id)](#get_offset_row_id_4) |    |
| [is_block_present(block_number)](#is_block_present_block_number_5) |    |
| [open(path)](#open_path_6) |    |
| [open(path)](#open_path_7) |    |


### Method: add(offset) {#add_offset_1}


```
 add(offset) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 偏移量 | 长整数 |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| 整数 |  |


### Method: create(path)  [static] {#create_path_2}


```
 create(path) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GdbTableIndexFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile) |  |


### Method: create(path)  [static] {#create_path_3}


```
 create(path) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GdbTableIndexFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile) |  |


### Method: get_offset(row_id) {#get_offset_row_id_4}


```
 get_offset(row_id) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| row_id | 整数 |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| 长整数 |  |


### Method: is_block_present(block_number) {#is_block_present_block_number_5}


```
 is_block_present(block_number) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| block_number | 整数 |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: open(path)  [static] {#open_path_6}


```
 open(path) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GdbTableIndexFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile) |  |


### Method: open(path)  [static] {#open_path_7}


```
 open(path) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [GdbTableIndexFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile) |  |


