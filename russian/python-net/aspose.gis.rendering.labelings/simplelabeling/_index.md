---
title: "Класс SimpleLabeling"
type: docs
weight: 80
url: /ru/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Инициализирует новый экземпляр класса [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Инициализирует новый экземпляр класса [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Инициализирует новый экземпляр класса [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | Определяет цвет текста. |
| font_family | string | r/w | Семейство шрифтов, используемое для отображения текста. По умолчанию значение зависит от системы. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Размер текста. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Стиль, применяемый к тексту. |
| halo_color | System.Drawing.Color | r/w | Цвет ореола (обводки) вокруг текста. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Размер ореола (обводки) вокруг текста. |
| label_attribute | string | r/w | Имя атрибута, используемое в качестве источника меток. Игнорируется, если установлен [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).<br/>            Либо [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) или [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) должны быть установлены перед рендерингом;<br/>            В противном случае выбрасывается InvalidOperationException. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Указывает поведение рендеринга для многосоставных геометрий. По умолчанию — [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Получает экземпляр [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | Размещение меток указывает, как метки размещаются относительно геометрий объектов. |
| приоритет | int | r/w | Указывает приоритет этой метки в случае перекрытия с другой меткой. Метка с более низким приоритетом не отображается.<br/>            По умолчанию — 1000. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Инициализирует новый экземпляр класса [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Инициализирует новый экземпляр класса [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| label_attribute | string | Имя атрибута, используемое в качестве источника меток. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Инициализирует новый экземпляр класса [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Другой [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) для копирования данных. |

### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Клон этого экземпляра. |


