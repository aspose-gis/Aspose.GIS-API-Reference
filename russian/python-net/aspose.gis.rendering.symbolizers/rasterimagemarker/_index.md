---
title: "Класс RasterImageMarker"
type: docs
weight: 80
url: /ru/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/
---

**Summary:** This symbolizer renders a provided raster image.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.RasterImageMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_1) | Инициализирует новый экземпляр класса [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(image_path)](#RasterImageMarker_image_path_2) | Инициализирует новый экземпляр класса [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
| [RasterImageMarker(other)](#RasterImageMarker_other_3) | Инициализирует новый экземпляр класса [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает высоту маркера. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | указывает, какая сторона формы маркера будет выровнена по горизонтали с точкой расположения. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает горизонтальное смещение от положения точки до точки привязки формы. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Элемент [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ничего не рисует и фактически пропускает отрисовку геометрии, к которой он применён. |
| opacity | double | r/w | Непрозрачность слоя. Значение по умолчанию — 1.0. |
| вращение | double | r/w | Указывает вращение символа вокруг его центральной точки в десятичных градусах.<br/>            Положительные значения означают вращение по часовой стрелке, отрицательные — против часовой стрелки. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Указывает, какая сторона формы маркера будет выровнена по вертикали с точкой расположения. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает вертикальное смещение от положения точки до точки привязки формы. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает ширину маркера. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |


### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_1}


```
 RasterImageMarker(image_path) 
```

Инициализирует новый экземпляр класса [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_path | string | Путь к файлу. |

### Constructor: RasterImageMarker(image_path) {#RasterImageMarker_image_path_2}


```
 RasterImageMarker(image_path) 
```

Инициализирует новый экземпляр класса [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| image_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Путь к файлу. |

### Constructor: RasterImageMarker(other) {#RasterImageMarker_other_3}


```
 RasterImageMarker(other) 
```

Инициализирует новый экземпляр класса [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | Другой [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker/) для копирования данных. |

### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [RasterImageMarker](/psd/python-net/aspose.gis.rendering.symbolizers/rasterimagemarker) | Клон этого экземпляра. |


