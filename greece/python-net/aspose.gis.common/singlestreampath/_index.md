---
title: "SingleStreamPath Κλάση"
type: docs
weight: 850
url: /el/python-net/aspose.gis.common/singlestreampath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.SingleStreamPath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SingleStreamPath(stream)](#SingleStreamPath_stream_1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SingleStreamPath |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| τοποθεσία | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Description** |
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

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης SingleStreamPath

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| ροή | _io.BufferedRandom |  |

### Method: combine(path) {#combine_path_1}


```
 combine(path) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| πρόσβαση | System.IO.FileAccess |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(path) {#with_location_path_6}


```
 with_location(path) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


