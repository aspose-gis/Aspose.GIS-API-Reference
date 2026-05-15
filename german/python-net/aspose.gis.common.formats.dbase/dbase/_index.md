---
title: "DBase Klasse"
type: docs
weight: 10
url: /de/python-net/aspose.gis.common.formats.dbase/dbase/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.dbase](/psd/python-net/aspose.gis.common.formats.dbase/)

**Full Name:** aspose.gis.common.formats.dbase.DBase

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Kodierung | System.Text.Encoding | r |  |
| Felder | System.Collections.Generic.IList<DBaseField> | r |  |
| records_count | long | r |  |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| add_field(name, type, width, precision) |  |
| [add_record()](#add_record__1) |    |
| [create(path, options)](#create_path_options_2) |    |
| [create(path, options)](#create_path_options_3) |    |
| delete_record(record_index) |  |
| [edit(path, options, encoding)](#edit_path_options_encoding_4) |    |
| [is_null(record_index, field_index)](#is_null_record_index_field_index_5) |    |
| [is_record_deleted(record_index)](#is_record_deleted_record_index_6) |    |
| [open(path, encoding)](#open_path_encoding_7) |    |
| [open(path, encoding)](#open_path_encoding_8) |    |
| [read_binary_integer(record_index, field_index)](#read_binary_integer_record_index_field_index_9) |    |
| [read_character(record_index, field_index)](#read_character_record_index_field_index_10) |    |
| [read_date(record_index, field_index, is_ignore_wrong_data)](#read_date_record_index_field_index_is_ignore_wrong_data_11) |    |
| [read_field_value(record_index, field_index)](#read_field_value_record_index_field_index_12) |    |
| [read_integer(record_index, field_index, is_ignore_wrong_data)](#read_integer_record_index_field_index_is_ignore_wrong_data_13) |    |
| [read_integer64(record_index, field_index, is_ignore_wrong_data)](#read_integer64_record_index_field_index_is_ignore_wrong_data_14) |    |
| [read_logical(record_index, field_index, is_ignore_wrong_data)](#read_logical_record_index_field_index_is_ignore_wrong_data_15) |    |
| [read_number(record_index, field_index, is_ignore_wrong_data)](#read_number_record_index_field_index_is_ignore_wrong_data_16) |    |
| [read_raw(record_index, field_index)](#read_raw_record_index_field_index_17) |    |
| write_binary_float(record_index, field_index, value) |  |
| write_binary_integer(record_index, field_index, value) |  |
| write_binary_integer64(record_index, field_index, value) |  |
| write_character(record_index, field_index, value) |  |
| write_date(record_index, field_index, value) |  |
| write_integer(record_index, field_index, value) |  |
| write_integer64(record_index, field_index, value) |  |
| write_logical(record_index, field_index, value) |  |
| write_null(record_index, field_index) |  |
| write_number(record_index, field_index, value) |  |
| write_raw_bytes(record_index, field_index, bytes) |  |


### Method: add_record() {#add_record__1}


```
 add_record() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| long |  |


### Method: create(path, options)  [static] {#create_path_options_2}


```
 create(path, options) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string |  |
| options | [DBaseOptions](/psd/python-net/aspose.gis.common.formats.dbase/dbaseoptions) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DBase](/psd/python-net/aspose.gis.common.formats.dbase/dbase) |  |


### Method: create(path, options)  [static] {#create_path_options_3}


```
 create(path, options) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |
| options | [DBaseOptions](/psd/python-net/aspose.gis.common.formats.dbase/dbaseoptions) |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DBase](/psd/python-net/aspose.gis.common.formats.dbase/dbase) |  |


### Method: edit(path, options, encoding)  [static] {#edit_path_options_encoding_4}


```
 edit(path, options, encoding) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |
| options | [DBaseOptions](/psd/python-net/aspose.gis.common.formats.dbase/dbaseoptions) |  |
| Kodierung | System.Text.Encoding |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DBase](/psd/python-net/aspose.gis.common.formats.dbase/dbase) |  |


### Method: is_null(record_index, field_index) {#is_null_record_index_field_index_5}


```
 is_null(record_index, field_index) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: is_record_deleted(record_index) {#is_record_deleted_record_index_6}


```
 is_record_deleted(record_index) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: open(path, encoding)  [static] {#open_path_encoding_7}


```
 open(path, encoding) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string |  |
| Kodierung | System.Text.Encoding |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DBase](/psd/python-net/aspose.gis.common.formats.dbase/dbase) |  |


### Method: open(path, encoding)  [static] {#open_path_encoding_8}


```
 open(path, encoding) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |
| Kodierung | System.Text.Encoding |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [DBase](/psd/python-net/aspose.gis.common.formats.dbase/dbase) |  |


### Method: read_binary_integer(record_index, field_index) {#read_binary_integer_record_index_field_index_9}


```
 read_binary_integer(record_index, field_index) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int |  |


### Method: read_character(record_index, field_index) {#read_character_record_index_field_index_10}


```
 read_character(record_index, field_index) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string |  |


### Method: read_date(record_index, field_index, is_ignore_wrong_data) {#read_date_record_index_field_index_is_ignore_wrong_data_11}


```
 read_date(record_index, field_index, is_ignore_wrong_data) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |
| is_ignore_wrong_data | bool |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| datetime |  |


### Method: read_field_value(record_index, field_index) {#read_field_value_record_index_field_index_12}


```
 read_field_value(record_index, field_index) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| string |  |


### Method: read_integer(record_index, field_index, is_ignore_wrong_data) {#read_integer_record_index_field_index_is_ignore_wrong_data_13}


```
 read_integer(record_index, field_index, is_ignore_wrong_data) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |
| is_ignore_wrong_data | bool |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| int |  |


### Method: read_integer64(record_index, field_index, is_ignore_wrong_data) {#read_integer64_record_index_field_index_is_ignore_wrong_data_14}


```
 read_integer64(record_index, field_index, is_ignore_wrong_data) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |
| is_ignore_wrong_data | bool |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| long |  |


### Method: read_logical(record_index, field_index, is_ignore_wrong_data) {#read_logical_record_index_field_index_is_ignore_wrong_data_15}


```
 read_logical(record_index, field_index, is_ignore_wrong_data) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |
| is_ignore_wrong_data | bool |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: read_number(record_index, field_index, is_ignore_wrong_data) {#read_number_record_index_field_index_is_ignore_wrong_data_16}


```
 read_number(record_index, field_index, is_ignore_wrong_data) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |
| is_ignore_wrong_data | bool |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| double |  |


### Method: read_raw(record_index, field_index) {#read_raw_record_index_field_index_17}


```
 read_raw(record_index, field_index) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| record_index | long |  |
| field_index | int |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| byte |  |


