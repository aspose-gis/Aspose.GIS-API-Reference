---
title: "WebTile 클래스"
type: docs
weight: 10
url: /ko/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| cell_x | int | r | 타일의 X-열. |
| cell_y | int | r | 타일의 Y-행. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_binary()](#as_binary__1) | 이미지 바이트 시퀀스를 반환합니다. |
| [as_path()](#as_path__2) | 타일 내용을 URL 또는 파일 경로로 제공합니다. |
| [as_raster()](#as_raster__3) | 타일 콘텐츠를 래스터 레이어로 표시합니다. |
| [get_extent()](#get_extent__4) | 이 레이어의 공간 범위를 표시합니다. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

이미지 바이트 시퀀스를 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| byte | 바이트 시퀀스 |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

타일 내용을 URL 또는 파일 경로로 제공합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 파일에 대한 URL 또는 경로 |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

타일 콘텐츠를 래스터 레이어로 표시합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | 래스터. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

이 레이어의 공간 범위를 표시합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | 이 레이어의 공간 범위. |


