---
title: "SingleStreamPath-klasse"
type: docs
weight: 850
url: /nl/python-net/aspose.gis.common/singlestreampath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.SingleStreamPath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [SingleStreamPath(stream)](#SingleStreamPath_stream_1) | Initialiseert een nieuwe instantie van de SingleStreamPath-klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| locatie | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [combine(path)](#combine_path_1) |    |
| delete() |  |
| [is_file()](#is_file__2) |    |
| [list_directory()](#list_directory__3) |    |
| [open(access)](#open_access_4) |    |
| [with_extension(new_extension)](#with_extension_new_extension_5) |    |
| [with_location(path)](#with_location_path_6) |    |


### Constructor: SingleStreamPath(stream) {#SingleStreamPath_stream_1}


```
 SingleStreamPath(stream) 
```

Initialiseert een nieuwe instantie van de SingleStreamPath-klasse

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| stroom | _io.BufferedRandom |  |

### Method: combine(path) {#combine_path_1}


```
 combine(path) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Type | Beschrijving |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| toegang | System.IO.FileAccess |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(path) {#with_location_path_6}


```
 with_location(path) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


