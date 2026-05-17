---
title: "Класс RasterLayer"
type: docs
weight: 70
url: /ru/python-net/aspose.gis.raster/rasterlayer/
---

**Summary:** Represents a raster layer.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.RasterLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| band_count | int | r | Возвращает количество полос в растровом слое. |
| bounds | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | r | Возвращает границы растра. |
| cell_size | [IRasterCellSize](/psd/python-net/aspose.gis.raster/irastercellsize) | r | Возвращает размер ячейки или пикселя растра. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Возвращает [RasterLayer.driver](/psd/python-net/aspose.gis.raster/rasterlayer/) который создал этот слой. |
| высота | int | r | Возвращает высоту растра в пикселях. Также известна как количество строк. |
| no_data_values | [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | r | Возвращает значения, представляющие фон или «нет данных» растра. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Возвращает систему пространственной привязки растра.<br/>            Может быть <see langword=\"null\" /> если она неизвестна. |
| upper_left_x | double | r | Возвращает координату x верхнего левого угла растра. |
| upper_left_y | double | r | Возвращает координату y верхнего левого угла растра. |
| width | int | r | Возвращает ширину растра в пикселях. Также известна как количество столбцов. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [crop(geometry, masks)](#crop_geometry_masks_1) | Обрезает растровый слой с использованием формы (и маски полос). |
| [crop(masks)](#crop_masks_2) | Обрезает растровый слой с использованием маски полос). |
| [get_band(index)](#get_band_index_3) | Возвращает полосу по указанному индексу. |
| [get_extent()](#get_extent__4) | Вычисляет пространственное покрытие этого слоя. |
| [get_spatial_point(cell_x, cell_y)](#get_spatial_point_cell_x_cell_y_5) | Преобразует указанные столбец и строку в пространственную координату. |
| [get_statistics(band_index, exclude_nodata_value)](#get_statistics_band_index_exclude_nodata_value_6) | Вычисляет сводную статистику, включающую количество, сумму, среднее, минимум, максимум. |
| [get_values(cell_x, cell_y)](#get_values_cell_x_cell_y_7) | Считывает значения в указанной ячейке. |
| [get_values_dump(rect)](#get_values_dump_rect_8) | Считывает значения в указанном блоке как одномерный массив. |
| [warp(options)](#warp_options_9) | Перекладывает растровый слой в другой. |


### Method: crop(geometry, masks) {#crop_geometry_masks_1}


```
 crop(geometry, masks) 
```

Обрезает растровый слой с использованием формы (и маски полос).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Геометрия представляет форму. |
| маски | double | Маска для слоя обрезки |

**Returns**

| Тип | Описание |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Обрезанный растровый слой. Если пересечения не найдены, возвращает <see langword=\"null\" />. |


### Method: crop(masks) {#crop_masks_2}


```
 crop(masks) 
```

Обрезает растровый слой с использованием маски полос).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| маски | double | Маска для слоя обрезки |

**Returns**

| Тип | Описание |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Обрезанный растровый слой. Если пересечения не найдены, возвращает <see langword=\"null\" />. |


### Method: get_band(index) {#get_band_index_3}


```
 get_band(index) 
```

Возвращает полосу по указанному индексу.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| индекс | int | Номера полос начинаются с 0, и полоса считается равной 0, если не указано иначе. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IRasterBand](/psd/python-net/aspose.gis.raster/irasterband) | Возвращает базовые метаданные о растровой полосе. |


### Method: get_extent() {#get_extent__4}


```
 get_extent() 
```

Вычисляет пространственное покрытие этого слоя.

**Returns**

| Тип | Описание |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Пространственный экстент этого слоя. |


### Method: get_spatial_point(cell_x, cell_y) {#get_spatial_point_cell_x_cell_y_5}


```
 get_spatial_point(cell_x, cell_y) 
```

Преобразует указанные столбец и строку в пространственную координату.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cell_x | int | Значение столбца (координата x). Нумерация начинается с 0. |
| cell_y | int | Значение строки (координата y). Нумерация начинается с 0. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Возвращает координату x верхнего левого угла по заданному столбцу и строке. |


### Method: get_statistics(band_index, exclude_nodata_value) {#get_statistics_band_index_exclude_nodata_value_6}


```
 get_statistics(band_index, exclude_nodata_value) 
```

Вычисляет сводную статистику, включающую количество, сумму, среднее, минимум, максимум.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| band_index | int | Индекс диапазона. Нумерация начинается с 0. |
| exclude_nodata_value | bool | Позволяет исключать значения 'nodata'. Если 'excludeNodataValue' установлено в false, то учитываются все пиксели. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RasterStatistics](/psd/python-net/aspose.gis.raster/rasterstatistics) | Сводная статистика. |


### Method: get_values(cell_x, cell_y) {#get_values_cell_x_cell_y_7}


```
 get_values(cell_x, cell_y) 
```

Считывает значения в указанной ячейке.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| cell_x | int | Значение столбца (координата x). Нумерация начинается с 0. |
| cell_y | int | Значение строки (координата y). Нумерация начинается с 0. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IRasterValues](/psd/python-net/aspose.gis.raster/irastervalues) | Растровые значения. |


### Method: get_values_dump(rect) {#get_values_dump_rect_8}


```
 get_values_dump(rect) 
```

Считывает значения в указанном блоке как одномерный массив.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| rect | [RasterRect](/psd/python-net/aspose.gis.raster/rasterrect) | Блок растровых ячеек, из которых читается дамп. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IRasterValues[]](/psd/python-net/aspose.gis.raster/irastervalues) | Дамп значений. |


### Method: warp(options) {#warp_options_9}


```
 warp(options) 
```

Перекладывает растровый слой в другой.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| options | [WarpOptions](/psd/python-net/aspose.gis.raster/warpoptions) | Параметры процедуры репроекции. |

**Returns**

| Тип | Описание |
| :- | :- |
| [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer) | Слой искажения растра. |


