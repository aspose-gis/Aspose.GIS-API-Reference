---
title: "LocalFilePath クラス"
type: docs
weight: 570
url: /ja/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | LocalFilePath クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| location | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **説明** |
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

LocalFilePath クラスの新しいインスタンスを初期化します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| filename | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| 型 | 説明 |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| アクセス | System.IO.FileAccess |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


