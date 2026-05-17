---
title: "Класс WebTile"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.raster.web/webtile/
---

**Summary:** Abstract Web Tile Model.

**Module:** [aspose.gis.raster.web](/psd/python-net/aspose.gis.raster.web/)

**Full Name:** aspose.gis.raster.web.WebTile

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| cell_x | int | r | X-колонка плитки. |
| cell_y | int | r | Y-строка плитки. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [as_binary()](#as_binary__1) | Возвращает последовательность байтов изображения |
| [as_path()](#as_path__2) | Представляет содержимое плитки как URL или путь к файлу. |
| [as_raster()](#as_raster__3) | Представляет содержимое плитки как растровый слой. |
| [get_extent()](#get_extent__4) | Представляет пространственное покрытие этого слоя. |


### Method: as_binary() {#as_binary__1}


```
 as_binary() 
```

Возвращает последовательность байтов изображения

**Returns**

| Тип | Описание |
| :- | :- |
| byte | Последовательность байтов |


### Method: as_path() {#as_path__2}


```
 as_path() 
```

Представляет содержимое плитки как URL или путь к файлу.

**Returns**

| Тип | Описание |
| :- | :- |
| string | URL или путь к файлу |


### Method: as_raster() {#as_raster__3}


```
 as_raster() 
```

Представляет содержимое плитки как растровый слой.

**Returns**

| Тип | Описание |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Растр. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Представляет пространственное покрытие этого слоя.

**Returns**

| Тип | Описание |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Пространственный экстент этого слоя. |


