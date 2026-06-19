---
title: "FileGdbOptions.ZTolerance"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "FileGdbOptions 属性。Z 方向捕捉容差"
type: docs
weight: 110
url: /zh/net/aspose.gis.formats.filegdb/filegdboptions/ztolerance/
---
## FileGdbOptions.ZTolerance property

Z 捕捉容差。

```csharp
public double? ZTolerance { get; set; }
```

## 备注

这是一个创建选项，不影响读取和编辑。此参数控制用于高级 ArcGIS 功能的捕捉容差。它不影响 Aspose.GIS 的行为，但可被 ArcGIS 使用。参数的单位与空间参考系统的单位相同。如果设置为 `null`，则使用默认值。如果空间参考系统未知或维度少于三维，默认值为 0.001。如果空间参考系统具有三维，则默认值为 0.001 米，转换为第三维的单位。

### 另见

* class [FileGdbOptions](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdboptions/)
* assembly [Aspose.GIS](../../../)


