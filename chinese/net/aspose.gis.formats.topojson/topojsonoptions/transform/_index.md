---
title: Transform
second_title: Aspose.GIS for .NET API 参考
description: 指定用于量化输出 TopoJSON 中的坐标和增量编码弧的变换对象
type: docs
weight: 60
url: /zh/net/aspose.gis.formats.topojson/topojsonoptions/transform/
---
## TopoJsonOptions.Transform property

指定用于量化输出 TopoJSON 中的坐标和增量编码弧的变换对象。

```csharp
public TopoJsonTransform Transform { get; set; }
```

### 评论

这是写入选项 - 它不影响读取。 此选项与[`QuantizationNumber`](../quantizationnumber)互斥 - 这两个选项中只有一个不能是`null`。 如果不是`null`- 输出 TopoJSON 坐标是量化的，并且弧是使用指定的 变换对象进行增量编码的。 有关转换对象的更多详细信息，请参阅 TopoJSON 规范。 默认为`null`。

### 也可以看看

* class [TopoJsonTransform](../../topojsontransform)
* class [TopoJsonOptions](../../topojsonoptions)
* 命名空间 [Aspose.Gis.Formats.TopoJson](../../topojsonoptions)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->