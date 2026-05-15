---
title: "GdbTableFile Κλάση"
type: docs
weight: 140
url: /el/python-net/aspose.gis.common.formats.gdbtable/gdbtablefile/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.gdbtable](/psd/python-net/aspose.gis.common.formats.gdbtable/)

**Full Name:** aspose.gis.common.formats.gdbtable.GdbTableFile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| count | int | r |  |
| πεδία | System.Collections.Generic.IReadOnlyList<GdbFieldDescription> | r |  |
| gdb_table_version | [GdbTableVersion](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableversion) | r |    |
| is_dirty | bool | r |  |
| next_row_id | int | r |  |
| object_id_field | [GdbFieldDescription](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbfielddescription) | r |    |
| shape_field | [GdbShapeFieldDescription](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbshapefielddescription) | r |    |
| shape_type | [GdbTableShapeType](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtableshapetype) | r/w |    |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| add_field(field) |  |
| [add_row(row)](#add_row_row_1) |    |
| [create(path)](#create_path_2) |    |
| [create(path)](#create_path_3) |    |
| [create_row()](#create_row__4) |    |
| delete_row(row_id) |  |
| delete_row_at(row_index) |  |
| [has_field(name)](#has_field_name_5) |    |
| [is_valid_and_unqiue_field_name(name, error)](#is_valid_and_unqiue_field_name_name_error_6) |    |
| [is_valid_field_name(name, error)](#is_valid_field_name_name_error_7) |    |
| [open(path)](#open_path_8) |    |
| [open(path)](#open_path_9) |    |
| [read_row(row_id)](#read_row_row_id_10) |    |
| [read_row_at(row_index)](#read_row_at_row_index_11) |    |
| update_row(row, row_index) |  |


### Method: add_row(row) {#add_row_row_1}


```
 add_row(row) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| row | [GdbTableRowWriter](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtablerowwriter) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int |  |


### Method: create(path)  [static] {#create_path_2}


```
 create(path) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GdbTableFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtablefile) |  |


### Method: create(path)  [static] {#create_path_3}


```
 create(path) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GdbTableFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtablefile) |  |


### Method: create_row() {#create_row__4}


```
 create_row() 
```

  

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GdbTableRowWriter](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtablerowwriter) |  |


### Method: has_field(name) {#has_field_name_5}


```
 has_field(name) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool |  |


### Method: is_valid_and_unqiue_field_name(name, error) {#is_valid_and_unqiue_field_name_name_error_6}


```
 is_valid_and_unqiue_field_name(name, error) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string |  |
| σφάλμα | Συμβολοσειρά |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool |  |


### Method: is_valid_field_name(name, error)  [static] {#is_valid_field_name_name_error_7}


```
 is_valid_field_name(name, error) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| όνομα | string |  |
| σφάλμα | Συμβολοσειρά |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool |  |


### Method: open(path)  [static] {#open_path_8}


```
 open(path) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GdbTableFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtablefile) |  |


### Method: open(path)  [static] {#open_path_9}


```
 open(path) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GdbTableFile](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtablefile) |  |


### Method: read_row(row_id) {#read_row_row_id_10}


```
 read_row(row_id) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| row_id | int |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GdbTableRowReader](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtablerowreader) |  |


### Method: read_row_at(row_index) {#read_row_at_row_index_11}


```
 read_row_at(row_index) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| row_index | int |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [GdbTableRowReader](/psd/python-net/aspose.gis.common.formats.gdbtable/gdbtablerowreader) |  |


