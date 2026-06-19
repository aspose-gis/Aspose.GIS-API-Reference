---
title: "WarpOptions.Width"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "WarpOptions 属性。指定输出栅格的宽度（以像素和列计）。如果该值设置为 0，宽度将自动计算。默认值为 0。"
type: docs
weight: 80
url: /zh/net/aspose.gis.raster/warpoptions/width/
---
## WarpOptions.Width property

指定输出栅格的宽度（以像素和列数计）。如果该值设置为 0，则会自动计算宽度。默认值为 \"0\"。

```csharp
public int Width { get; set; }
```

## 备注

如果宽度设置为 0，值将取自原始宽度或通过[`CellWidth`](../cellwidth/)计算。请注意，`Width` 不能与[`CellWidth`](../cellwidth/)一起使用。

### 另见

* class [WarpOptions](../)
* namespace [Aspose.Gis.Raster](../../warpoptions/)
* assembly [Aspose.GIS](../../../)


