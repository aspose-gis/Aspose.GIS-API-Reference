---
title: "TopoJsonOptions.Transform"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "TopoJsonOptions 属性。指定用于对输出 TopoJSON 中的坐标进行量化以及对弧线进行 delta 编码的变换对象"
type: docs
weight: 60
url: /zh/net/aspose.gis.formats.topojson/topojsonoptions/transform/
---
## TopoJsonOptions.Transform property

指定用于对坐标进行量化并在输出 TopoJSON 中对弧线进行差分编码的变换对象。

```csharp
public TopoJsonTransform Transform { get; set; }
```

## 备注

这是写入选项——它不影响读取。此选项与 [`QuantizationNumber`](../quantizationnumber/) 互斥——这两个选项只能有一个不为 `null`。如果此项不为 `null`，则输出的 TopoJSON 坐标将被量化，弧线将使用指定的变换对象进行 delta 编码。有关变换对象的更多细节，请参阅 TopoJSON 规范。默认值为 `null`。

### 另见

* class [TopoJsonTransform](../../topojsontransform/)
* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


