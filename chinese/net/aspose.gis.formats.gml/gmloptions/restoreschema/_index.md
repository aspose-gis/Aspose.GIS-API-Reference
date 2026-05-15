---
title: "GmlOptions.RestoreSchema"
second_title: "Aspose.GIS for .NET API 参考"
description: "GmlOptions 属性。确定是否允许 Aspose.GIS 解析在缺少或无法加载 XML 架构的 Gml 文件中的属性。如果设置为 true，Aspose.GIS 读取器不需要 XML 架构的存在。默认值为 false。"
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.gml/gmloptions/restoreschema/
---
## GmlOptions.RestoreSchema property

确定是否允许 Aspose.GIS 在缺少或无法加载 XML 模式的 Gml 文件中解析属性。如果设置为 `true`，Aspose.GIS 读取器不需要 XML 模式的存在。默认值为 `false`。

```csharp
public bool RestoreSchema { get; set; }
```

## 备注

驱动程序尝试通过扫描文件并查找“已知”对象来自动解析要素类及其关联属性，以确定组织结构。虽然此方法容易出错，但即使关联的 XML 架构已丢失或无法从 Internet 加载，它仍能适用于 GML 文件，这是一大优势。

### 另见

* class [GmlOptions](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmloptions/)
* assembly [Aspose.GIS](../../../)


