---
title: "TopoJsonOptions.Transform"
second_title: "Aspose.GIS for .NET API 参考"
description: "TopoJsonOptions 属性。指定用于在输出 TopoJSON 中量化坐标和对弧线进行 delta 编码的变换对象"
type: docs
weight: 60
url: /zh/net/aspose.gis.formats.topojson/topojsonoptions/transform/
---
## TopoJsonOptions.Transform property

指定用于在输出 TopoJSON 中量化坐标并对弧线进行增量编码的变换对象。

```csharp
public TopoJsonTransform Transform { get; set; }
```

## 备注

这是写入选项——它不影响读取。此选项与 [`QuantizationNumber`](../quantizationnumber/) 互斥——这两个选项只能有一个不为 `null`。如果此项不为 `null`——输出 TopoJSON 坐标将被量化，弧线将使用指定的变换对象进行 delta 编码。请参阅 TopoJSON 规范以获取有关变换对象的更多详细信息。默认值为 `null`。

### 另见

* class [TopoJsonTransform](../../topojsontransform/)
* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


