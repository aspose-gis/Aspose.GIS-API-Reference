---
title: "FileGdbOptions.EnsureValidCoordinatesRange"
second_title: "Aspose.GIS for .NET API 参考"
description: "FileGdbOptions 属性。坐标是否应在有效范围内"
type: docs
weight: 30
url: /zh/net/aspose.gis.formats.filegdb/filegdboptions/ensurevalidcoordinatesrange/
---
## FileGdbOptions.EnsureValidCoordinatesRange property

坐标是否应在有效范围内。

```csharp
public bool EnsureValidCoordinatesRange { get; set; }
```

## 备注

这是一个创建选项，不影响读取和编辑。如果设置为 `true`，在尝试写入超出有效范围的坐标时将抛出异常。如果设置为 `false`，此类坐标将静默写入。有效范围由 [`CoordinatePrecisionGrid`](../coordinateprecisiongrid/) 定义。请参阅 [`CoordinatePrecisionGrid`](../coordinateprecisiongrid/) 文档了解如何根据坐标精度网格确定有效范围。默认值为 `false`。

### 另见

* class [FileGdbOptions](../)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdboptions/)
* assembly [Aspose.GIS](../../../)


