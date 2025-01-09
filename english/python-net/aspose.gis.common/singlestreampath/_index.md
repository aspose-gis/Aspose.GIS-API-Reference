---
title: SingleStreamPath Class
type: docs
weight: 850
url: /python-net/aspose.gis.common/singlestreampath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.SingleStreamPath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 24.12.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SingleStreamPath(stream)](#SingleStreamPath_stream_1) | Initializes a new instance of the SingleStreamPath class |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| location | string | r |    |
| separator | char | r |    |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [combine(path)](#combine_path_1) |    |
| delete() |    |
| [is_file()](#is_file__2) |    |
| [list_directory()](#list_directory__3) |    |
| [open(access)](#open_access_4) |    |
| [with_extension(new_extension)](#with_extension_new_extension_5) |    |
| [with_location(path)](#with_location_path_6) |    |


### Constructor: SingleStreamPath(stream) {#SingleStreamPath_stream_1}


```
 SingleStreamPath(stream) 
```

Initializes a new instance of the SingleStreamPath class

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| stream | _io.BufferedRandom |  |

### Method: combine(path) {#combine_path_1}


```
 combine(path) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string |  |

**Returns**

| Type | Description |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Type | Description |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Type | Description |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| access | System.IO.FileAccess |  |

**Returns**

| Type | Description |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Type | Description |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(path) {#with_location_path_6}


```
 with_location(path) 
```

  

**Parameters:**

| Parameter | Type | Description |
| :- | :- | :- |
| path | string |  |

**Returns**

| Type | Description |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


