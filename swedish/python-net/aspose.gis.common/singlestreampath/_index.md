---
title: "SingleStreamPath-klass"
type: docs
weight: 850
url: /sv/python-net/aspose.gis.common/singlestreampath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.SingleStreamPath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [SingleStreamPath(stream)](#SingleStreamPath_stream_1) | Initierar en ny instans av SingleStreamPath-klassen |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| plats | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Beskrivning** |
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

Initierar en ny instans av SingleStreamPath-klassen

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| ström | _io.BufferedRandom |  |

### Method: combine(path) {#combine_path_1}


```
 combine(path) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Typ | Beskrivning |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| åtkomst | System.IO.FileAccess |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(path) {#with_location_path_6}


```
 with_location(path) 
```

  

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string |  |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


