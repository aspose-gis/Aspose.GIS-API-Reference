---
title: "MultiStreamPath 类"
type: docs
weight: 2760
url: /zh/python-net/aspose.gis/multistreampath/
---

**Summary:** This class works with formats which contains several files.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.MultiStreamPath

**Inheritance:** AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MultiStreamPath(entry_file_name, file_names, streams)](#MultiStreamPath_entry_file_name_file_names_streams_1) | 初始化一个新的 [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) 类实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| location | string | r | 获取此 <c>AbstractPath</c> 的位置的字符串表示形式。 |
| separator | char | r | 获取用于分隔 [MultiStreamPath.location](/psd/python-net/aspose.gis/multistreampath/) 字符串中目录层级的分隔符字符。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [combine(location)](#combine_location_1) | 将此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 与指定的路径组件组合。 |
| delete() | 删除此路径指向的文件。 |
| [from_local_path(path)](#from_local_path_path_2) | 创建一个表示本地文件系统上位置的 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)。 |
| [from_stream(stream)](#from_stream_stream_3) | 从流创建一个 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)。 |
| [get_extension()](#get_extension__4) | 返回此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 的扩展名。 |
| [get_file_name()](#get_file_name__5) | 返回此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 的文件名和扩展名。 |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | 返回此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 不含扩展名的文件名。 |
| [is_file()](#is_file__7) | 获取一个值，指示此路径是否指向可供读取的现有文件。 |
| [list_directory()](#list_directory__8) | 如果它是目录，则返回位于此 <c>AbstractPath</c> 内的路径。 |
| [open(access)](#open_access_9) | 抽象一组用于访问数据的打开流式多文件格式的路径。 |
| [with_extension(new_extension)](#with_extension_new_extension_10) | 返回一个新的 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)，其文件扩展名已更改为指定值。 |


### Constructor: MultiStreamPath(entry_file_name, file_names, streams) {#MultiStreamPath_entry_file_name_file_names_streams_1}


```
 MultiStreamPath(entry_file_name, file_names, streams) 
```

初始化一个新的 [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) 类实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| entry_file_name | string | 入口文件的名称。 |
| file_names | string | 文件名。 |
| streams | _io.BufferedRandom[] | 流。 |

### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

将此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 与指定的路径组件组合。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| location | string | 要追加到此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 的路径组件。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 一个新的 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)，指向一个 [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/)，该位置是此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 与<br/>            参数的位置的组合。 |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

创建一个表示本地文件系统上位置的 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| path | string | 本地文件系统上的路径，例如 <c>\"C:\\\\file.shp\"</c> 或 <c>\"D:\\\\directory\\\\\"</c>。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 一个表示由 <paramref name="path" /> 定义的位置的 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)。 |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

从流创建一个 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | _io.BufferedRandom | 用于创建 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 的流。<c>Aspose.GIS</c> 不会释放该流。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 一个 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 实例，其内容为指定的流。 |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

返回此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 的扩展名。

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 的扩展名（包括句点 "."），如果该 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 没有扩展名，则为<br/>            空字符串。 |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

返回此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 的文件名和扩展名。

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 在 [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) 中最后一个 [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) 字符之后的字符。如果<br/>            最后一个字符是 [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/)，则返回空字符串。如果在 [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) 中没有<br/>            [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) 字符，则返回 [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) 本身。 |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

返回此 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 不含扩展名的文件名。

**Returns**

| 类型 | 描述 |
| :- | :- |
| string | 由 [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) 返回的字符串，去除最后的句点及其后面的所有字符。 |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

获取一个值，指示此路径是否指向可供读取的现有文件。

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 如果位置指向文件，则为 <see langword="true" />；否则为 <see langword="false" />。 |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

如果它是目录，则返回位于此 <c>AbstractPath</c> 内的路径。

**Returns**

| 类型 | 描述 |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | 位于此 <c>AbstractPath</c> 内的路径。 |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

抽象一组用于访问数据的打开流式多文件格式的路径。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 访问 | System.IO.FileAccess | 指定可以在流上执行的操作子集。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| _io.BufferedRandom | 这可以是一个   或者是客户端最初传入的流。 |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

返回一个新的 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)，其文件扩展名已更改为指定值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| new_extension | string | 一个新的扩展名。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 一个新的 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)，指向同一目录中的文件，但使用新的扩展名。 |


