---
title: "AbstractPathInternal Класс"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.common/abstractpathinternal/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| location | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [combine(path)](#combine_path_1) |    |
| delete() |  |
| [is_file()](#is_file__2) |    |
| [list_directory()](#list_directory__3) |    |
| [open(access)](#open_access_4) |    |
| [with_extension(new_extension)](#with_extension_new_extension_5) |    |
| [with_location(path)](#with_location_path_6) |    |


### Method: combine(path) {#combine_path_1}


```
 combine(path) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| доступ | System.IO.FileAccess |  |

**Returns**

| Тип | Описание |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(path) {#with_location_path_6}


```
 with_location(path) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


