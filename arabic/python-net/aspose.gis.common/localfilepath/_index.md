---
title: "LocalFilePath فئة"
type: docs
weight: 570
url: /ar/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | يُنشئ مثلاً جديداً من فئة LocalFilePath |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| الموقع | string | r |  |
| فاصل | char | r |  |
## **Methods**
| **Name** | **الوصف** |
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

يُنشئ مثلاً جديداً من فئة LocalFilePath

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| المسار | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| filename | string |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| نوع | الوصف |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| نوع | الوصف |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الوصول | System.IO.FileAccess |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| نوع | الوصف |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


