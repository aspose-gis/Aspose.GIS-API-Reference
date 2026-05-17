---
title: "LocalFilePath Sınıf"
type: docs
weight: 570
url: /tr/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | LocalFilePath sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| konum | string | r |  |
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

LocalFilePath sınıfının yeni bir örneğini başlatır

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| filename | string |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| erişim | System.IO.FileAccess |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


