---
title: "ImageMetadataReader 클래스"
type: docs
weight: 30
url: /ko/python-net/aspose.gis.imagemetadata/imagemetadatareader/
---

**Summary:** Class for editing, adding some EXIF tags

**Module:** [aspose.gis.imagemetadata](/psd/python-net/aspose.gis.imagemetadata/)

**Full Name:** aspose.gis.imagemetadata.ImageMetadataReader

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_reader(file_name)](#get_reader_file_name_1) | EXIF 태그용 리더 인스턴스를 생성합니다 |
| [get_reader(stream)](#get_reader_stream_2) | EXIF 태그용 리더 인스턴스를 생성합니다 |
| [read_data()](#read_data__3) | 지원되는 모든 EXIF 태그를 추출합니다 |
| [save(file_name)](#save_file_name_4) | 원본 파일이 변경에 대해 잠겨 있으므로 새 파일에 저장합니다 |
| [save(file_name, format)](#save_file_name_format_5) | 원본 파일이 변경에 대해 잠겨 있으므로 새 파일에 저장합니다 |
| [save(stream)](#save_stream_6) | 변경 사항을 별도 스트림에 저장합니다 |
| [save(stream, format)](#save_stream_format_7) | 변경 사항을 별도 스트림에 저장합니다 |
| [set_artist(artist)](#set_artist_artist_8) | EXIF Artist 태그를 저장하고 데이터를 추가하거나 덮어씁니다. |
| [set_description(description)](#set_description_description_9) | EXIF ImageDescription 태그를 저장하고, 데이터를 추가하거나 덮어씁니다. |
| [set_geo_location(latitude, longitude)](#set_geo_location_latitude_longitude_10) | EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude 및 GPSLongitude 태그를 저장하고, 데이터를 추가하거나 덮어씁니다. |
| [set_image_size(width, height)](#set_image_size_width_height_11) | EXIF ImageWidth 및 ImageHeight 태그를 저장하고, 데이터를 추가하거나 덮어씁니다. |
| [set_modify_date(modify_date)](#set_modify_date_modify_date_12) | EXIF ModifyDate (DataTime) 태그를 저장하고, 데이터를 추가하거나 덮어씁니다. |
| [try_get_artist(artist)](#try_get_artist_artist_13) | EXIF 태그 Artist를 찾으려고 시도하며, 태그를 찾지 못하면 null을 반환합니다. |
| [try_get_description(description)](#try_get_description_description_14) | EXIF 태그 ImageDescription을 찾으려고 시도하며, 태그를 찾지 못하면 null을 반환합니다. |
| [try_get_geo_location(geo_location)](#try_get_geo_location_geo_location_15) | EXIF 태그 집합 GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude를 찾으려고 시도하며, 태그가 존재하지 않으면 null을 반환합니다. |
| [try_get_image_size(image_size)](#try_get_image_size_image_size_16) | EXIF 태그 집합 ImageWidth 및 ImageHeight를 찾으려고 시도하며, 태그가 존재하지 않으면 null을 반환합니다. |
| [try_get_modify_date(modify_date)](#try_get_modify_date_modify_date_17) | EXIF 태그 ModifyDate (DataTime)를 찾으려고 시도하며, 태그를 찾지 못하면 기본 DataTime 값을 반환합니다. |


### Method: get_reader(file_name)  [static] {#get_reader_file_name_1}


```
 get_reader(file_name) 
```

EXIF 태그용 리더 인스턴스를 생성합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_name | string | 이미지 파일의 전체 이름. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | 메타데이터 리더 인스턴스 |


### Method: get_reader(stream)  [static] {#get_reader_stream_2}


```
 get_reader(stream) 
```

EXIF 태그용 리더 인스턴스를 생성합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 이미지 데이터 소스 스트림 |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [ImageMetadataReader](/psd/python-net/aspose.gis.imagemetadata/imagemetadatareader) | 메타데이터 리더 인스턴스 |


### Method: read_data() {#read_data__3}


```
 read_data() 
```

지원되는 모든 EXIF 태그를 추출합니다

**Returns**

| 형식 | 설명 |
| :- | :- |
| [ImageData](/psd/python-net/aspose.gis.imagemetadata/imagedata) | 지원되는 태그 집합을 나타내는 ImageData |


### Method: save(file_name) {#save_file_name_4}


```
 save(file_name) 
```

원본 파일이 변경에 대해 잠겨 있으므로 새 파일에 저장합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_name | string | 대상 파일의 전체 이름 |

### Method: save(file_name, format) {#save_file_name_format_5}


```
 save(file_name, format) 
```

원본 파일이 변경에 대해 잠겨 있으므로 새 파일에 저장합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| file_name | string | 대상 파일의 전체 이름 |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | 저장 형식을 지정합니다. |

### Method: save(stream) {#save_stream_6}


```
 save(stream) 
```

변경 사항을 별도 스트림에 저장합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 대상 스트림 |

### Method: save(stream, format) {#save_stream_format_7}


```
 save(stream, format) 
```

변경 사항을 별도 스트림에 저장합니다

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 스트림 | _io.BufferedRandom | 대상 스트림 |
| format | [ImageFormat](/psd/python-net/aspose.gis.imagemetadata/imageformat) | 저장 형식을 지정합니다. |

### Method: set_artist(artist) {#set_artist_artist_8}


```
 set_artist(artist) 
```

EXIF Artist 태그를 저장하고 데이터를 추가하거나 덮어씁니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 아티스트 | string | 아티스트. |

### Method: set_description(description) {#set_description_description_9}


```
 set_description(description) 
```

EXIF ImageDescription 태그를 저장하고, 데이터를 추가하거나 덮어씁니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 설명 | string | 설명. |

### Method: set_geo_location(latitude, longitude) {#set_geo_location_latitude_longitude_10}


```
 set_geo_location(latitude, longitude) 
```

EXIF GPSLatitudeRef, GPSLongitudeRef, GPSLatitude 및 GPSLongitude 태그를 저장하고, 데이터를 추가하거나 덮어씁니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 위도 | double | 위도. |
| 경도 | double | 경도. |

### Method: set_image_size(width, height) {#set_image_size_width_height_11}


```
 set_image_size(width, height) 
```

EXIF ImageWidth 및 ImageHeight 태그를 저장하고, 데이터를 추가하거나 덮어씁니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| width | int | 너비. |
| 높이 | int | 높이. |

### Method: set_modify_date(modify_date) {#set_modify_date_modify_date_12}


```
 set_modify_date(modify_date) 
```

EXIF ModifyDate (DataTime) 태그를 저장하고, 데이터를 추가하거나 덮어씁니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| modify_date | datetime | 수정 날짜. |

### Method: try_get_artist(artist) {#try_get_artist_artist_13}


```
 try_get_artist(artist) 
```

EXIF 태그 Artist를 찾으려고 시도하며, 태그를 찾지 못하면 null을 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 아티스트 | 문자열 | 아티스트. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 성공하면 True |


### Method: try_get_description(description) {#try_get_description_description_14}


```
 try_get_description(description) 
```

EXIF 태그 ImageDescription을 찾으려고 시도하며, 태그를 찾지 못하면 null을 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 설명 | 문자열 | 설명. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 성공하면 True |


### Method: try_get_geo_location(geo_location) {#try_get_geo_location_geo_location_15}


```
 try_get_geo_location(geo_location) 
```

EXIF 태그 집합 GPSLatitudeRef, GPSLongitudeRef, GPSLatitude, GPSLongitude를 찾으려고 시도하며, 태그가 존재하지 않으면 null을 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| geo_location | [GeoLocation[]](/psd/python-net/aspose.gis.imagemetadata/geolocation) | 지리 위치. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 성공하면 True |


### Method: try_get_image_size(image_size) {#try_get_image_size_image_size_16}


```
 try_get_image_size(image_size) 
```

EXIF 태그 집합 ImageWidth 및 ImageHeight를 찾으려고 시도하며, 태그가 존재하지 않으면 null을 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| image_size | [ImageSize[]](/psd/python-net/aspose.gis.imagemetadata/imagesize) | 이미지 크기. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 성공하면 True |


### Method: try_get_modify_date(modify_date) {#try_get_modify_date_modify_date_17}


```
 try_get_modify_date(modify_date) 
```

EXIF 태그 ModifyDate (DataTime)를 찾으려고 시도하며, 태그를 찾지 못하면 기본 DataTime 값을 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| modify_date | datetime[] | 수정 날짜. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 성공하면 True |


