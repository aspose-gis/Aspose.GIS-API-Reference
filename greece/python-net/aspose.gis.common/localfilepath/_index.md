---
title: "LocalFilePath Κλάση"
type: docs
weight: 570
url: /el/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης LocalFilePath |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| τοποθεσία | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [combine(filename)](#combine_filename_1) |    |
| delete() |  |
| [is_file()](#is_file__2) |    |
| [list_directory()](#list_directory__3) |    |
| [open(access)](#open_access_4) |    |
| [with_extension(new_extension)](#with_extension_new_extension_5) |    |
| [with_location(new_location)](#with_location_new_location_6) |    |


### Constructor: LocalFilePath(path) {#LocalFilePath_path_1}


```
 LocalFilePath(path) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης LocalFilePath

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| filename | string |  |

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


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


