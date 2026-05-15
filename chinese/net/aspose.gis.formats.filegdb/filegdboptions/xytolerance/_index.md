---
title: "FileGdbOptions.XYTolerance"
second_title: "Aspose.GIS for .NET API 参考"
description: "FileGdbOptions 属性。X 和 Y 方向的捕捉容差"
type: docs
weight: 100
url: /zh/net/aspose.gis.formats.filegdb/filegdboptions/xytolerance/
---
## FileGdbOptions.XYTolerance property

X 和 Y 捕捉容差。

```csharp
public double? XYTolerance { get; set; }
```

## 备注

这是一个创建选项，不影响读取和编辑。此参数控制用于高级 ArcGIS 功能的捕捉容差。它不影响 Aspose.GIS 的行为，但可被 ArcGIS 使用。该参数的单位与空间参考系统的单位相同。如果设置为 `null`，将使用默认值。默认值取决于空间参考系统：对地理坐标系统为 0.000000008983153 度，对投影坐标系统为 0.001 米（数值会转换为空间参考系统的单位）。如果空间参考系统未知，默认值为 0.001。

### 另见

* class [FileGdbOptions](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdboptions/)
* assembly [Aspose.GIS](../../../)


