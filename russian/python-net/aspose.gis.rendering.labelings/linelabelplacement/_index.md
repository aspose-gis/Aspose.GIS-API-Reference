---
title: "Класс LineLabelPlacement"
type: docs
weight: 40
url: /ru/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | Создаёт новый экземпляр. |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | Создаёт новый экземпляр. |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | Указывает, как метка выравнивается по линейному пути. По умолчанию используется [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/). |
| max_angle_delta | double | r/w | При использовании с [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/) задаёт максимальный угол в градусах между двумя<br/>            последовательными символами в изогнутой метке. По умолчанию 25. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Смещение от линейного пути.<br/>            Положительные значения смещают влево от линии, отрицательные — вправо. По умолчанию 0. |
## **Methods**
| **Name** | **Описание** |
| :- | :- |
| [clone()](#clone__1) | Создаёт клон этого экземпляра. |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

Создаёт новый экземпляр.

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

Создаёт новый экземпляр.

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | Другой [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/) для копирования данных. |

### Method: clone() {#clone__1}


```
 clone() 
```

Создаёт клон этого экземпляра.

**Returns**

| Тип | Описание |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | Клон этого экземпляра. |


