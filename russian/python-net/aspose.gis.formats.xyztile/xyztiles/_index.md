---
title: "XyzTiles Класс"
type: docs
weight: 20
url: /ru/python-net/aspose.gis.formats.xyztile/xyztiles/
---

**Summary:** A XyzTiles provide access to [XyzTile](/psd/python-net/aspose.gis.formats.xyztile/xyztile/) objects.

**Module:** [aspose.gis.formats.xyztile](/psd/python-net/aspose.gis.formats.xyztile/)

**Full Name:** aspose.gis.formats.xyztile.XyzTiles

**Inheritance:** WebTiles

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [XyzTiles(connection)](#XyzTiles_connection_1) | Создайте экземпляр [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/). |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [get_tile(zoom, x, y)](#get_tile_zoom_x_y_1) | Загружает указанную плитку. |
| [get_tile(zoom, x, y, tile_size)](#get_tile_zoom_x_y_tile_size_2) | Загружает указанную плитку. |
| [get_tiles(zoom, extent)](#get_tiles_zoom_extent_3) | Загружает плитки по пространственной ограничивающей рамке и уровню масштабирования. |
| [get_tiles(zoom, extent, tile_size)](#get_tiles_zoom_extent_tile_size_4) | Загружает плитки по пространственной ограничивающей рамке и уровню масштабирования. |


### Constructor: XyzTiles(connection) {#XyzTiles_connection_1}


```
 XyzTiles(connection) 
```

Создайте экземпляр [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| connection | [XyzConnection](/psd/python-net/aspose.gis.formats.xyztile/xyzconnection) | Подключение, содержащее веб‑опции. |

### Method: get_tile(zoom, x, y) {#get_tile_zoom_x_y_1}


```
 get_tile(zoom, x, y) 
```

Загружает указанную плитку.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| zoom | int | Уровень масштабирования для загрузки плиток. Наивысший уровень масштабирования — 0. Большинство поставщиков плиток имеют около 22 максимальных уровней масштабирования. |
| x | int | Колонка x плитки. |
| y | int | Строка y плитки. |

**Returns**

| Тип | Описание |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Веб‑плитка. |


### Method: get_tile(zoom, x, y, tile_size) {#get_tile_zoom_x_y_tile_size_2}


```
 get_tile(zoom, x, y, tile_size) 
```

Загружает указанную плитку.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| zoom | int | Уровень масштабирования для загрузки плиток. Наивысший уровень масштабирования — 0. Большинство поставщиков плиток имеют около 22 максимальных уровней масштабирования. |
| x | int | Колонка x плитки. |
| y | int | Строка y плитки. |
| tile_size | int | Размер плиток, по умолчанию 256 (это стандартный размер плиток) |

**Returns**

| Тип | Описание |
| :- | :- |
| [WebTile](/psd/python-net/aspose.gis.raster.web/webtile/) | Веб‑плитка. |


### Method: get_tiles(zoom, extent) {#get_tiles_zoom_extent_3}


```
 get_tiles(zoom, extent) 
```

Загружает плитки по пространственной ограничивающей рамке и уровню масштабирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| zoom | int | Уровень масштабирования для загрузки плиток. Наивысший уровень масштабирования — 0. Большинство поставщиков плиток имеют около 22 максимальных уровней масштабирования. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Ограничивающая рамка для загрузки плиток. Если не указано, будет использована пространственная ссылка Wgs84. |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Веб‑плитки. |


### Method: get_tiles(zoom, extent, tile_size) {#get_tiles_zoom_extent_tile_size_4}


```
 get_tiles(zoom, extent, tile_size) 
```

Загружает плитки по пространственной ограничивающей рамке и уровню масштабирования.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| zoom | int | Уровень масштабирования для загрузки плиток. Наивысший уровень масштабирования — 0. Большинство поставщиков плиток имеют около 22 максимальных уровней масштабирования. |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Ограничивающая рамка для загрузки плиток. Если не указано, будет использована пространственная ссылка Wgs84. |
| tile_size | int | Размер плиток, по умолчанию 256 (это стандартный размер плиток) |

**Returns**

| Тип | Описание |
| :- | :- |
| System.Collections.Generic.IEnumerable<Aspose.Gis.Raster.Web.WebTile> | Веб‑плитки. |


