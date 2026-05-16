---
title: "SingleStreamPath クラス"
type: docs
weight: 850
url: /ja/python-net/aspose.gis.common/singlestreampath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.SingleStreamPath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [SingleStreamPath(stream)](#SingleStreamPath_stream_1) | SingleStreamPath クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| location | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **説明** |
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

SingleStreamPath クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom |  |

### Method: combine(path) {#combine_path_1}


```
 combine(path) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string |  |

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


### Method: with_location(path) {#with_location_path_6}


```
 with_location(path) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


