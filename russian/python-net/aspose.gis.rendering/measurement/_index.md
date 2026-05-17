---
title: "Класс Measurement"
type: docs
weight: 150
url: /ru/python-net/aspose.gis.rendering/measurement/
---

**Summary:** A number that indicates a render measurement.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Measurement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [Measurement()](#Measurement__1) | Инициализирует новый экземпляр класса Measurement |
| [Measurement(value, unit)](#Measurement_value_unit_2) | Создаёт новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Единица измерения. |
| value | double | r | Число, указывающее длину измерения. |
| zero [static] | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r | Измерение нулевой длины. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [inches(value)](#inches_value_1) | Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в дюймах. |
| [map_units(value)](#map_units_value_2) | Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в единицах пространственной привязки карт. |
| [meters_on_earth(value)](#meters_on_earth_value_3) | Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в метрах на Земле. |
| [millimeters(value)](#millimeters_value_4) | Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в миллиметрах. |
| [pixels(value)](#pixels_value_5) | Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в пикселях. |
| [points(value)](#points_value_6) | Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в пунктах. |


### Constructor: Measurement() {#Measurement__1}


```
 Measurement() 
```

Инициализирует новый экземпляр класса Measurement

### Constructor: Measurement(value, unit) {#Measurement_value_unit_2}


```
 Measurement(value, unit) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | double | Число, указывающее длину измерения. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Единица измерения. |

### Method: inches(value)  [static] {#inches_value_1}


```
 inches(value) 
```

Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в дюймах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | double | Количество дюймов. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Новый экземпляр класса <c>Measurement</c>. |


### Method: map_units(value)  [static] {#map_units_value_2}


```
 map_units(value) 
```

Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в единицах пространственной привязки карт.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | double | Количество единиц. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Новый экземпляр класса <c>Measurement</c>. |


### Method: meters_on_earth(value)  [static] {#meters_on_earth_value_3}


```
 meters_on_earth(value) 
```

Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в метрах на Земле.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | double | Количество метров. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Новый экземпляр класса <c>Measurement</c>. |


### Method: millimeters(value)  [static] {#millimeters_value_4}


```
 millimeters(value) 
```

Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в миллиметрах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | double | Количество миллиметров. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Новый экземпляр класса <c>Measurement</c>. |


### Method: pixels(value)  [static] {#pixels_value_5}


```
 pixels(value) 
```

Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в пикселях.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | double | Количество пикселей. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Новый экземпляр класса <c>Measurement</c>. |


### Method: points(value)  [static] {#points_value_6}


```
 points(value) 
```

Возвращает новый экземпляр <c>Measurement</c>, представляющий длину в пунктах.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| value | double | Количество точек. |

**Returns**

| Тип | Описание |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Новый экземпляр класса <c>Measurement</c>. |


