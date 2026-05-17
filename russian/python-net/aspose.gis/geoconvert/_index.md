---
title: "Класс GeoConvert"
type: docs
weight: 1140
url: /ru/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Возвращает вычисленную позицию в виде строки в указанном формате. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Возвращает вычисленную позицию в виде строки в указанном формате. |
| [parse_point_text(text)](#parse_point_text_text_3) | Преобразует строку, содержащую координаты, в объект IPoint. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Преобразует строку, содержащую координаты, в объект IPoint. Возвращаемое значение указывает, удалось ли выполнить преобразование или нет. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Возвращает вычисленную позицию в виде строки в указанном формате.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| широта | double | Широта позиции. |
| долгота | double | Долгота позиции. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Формат результата. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Позиция в виде строки. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Возвращает вычисленную позицию в виде строки в указанном формате.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Объект IPoint. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Формат результата. |

**Returns**

| Тип | Описание |
| :- | :- |
| string | Позиция в виде строки. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Преобразует строку, содержащую координаты, в объект IPoint.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Строка, содержащая координаты для преобразования.<br/>            Строка должна содержать как широту, так и долготу координат.<br/>            Координаты должны быть разделены пробелом, запятой или точкой с запятой. |

**Returns**

| Тип | Описание |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Объект IPoint с координатами, эквивалентными входной строке. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Преобразует строку, содержащую координаты, в объект IPoint. Возвращаемое значение указывает, удалось ли выполнить преобразование или нет.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| text | string | Строка, содержащая координаты для преобразования.<br/>            Строка должна содержать как широту, так и долготу координат.<br/>            Координаты должны быть разделены пробелом, запятой или точкой с запятой. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | При возврате этого метода содержит объект IPoint с разобранными координатами, если преобразование удалось, или null, если преобразование не удалось. |

**Returns**

| Тип | Описание |
| :- | :- |
| bool | True, если текст был успешно разобран, иначе False. |


