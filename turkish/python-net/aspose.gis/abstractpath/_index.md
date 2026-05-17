---
title: "AbstractPath Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.gis/abstractpath/
---

**Summary:** An <c>AbstractPath</c> is a base class for classes that specify a unique location in an environment similar to a filesystem,<br/>            like a local filesystem, a remote file storage or a ZIP archive, among others.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| konum | string | r | Bu <c>AbstractPath</c> konumunun dize temsili alınır. |
| separator | char | r | Bir dizin seviyesini ayırmak için kullanılan ayırıcı karakteri alır [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) dizesi. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [combine(location)](#combine_location_1) | Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) öğesini belirtilen yol bileşenleriyle birleştirir. |
| delete() | Bu yolun işaret ettiği dosyayı siler. |
| [from_local_path(path)](#from_local_path_path_2) | Yerel dosya sisteminde bir konumu temsil eden bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) oluşturur. |
| [from_stream(stream)](#from_stream_stream_3) | Bir akıştan bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) oluşturur. |
| [get_extension()](#get_extension__4) | Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) uzantısını döndürür. |
| [get_file_name()](#get_file_name__5) | Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) dosya adını ve uzantısını döndürür. |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) dosya adını uzantısız olarak döndürür. |
| [is_file()](#is_file__7) | Bu yolun okuma için açılabilecek mevcut bir dosyaya işaret edip etmediğini gösteren bir değer alınır. |
| [list_directory()](#list_directory__8) | Bu <c>AbstractPath</c> bir dizinse, içinde bulunan yolları döndürür. |
| [open(access)](#open_access_9) | Bu <c>AbstractPath</c>'i bir dosya olarak açar. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | Dosya uzantısı belirtilen değere değiştirilen yeni bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) döndürür. |


### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) öğesini belirtilen yol bileşenleriyle birleştirir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| location | string | Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) öğesine eklemek için bir yol bileşeni. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Yeni bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) işaret eden bir [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) ki bu, bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) konumları ile<br/>            argümanın bir kombinasyonudur. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

Yerel dosya sisteminde bir konumu temsil eden bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Yerel dosya sistemindeki bir yol, örneğin <c>"C:\\file.shp"</c> veya <c>"D:\\directory\\"</c>. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | <paramref name="path" /> tarafından tanımlanan konumu temsil eden bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

Bir akıştan bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| stream | _io.BufferedRandom | [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) oluşturmak için bir akış. <c>Aspose.GIS</c> akışı kapatmaz. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Belirtilen akışı içeriği olarak kullanan bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) örneği. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) uzantısını döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) uzantısı (nokta "." dahil) veya [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) uzantısı yoksa boş bir dize. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) dosya adını ve uzantısını döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bu [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) içindeki son [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) karakterinden sonraki karakterler. Eğer<br/>            son karakter [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) ise, boş bir dize döndürülür. Eğer [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) içinde [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) karakteri yoksa, [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) kendisi döndürülür. |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

Bu [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) dosya adını uzantısız olarak döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) tarafından döndürülen dize, son nokta ve ardından gelen tüm karakterler çıkarıldıktan sonra. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

Bu yolun okuma için açılabilecek mevcut bir dosyaya işaret edip etmediğini gösteren bir değer alınır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Konum bir dosyaya işaret ediyorsa <see langword="true" />; aksi takdirde <see langword="false" />. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

Bu <c>AbstractPath</c> bir dizinse, içinde bulunan yolları döndürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | Bu <c>AbstractPath</c> içinde bulunan yollar. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

Bu <c>AbstractPath</c>'i bir dosya olarak açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| erişim | System.IO.FileAccess | Bir akış üzerinde gerçekleştirilebilecek işlemlerin bir alt kümesini belirtir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| _io.BufferedRandom | Belirtilen FileAccess ile açılmış bir akış. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

Dosya uzantısı belirtilen değere değiştirilen yeni bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| new_extension | string | Yeni bir uzantı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Aynı dizinde bir dosyaya işaret eden, ancak yeni bir uzantıya sahip yeni bir [AbstractPath](/psd/python-net/aspose.gis/abstractpath/). |


