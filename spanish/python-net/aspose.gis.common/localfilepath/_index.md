---
title: "LocalFilePath Clase"
type: docs
weight: 570
url: /es/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | Inicializa una nueva instancia de la clase LocalFilePath |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| ubicación | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Descripción** |
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

Inicializa una nueva instancia de la clase LocalFilePath

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| path | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| filename | string |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Tipo | Descripción |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| acceso | System.IO.FileAccess |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


