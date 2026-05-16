---
title: "XyzTiles 클래스"
type: docs
weight: 20
url: /ko/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/)의 인스턴스를 생성합니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | 지정된 타일을 로드합니다. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | 지정된 타일을 로드합니다. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | 공간 경계 상자와 줌 레벨에 따라 타일을 로드합니다. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | 공간 경계 상자와 줌 레벨에 따라 타일을 로드합니다. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

[XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/)의 인스턴스를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | 웹 옵션을 포함하는 연결. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

지정된 타일을 로드합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| zoom | int | 타일을 로드하기 위한 줌 레벨입니다. 가장 높은 줌 레벨은 0이며, 대부분의 타일 제공자는 최대 약 22개의 줌 레벨을 가집니다. |
| x | int | 타일의 x-열. |
| y | int | 타일의 y-행. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | 웹 타일. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

지정된 타일을 로드합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| zoom | int | 타일을 로드하기 위한 줌 레벨입니다. 가장 높은 줌 레벨은 0이며, 대부분의 타일 제공자는 최대 약 22개의 줌 레벨을 가집니다. |
| x | int | 타일의 x-열. |
| y | int | 타일의 y-행. |
| tile_size | int | 타일 크기이며, 기본값은 256입니다(타일 크기의 표준값). |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | 웹 타일. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

공간 경계 상자와 줌 레벨에 따라 타일을 로드합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| zoom | int | 타일을 로드하기 위한 줌 레벨입니다. 가장 높은 줌 레벨은 0이며, 대부분의 타일 제공자는 최대 약 22개의 줌 레벨을 가집니다. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 타일을 로드하기 위한 경계 상자입니다. 누락된 경우 Wgs84 공간 참조가 사용됩니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | 웹 타일입니다. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

공간 경계 상자와 줌 레벨에 따라 타일을 로드합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| zoom | int | 타일을 로드하기 위한 줌 레벨입니다. 가장 높은 줌 레벨은 0이며, 대부분의 타일 제공자는 최대 약 22개의 줌 레벨을 가집니다. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | 타일을 로드하기 위한 경계 상자입니다. 누락된 경우 Wgs84 공간 참조가 사용됩니다. |
| tile_size | int | 타일 크기이며, 기본값은 256입니다(타일 크기의 표준값). |

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | 웹 타일입니다. |


