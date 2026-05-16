---
title: "LocalFilePath क्लास"
type: docs
weight: 570
url: /hi/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | LocalFilePath क्लास का एक नया उदाहरण आरंभ करता है |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| स्थान | string | r |  |
| separator | चर | r |  |
## **Methods**
| **नाम** | **विवरण** |
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

LocalFilePath क्लास का एक नया उदाहरण आरंभ करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| filename | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal) |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| पहुंच | System.IO.FileAccess |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


