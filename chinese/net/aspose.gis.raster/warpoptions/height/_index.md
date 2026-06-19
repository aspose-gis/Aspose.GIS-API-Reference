---
title: "WarpOptions.Height"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "WarpOptions 属性。指定输出栅格的高度（以像素和列计）。如果该值设置为 0，高度将自动计算。默认值为 0。"
type: docs
weight: 50
url: /zh/net/aspose.gis.raster/warpoptions/height/
---
## WarpOptions.Height property

指定输出栅格的高度（以像素和列数计）。如果该值设置为 0，则会自动计算高度。默认值为 \"0\"。

```csharp
public int Height { get; set; }
```

## 备注

如果高度设置为 0，值将取自原始高度或通过[`CellHeight`](../cellheight/)计算。请注意，`Height` 不能与[`CellHeight`](../cellheight/)一起使用。

### 另见

* class [WarpOptions](../)
* namespace [Aspose.Gis.Raster](../../warpoptions/)
* assembly [Aspose.GIS](../../../)


