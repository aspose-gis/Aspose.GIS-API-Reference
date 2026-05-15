---
title: "LineLabelPlacement 类"
type: docs
weight: 40
url: /zh/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **描述** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | 创建新实例。 |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | 创建新实例。 |
## **Properties**
| **Name** | **Type** | **Access** | **描述** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | 指定标签如何与线性路径对齐。默认是 [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/)。 |
| max_angle_delta | double | r/w | 当与 [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/) 一起使用时，设置弯曲标签中两个<br/>后续字符之间的最大角度（度）。默认是 25。 |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | 线性路径的偏移。<br/>正值向线的左侧偏移，负值向右侧偏移。默认是 0。 |
## **Methods**
| **Name** | **描述** |
| :- | :- |
| [clone()](#clone__1) | 克隆此实例。 |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

创建新实例。

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

创建新实例。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | 要从中复制数据的另一个 [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/)。 |

### Method: clone() {#clone__1}


```
 clone() 
```

克隆此实例。

**Returns**

| 类型 | 描述 |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | 此实例的克隆。 |


