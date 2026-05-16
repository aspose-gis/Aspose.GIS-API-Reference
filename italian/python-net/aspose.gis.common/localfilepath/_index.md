---
title: "LocalFilePath Classe"
type: docs
weight: 570
url: /it/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | Inizializza una nuova istanza della classe LocalFilePath |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| posizione | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Descrizione** |
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

Inizializza una nuova istanza della classe LocalFilePath

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| filename | string |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Tipo | Descrizione |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| accesso | System.IO.FileAccess |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


