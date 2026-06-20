---
title: "ImageMetadataReader 类"
type: docs
weight: 30
url: /zh/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | 创建一个用于 EXIF 标签的读取器实例 |
| [get_reader(stream)](#get_reader_stream_2) | 创建一个用于 EXIF 标签的读取器实例 |
| [read_data()](#read_data__3) | 提取所有支持的 EXIF 标签 |
| [save(file_name)](#save_file_name_4) | 保存到新文件，因为原文件已锁定，无法更改 |
| [save(file_name, format)](#save_file_name_format_5) | 保存到新文件，因为原文件已锁定，无法更改 |
| [save(stream)](#save_stream_6) | 将更改保存到单独的流 |
| [save(stream, format)](#save_stream_format_7) | 将更改保存到单独的流 |
| [set_artist(artist)](#set_artist_artist_8) | 保存 EXIF Artist 标签，添加或覆盖数据。 |
| [set_description(description)](#set_description_description_9) | 保存 EXIF ImageDescription 标签，添加或覆盖数据。 |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | 保存 EXIF GPSLatitudeRef、GPSLongitudeRef、GPSLatitude 和 GPSLongitude 标签，添加或覆盖数据。 |
| [set_image_size(width, height)](#set_image_size_width_height_11) | 保存 EXIF ImageWidth 和 ImageHeight 标签，添加或覆盖数据。 |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | 保存 EXIF ModifyDate（DataTime）标签，添加或覆盖数据。 |
| [try_get_artist(artist)](#try_get_artist_artist_13) | 尝试查找 EXIF Artist 标签，如果未找到该标签则返回 null。 |
| [try_get_description(description)](#try_get_description_description_14) | 尝试查找 EXIF ImageDescription 标签，如果未找到该标签则返回 null。 |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | 尝试查找 EXIF GPSLatitudeRef、GPSLongitudeRef、GPSLatitude、GPSLongitude 一组标签，如果这些标签不存在则返回 null。 |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | 尝试查找 EXIF ImageWidth 和 ImageHeight 一组标签，如果这些标签不存在则返回 null。 |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | 尝试查找 EXIF ModifyDate（DataTime）标签，如果未找到该标签则返回默认的 DataTime 值。 |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

创建一个用于 EXIF 标签的读取器实例

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | string | 图像文件的完整名称。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | 元数据读取器实例 |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

创建一个用于 EXIF 标签的读取器实例

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | _io.BufferedRandom | 图像数据源流 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | 元数据读取器实例 |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

提取所有支持的 EXIF 标签

**Returns**

| 类型 | 描述 |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | 表示支持标签集合的 ImageData |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

保存到新文件，因为原文件已锁定，无法更改

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | string | 目标文件的完整名称 |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

保存到新文件，因为原文件已锁定，无法更改

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| file_name | string | 目标文件的完整名称 |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | 指定保存的格式 |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

将更改保存到单独的流

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | _io.BufferedRandom | 目标流 |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

将更改保存到单独的流

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| stream | _io.BufferedRandom | 目标流 |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | 指定保存的格式 |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

保存 EXIF Artist 标签，添加或覆盖数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 艺术家 | string | 艺术家。 |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

保存 EXIF ImageDescription 标签，添加或覆盖数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 描述 | string | 描述。 |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

保存 EXIF GPSLatitudeRef、GPSLongitudeRef、GPSLatitude 和 GPSLongitude 标签，添加或覆盖数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 纬度 | double | 纬度。 |
| 经度 | double | 经度。 |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

保存 EXIF ImageWidth 和 ImageHeight 标签，添加或覆盖数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| width | 整数 | 宽度。 |
| 高度 | 整数 | 高度。 |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

保存 EXIF ModifyDate（DataTime）标签，添加或覆盖数据。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| modify_date | datetime | 修改日期。 |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

尝试查找 EXIF Artist 标签，如果未找到该标签则返回 null。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 艺术家 | 字符串 | 艺术家。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 成功时返回 true |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

尝试查找 EXIF ImageDescription 标签，如果未找到该标签则返回 null。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| 描述 | 字符串 | 描述。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 成功时返回 true |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

尝试查找 EXIF GPSLatitudeRef、GPSLongitudeRef、GPSLatitude、GPSLongitude 一组标签，如果这些标签不存在则返回 null。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | 地理位置。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 成功时返回 true |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

尝试查找 EXIF ImageWidth 和 ImageHeight 一组标签，如果这些标签不存在则返回 null。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | 图像大小。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 成功时返回 true |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

尝试查找 EXIF ModifyDate（DataTime）标签，如果未找到该标签则返回默认的 DataTime 值。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| modify_date | datetime[] | 修改日期。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| bool | 成功时返回 true |


