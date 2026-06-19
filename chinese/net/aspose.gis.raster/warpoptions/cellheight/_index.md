---
title: "WarpOptions.CellHeight"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "WarpOptions 属性。指定以目标地理参考单位的栅格单元格的新高度。如果该值设置为 0，CellHeight 将自动计算。默认值为 0"
type: docs
weight: 20
url: /zh/net/aspose.gis.raster/warpoptions/cellheight/
---
## WarpOptions.CellHeight property

指定栅格单元的新高度（以目标地理参考单位计）。如果该值设置为 0，`CellHeight` 将自动计算。默认值为 \"0\"。

```csharp
public double CellHeight { get; set; }
```

## 备注

如果单元格高度设置为 0，值将取自原始单元格高度或通过[`Height`](../height/)计算。请注意，`CellHeight` 不能与[`Height`](../height/)一起使用。

### 另见

* class [WarpOptions](../)
* namespace [Aspose.Gis.Raster](../../warpoptions/)
* assembly [Aspose.GIS](../../../)


