---
title: "SingleStreamPath 클래스"
type: docs
weight: 850
url: /ko/python-net/aspose.gis.common/singlestreampath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.SingleStreamPath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SingleStreamPath(stream)](#SingleStreamPath_stream_1) | SingleStreamPath 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| location | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Description** |
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

SingleStreamPath 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom |  |

### Method: combine(path) {#combine_path_1}


```
 combine(path) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 액세스 | System.IO.FileAccess |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(path) {#with_location_path_6}


```
 with_location(path) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


