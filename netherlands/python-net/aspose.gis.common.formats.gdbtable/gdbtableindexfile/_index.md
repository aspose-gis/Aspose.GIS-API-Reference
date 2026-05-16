---
title: "GdbTableIndexFile Klasse"
type: docs
weight: 150
url: /nl/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.gdbtable](/psd/python-net/aspose.gis.common.formats.gdbtable/)

**Full Name:** aspose.gis.common.formats.gdbtable.GdbTableIndexFile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| blocks_count | int | r |  |
| last_row_id | int | r |  |
| next_row_id | int | r |  |
| number_of_offsets_in_block | int | r |  |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add(offset)](#add_offset_1) |    |
| [create(path)](#create_path_2) |    |
| [create(path)](#create_path_3) |    |
| delete(row_id) |  |
| [get_offset(row_id)](#get_offset_row_id_4) |    |
| [is_block_present(block_number)](#is_block_present_block_number_5) |    |
| [open(path)](#open_path_6) |    |
| [open(path)](#open_path_7) |    |


### Method: add(offset) {#add_offset_1}


```
 add(offset) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| offset | long |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int |  |


### Method: create(path)  [static] {#create_path_2}


```
 create(path) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GdbTableIndexFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile) |  |


### Method: create(path)  [static] {#create_path_3}


```
 create(path) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GdbTableIndexFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile) |  |


### Method: get_offset(row_id) {#get_offset_row_id_4}


```
 get_offset(row_id) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| row_id | int |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| long |  |


### Method: is_block_present(block_number) {#is_block_present_block_number_5}


```
 is_block_present(block_number) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| block_number | int |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool |  |


### Method: open(path)  [static] {#open_path_6}


```
 open(path) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GdbTableIndexFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile) |  |


### Method: open(path)  [static] {#open_path_7}


```
 open(path) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [GdbTableIndexFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableindexfile) |  |


