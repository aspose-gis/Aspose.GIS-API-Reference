---
title: "ImageMetadataReader クラス"
type: docs
weight: 30
url: /ja/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **説明** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | EXIF タグ用のリーダーインスタンスを作成します |
| [get_reader(stream)](#get_reader_stream_2) | EXIF タグ用のリーダーインスタンスを作成します |
| [read_data()](#read_data__3) | サポートされているすべての EXIF タグを抽出します |
| [save(file_name)](#save_file_name_4) | 元のファイルが変更ロックされているため、新しいファイルに保存します |
| [save(file_name, format)](#save_file_name_format_5) | 元のファイルが変更ロックされているため、新しいファイルに保存します |
| [save(stream)](#save_stream_6) | 変更を別のストリームに保存しています |
| [save(stream, format)](#save_stream_format_7) | 変更を別のストリームに保存しています |
| [set_artist(artist)](#set_artist_artist_8) | EXIF アーティストタグを保存し、データを追加または上書きします。 |
| [set_description(description)](#set_description_description_9) | EXIF ImageDescription タグを保存し、データを追加または上書きします。 |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | EXIF GPSLatitudeRef、GPSLongitudeRef、GPSLatitude、GPSLongitude タグを保存し、データを追加または上書きします。 |
| [set_image_size(width, height)](#set_image_size_width_height_11) | EXIF ImageWidth と ImageHeight タグを保存し、データを追加または上書きします。 |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | EXIF ModifyDate（DataTime）タグを保存し、データを追加または上書きします。 |
| [try_get_artist(artist)](#try_get_artist_artist_13) | EXIF タグ Artist を検索し、タグが見つからない場合は null を返します。 |
| [try_get_description(description)](#try_get_description_description_14) | EXIF タグ ImageDescription を検索し、タグが見つからない場合は null を返します。 |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | EXIF のタグセット GPSLatitudeRef、GPSLongitudeRef、GPSLatitude、GPSLongitude を検索し、タグが存在しない場合は null を返します。 |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | EXIF のタグセット ImageWidth と ImageHeight を検索し、タグが存在しない場合は null を返します。 |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | EXIF タグ ModifyDate（DataTime）を検索し、タグが見つからない場合はデフォルトの DataTime 値を返します。 |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

EXIF タグ用のリーダーインスタンスを作成します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_name | string | 画像ファイルのフルネーム。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | メタデータリーダーインスタンス |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

EXIF タグ用のリーダーインスタンスを作成します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 画像データソースストリーム |

**Returns**

| 型 | 説明 |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | メタデータリーダーインスタンス |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

サポートされているすべての EXIF タグを抽出します

**Returns**

| 型 | 説明 |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | サポートされているタグのセットを表す ImageData |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

元のファイルが変更ロックされているため、新しいファイルに保存します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_name | string | 宛先ファイルのフルネーム |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

元のファイルが変更ロックされているため、新しいファイルに保存します

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| file_name | string | 宛先ファイルのフルネーム |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | 保存形式を指定します |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

変更を別のストリームに保存しています

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 宛先ストリーム |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

変更を別のストリームに保存しています

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| ストリーム | _io.BufferedRandom | 宛先ストリーム |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | 保存形式を指定します |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

EXIF アーティストタグを保存し、データを追加または上書きします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| アーティスト | string | アーティスト。 |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

EXIF ImageDescription タグを保存し、データを追加または上書きします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 説明 | string | 説明。 |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

EXIF GPSLatitudeRef、GPSLongitudeRef、GPSLatitude、GPSLongitude タグを保存し、データを追加または上書きします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 緯度 | double | 緯度。 |
| 経度 | double | 経度。 |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

EXIF ImageWidth と ImageHeight タグを保存し、データを追加または上書きします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| width | int | 幅。 |
| 高さ | int | 高さ。 |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

EXIF ModifyDate（DataTime）タグを保存し、データを追加または上書きします。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| modify_date | datetime | 修正日。 |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

EXIF タグ Artist を検索し、タグが見つからない場合は null を返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| アーティスト | 文字列 | アーティスト。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 成功した場合は True |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

EXIF タグ ImageDescription を検索し、タグが見つからない場合は null を返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 説明 | 文字列 | 説明。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 成功した場合は True |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

EXIF のタグセット GPSLatitudeRef、GPSLongitudeRef、GPSLatitude、GPSLongitude を検索し、タグが存在しない場合は null を返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | ジオロケーション。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 成功した場合は True |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

EXIF のタグセット ImageWidth と ImageHeight を検索し、タグが存在しない場合は null を返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | 画像のサイズ。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 成功した場合は True |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

EXIF タグ ModifyDate（DataTime）を検索し、タグが見つからない場合はデフォルトの DataTime 値を返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| modify_date | datetime[] | 修正日。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 成功した場合は True |


