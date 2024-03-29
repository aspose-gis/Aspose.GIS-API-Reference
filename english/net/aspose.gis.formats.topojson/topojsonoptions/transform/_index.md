---
title: TopoJsonOptions.Transform
second_title: Aspose.GIS for .NET API Reference
description: TopoJsonOptions property. Specifies transform object to use to quantize coordinates and deltaencode arcs in output TopoJSON
type: docs
weight: 60
url: /net/aspose.gis.formats.topojson/topojsonoptions/transform/
---
## TopoJsonOptions.Transform property

Specifies transform object to use to quantize coordinates and delta-encode arcs in output TopoJSON.

```csharp
public TopoJsonTransform Transform { get; set; }
```

## Remarks

This is writing option - it does not affect reading. This option is mutually exclusive with [`QuantizationNumber`](../quantizationnumber/) - only one of this two options can be not `null`. If this is not `null` - output TopoJSON coordinates are quantized and arcs are delta-encoded with the specified transform object. Refer to TopoJSON specification for more details on transform object. Defaults to `null`.

### See Also

* class [TopoJsonTransform](../../topojsontransform/)
* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


