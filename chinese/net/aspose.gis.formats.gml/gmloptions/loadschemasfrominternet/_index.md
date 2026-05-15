---
title: "GmlOptions.LoadSchemasFromInternet"
second_title: "Aspose.GIS for .NET API 参考"
description: "GmlOptions 属性。确定是否允许 Aspose.GIS 从 Internet 加载 XML 架构。如果设置为 false，则不会加载以 file// 开头的绝对 URI 的架构。默认值为 false。"
type: docs
weight: 20
url: /zh/net/aspose.gis.formats.gml/gmloptions/loadschemasfrominternet/
---
## GmlOptions.LoadSchemasFromInternet property

确定是否允许 Aspose.GIS 从互联网加载 XML 模式。如果设置为 `false`，则不会加载以非 'file://' 开头的绝对 URI 的模式。默认值为 `false`。

```csharp
public bool LoadSchemasFromInternet { get; set; }
```

## 备注

Aspose.GIS 使用 GML 文件的 XML 架构来创建 [`FeatureAttributeCollection`](../../../aspose.gis/featureattributecollection/)。XML 架构文件可以与 GML 文件一起分发，也可以位于 Internet 上。在前一种情况下，您需要将此选项设置为 `true`，以允许 Aspose.GIS 加载 XML 架构。

### 另见

* class [GmlOptions](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmloptions/)
* assembly [Aspose.GIS](../../../)


