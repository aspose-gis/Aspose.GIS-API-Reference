---
title: "FileGdbCoordinatePrecisionGrid.CreateFromRectangle"
second_title: "Aspose.GIS for .NET API 参考"
description: "FileGdbCoordinatePrecisionGrid 方法。创建新的 FileGdbCoordinatePrecisionGrid，使矩形内的所有值均可表示。"
type: docs
weight: 20
url: /zh/net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/createfromrectangle/
---
## FileGdbCoordinatePrecisionGrid.CreateFromRectangle method

创建新的 `FileGdbCoordinatePrecisionGrid`，使矩形内的所有值都可表示。

```csharp
public static FileGdbCoordinatePrecisionGrid CreateFromRectangle(IPoint p1, IPoint p2)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| p1 | IPoint | 矩形的一个角点。 |
| p2 | IPoint | 矩形的对角角点。必须与 *p1* 具有相同的尺寸。 |

### 返回值

`FileGdbCoordinatePrecisionGrid` 使矩形内的所有值均可表示。矩形外的值不可表示，因此写入 FileGDB 图层的所有坐标必须位于矩形内部。

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| ArgumentException | *p1* 和 *p2* 未形成有效的非空矩形：*p1* 或 *p2* 为空。*p1* 的 'HasZ' 标志不等于 *p2* 的 'HasZ' 标志；*p1* 的 'HasM' 标志不等于 *p2* 的 'HasM' 标志；*p1* 的 'X' 坐标等于 *p2* 的 'X' 坐标；*p1* 的 'Y' 坐标等于 *p2* 的 'Y' 坐标；*p1* 的 'Z' 坐标等于 *p2* 的 'Z' 坐标；*p1* 的 'M' 坐标等于 *p2* 的 'M' 坐标。任何坐标为 NaN 或无穷大。 |

### 另见

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [FileGdbCoordinatePrecisionGrid](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbcoordinateprecisiongrid/)
* assembly [Aspose.GIS](../../../)


