---
title: "Класс SimpleMarker"
type: docs
weight: 130
url: /ru/python-net/aspose.gis.rendering.symbolizers/simplemarker/
---

**Summary:** Simple point symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleMarker

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [SimpleMarker()](#SimpleMarker__1) | Инициализирует новый экземпляр класса [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/). |
| [SimpleMarker(other)](#SimpleMarker_other_2) | Инициализирует новый экземпляр класса [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| fill_color | System.Drawing.Color | r/w | Указывает цвет и прозрачность для заполнения. |
| horizontal_anchor_point | [HorizontalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/horizontalanchor) | r/w | Указывает, какая сторона формы маркера будет выровнена по горизонтали с расположением точки. |
| horizontal_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает горизонтальное смещение от положения точки до точки привязки формы. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Элемент [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ничего не рисует и фактически пропускает отрисовку геометрии, к которой он применён. |
| вращение | double | r/w | Указывает вращение символа вокруг его центральной точки в десятичных градусах.<br/>            Положительные значения означают вращение по часовой стрелке, отрицательные — против часовой стрелки. |
| shape_type | [MarkerShapeType](/psd/python-net/aspose.gis.rendering.symbolizers/markershapetype) | r/w | Указывает форму маркера. |
| size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает размер маркера. |
| stroke_color | System.Drawing.Color | r/w | Указывает цвет и прозрачность, задаваемые линии. |
| stroke_dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает расстояние от начала линии до начала шаблона штриха. |
| stroke_dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | Указывает массив расстояний, определяющий длину чередующихся тире и пробелов<br/>            в пунктирных линиях. |
| stroke_line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | Определяет, как линии отображаются при пересечении отрезков. |
| stroke_style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | Указывает, как должны быть нарисованы линии символа. |
| stroke_width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает ширину линии. |
| vertical_anchor_point | [VerticalAnchor](/psd/python-net/aspose.gis.rendering.symbolizers/verticalanchor) | r/w | Указывает, какая сторона формы маркера будет выровнена по вертикали с точкой расположения. |
| vertical_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает вертикальное смещение от положения точки до точки привязки формы. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |


### Constructor: SimpleMarker() {#SimpleMarker__1}


```
 SimpleMarker() 
```

Инициализирует новый экземпляр класса [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/).

### Constructor: SimpleMarker(other) {#SimpleMarker_other_2}


```
 SimpleMarker(other) 
```

Инициализирует новый экземпляр класса [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | Другой [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker/), из которого копировать данные. |

### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [SimpleMarker](/psd/python-net/aspose.gis.rendering.symbolizers/simplemarker) | Клон этого экземпляра. |


