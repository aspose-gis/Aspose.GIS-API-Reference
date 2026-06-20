---
title: "FileGdbCoordinatePrecisionGrid 类"
type: docs
weight: 10
url: /zh/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | 初始化 FileGdbCoordinatePrecisionGrid 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | 获取或设置 M 坐标的原点。如果设置为 <see langword=\"null\" />，则使用默认值。 |
| m_scale | Nullable<double> | r/w | 获取或设置 M 坐标的比例。如果设置为 <see langword=\"null\" />，则使用默认值。 |
| x_origin | Nullable<double> | r/w | 获取或设置 X 坐标的原点。如果设置为 <see langword="null" /> 则使用默认值。 |
| xy_scale | Nullable<double> | r/w | 获取或设置 X 和 Y 坐标的比例。如果设置为 <see langword="null" /> 则使用默认值。 |
| y_origin | Nullable<double> | r/w | 获取或设置 Y 坐标的原点。如果设置为 <see langword="null" /> 则使用默认值。 |
| z_origin | Nullable<double> | r/w | 获取或设置 Z 坐标的原点。如果设置为 <see langword="null" /> 则使用默认值。 |
| z_scale | Nullable<double> | r/w | 获取或设置 Z 坐标的比例。如果设置为 <see langword="null" /> 则使用默认值。 |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | 创建新的 <c>FileGdbCoordinatePrecisionGrid</c>，使矩形内的所有值均可表示。 |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

初始化 FileGdbCoordinatePrecisionGrid 类的新实例

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

创建新的 <c>FileGdbCoordinatePrecisionGrid</c>，使矩形内的所有值均可表示。

**Parameters:**

| 参数 | 类型 | 描述 |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 矩形的一个角点。 |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | 矩形的对角点。必须与 <paramref name="p1" /> 具有相同的维度。 |

**Returns**

| 类型 | 描述 |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | 该 <c>FileGdbCoordinatePrecisionGrid</c> 使矩形内的所有值均可表示。<br/>            矩形外的值不可表示，因此所有写入 FileGDB 图层的坐标必须位于矩形内部。 |


