---
title: "Класс FileGdbCoordinatePrecisionGrid"
type: docs
weight: 10
url: /ru/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | Инициализирует новый экземпляр класса FileGdbCoordinatePrecisionGrid |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | Получает или задает начало координаты M. Если установлено значение <see langword="null" />, используется значение по умолчанию. |
| m_scale | Nullable<double> | r/w | Получает или задает масштаб координаты M. Если установлено значение <see langword="null" />, используется значение по умолчанию. |
| x_origin | Nullable<double> | r/w | Получает или задает начало координаты X. Если установить значение <see langword="null" />, используется значение по умолчанию. |
| xy_scale | Nullable<double> | r/w | Получает или задает масштаб координат X и Y. Если установить значение <see langword="null" />, используется значение по умолчанию. |
| y_origin | Nullable<double> | r/w | Получает или задает начало координаты Y. Если установить значение <see langword="null" />, используется значение по умолчанию. |
| z_origin | Nullable<double> | r/w | Получает или задает начало координаты Z. Если установить значение <see langword="null" />, используется значение по умолчанию. |
| z_scale | Nullable<double> | r/w | Получает или задает масштаб координаты Z. Если установить значение <see langword="null" />, используется значение по умолчанию. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Создает новый <c>FileGdbCoordinatePrecisionGrid</c>, так чтобы все значения внутри прямоугольника были представимы. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

Инициализирует новый экземпляр класса FileGdbCoordinatePrecisionGrid

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Создает новый <c>FileGdbCoordinatePrecisionGrid</c>, так чтобы все значения внутри прямоугольника были представимы.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Один угол прямоугольника. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Противоположный угол прямоугольника. Должен иметь те же размеры, что и <paramref name="p1" />. |

**Returns**

| Тип | Описание |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | Этот <c>FileGdbCoordinatePrecisionGrid</c>, так чтобы все значения внутри прямоугольника были представимы.<br/>            Значения за пределами прямоугольника не представимы, поэтому все координаты, которые будут записаны в слой FileGDB,<br/>            должны находиться внутри прямоугольника. |


