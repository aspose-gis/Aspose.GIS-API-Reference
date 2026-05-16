---
title: "LocalFilePath Kelas"
type: docs
weight: 570
url: /id/python-net/aspose.gis.common/localfilepath/
---

**Summary:** 

**Module:** [aspose.gis.common](/psd/python-net/aspose.gis.common/)

**Full Name:** aspose.gis.common.LocalFilePath

**Inheritance:** AbstractPathInternal

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LocalFilePath(path)](#LocalFilePath_path_1) | Menginisialisasi sebuah instance baru dari kelas LocalFilePath |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| lokasi | string | r |  |
| separator | char | r |  |
## **Methods**
| **Name** | **Deskripsi** |
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

Menginisialisasi sebuah instance baru dari kelas LocalFilePath

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string |  |

### Method: combine(filename) {#combine_filename_1}


```
 combine(filename) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| filename | string |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: is_file() {#is_file__2}


```
 is_file() 
```

  

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| bool |  |


### Method: list_directory() {#list_directory__3}


```
 list_directory() 
```

  

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPathInternal> |  |


### Method: open(access) {#open_access_4}


```
 open(access) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| akses | System.IO.FileAccess |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| _io.BufferedRandom |  |


### Method: with_extension(new_extension) {#with_extension_new_extension_5}


```
 with_extension(new_extension) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_extension | string |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


### Method: with_location(new_location) {#with_location_new_location_6}


```
 with_location(new_location) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| new_location | string |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |


