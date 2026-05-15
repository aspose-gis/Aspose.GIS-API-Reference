---
title: "WarpOptions.CellWidth"
second_title: "Aspose.GIS for .NET API 参考"
description: "WarpOptions 属性。指定目标地理参考单位中栅格单元的新宽度。如果该值设为 0，则自动计算 CellWidth。默认值为 0"
type: docs
weight: 30
url: /zh/net/aspose.gis.raster/warpoptions/cellwidth/
---
## WarpOptions.CellWidth property

指定栅格单元的新宽度（以目标地理参考单位计）。如果该值设为 0，`CellWidth` 将自动计算。默认值为 "0"。

```csharp
public double CellWidth { get; set; }
```

## 备注

如果单元格宽度设为 0，则该值将取自原始单元格宽度或通过 [`Width`](../width/) 计算。注意 `CellWidth` 不能与 [`Width`](../width/) 同时使用。

### 另见

* class [WarpOptions](../)
* namespace [Aspose.Gis.Raster](../../warpoptions/)
* assembly [Aspose.GIS](../../../)


