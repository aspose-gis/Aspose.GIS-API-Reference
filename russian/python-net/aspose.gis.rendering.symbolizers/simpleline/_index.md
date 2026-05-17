---
title: "SimpleLine Класс"
type: docs
weight: 120
url: /ru/python-net/aspose.gis.rendering.symbolizers/simpleline/
---

**Summary:** Simple line symbolizer.

**Module:** [aspose.gis.rendering.symbolizers](/psd/python-net/aspose.gis.rendering.symbolizers/)

**Full Name:** aspose.gis.rendering.symbolizers.SimpleLine

**Inheritance:** VectorSymbolizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [SimpleLine()](#SimpleLine__1) | Создаёт новый экземпляр. |
| [SimpleLine(other)](#SimpleLine_other_2) | Инициализирует новый экземпляр класса [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| cap_style | [CapStyle](/psd/python-net/aspose.gis.rendering/capstyle) | r/w | Указывает, как линии отрисовываются на их концах. |
| color | System.Drawing.Color | r/w | Указывает цвет и прозрачность, задаваемые линии. |
| dash_offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает расстояние от начала линии до начала шаблона штриха. |
| dash_pattern | System.Collections.Generic.IEnumerable<Measurement> | r/w | Указывает массив расстояний, определяющий длину чередующихся тире и пробелов<br/>            в пунктирных линиях. |
| line_join | [LineJoin](/psd/python-net/aspose.gis.rendering/linejoin) | r/w | Определяет, как линии отображаются при пересечении отрезков. |
| null [static] | [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer) | r | Элемент [NullVectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/nullvectorsymbolizer/) ничего не рисует и фактически пропускает отрисовку геометрии, к которой он применён. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает смещение от исходной линии.<br/>            Для положительного расстояния смещение будет находиться слева от входной линии (относительно направления линии).<br/>            Для отрицательного расстояния оно будет находиться справа. |
| style | [StrokeStyle](/psd/python-net/aspose.gis.rendering/strokestyle) | r/w | Указывает, как должны быть нарисованы линии символа. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Указывает ширину линии. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |


### Constructor: SimpleLine() {#SimpleLine__1}


```
 SimpleLine() 
```

Создаёт новый экземпляр.

### Constructor: SimpleLine(other) {#SimpleLine_other_2}


```
 SimpleLine(other) 
```

Инициализирует новый экземпляр класса [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | Другой [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline/) для копирования данных. |

### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [SimpleLine](/psd/python-net/aspose.gis.rendering.symbolizers/simpleline) | Клон этого экземпляра. |


