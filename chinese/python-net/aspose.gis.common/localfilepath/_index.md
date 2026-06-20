---
title: "LocalFilePath 类"
type: docs
weight: 570
url: /zh/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | 初始化 LocalFilePath 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| location | string | r |  |
| separator | 字符 | r |  |
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

初始化 LocalFilePath 类的新实例

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| filename | string |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 访问 | System.IO.FileAccess |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


