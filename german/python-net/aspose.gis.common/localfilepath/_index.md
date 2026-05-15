---
title: "LocalFilePath Klasse"
type: docs
weight: 570
url: /de/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | Initialisiert eine neue Instanz der LocalFilePath Klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| Ort | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Beschreibung** |
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

Initialisiert eine neue Instanz der LocalFilePath Klasse

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Dateiname | string |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Typ | Beschreibung |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| Zugriff | System.IO.FileAccess |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


