---
title: "GmlOptions.SchemaLocation"
second_title: "Aspose.GIS for .NET API 参考"
description: "GmlOptions 属性。以空格分隔的 URI 对列表。每对中的第一个 URI 是命名空间的 URI，第二个 URI 是该命名空间的 XML 模式路径。如果设置为 null，GmlDriver 将尝试从文档根元素读取 schemaLocation。默认值为 null"
type: docs
weight: 50
url: /zh/net/aspose.gis.formats.gml/gmloptions/schemalocation/
---
## GmlOptions.SchemaLocation property

以空格分隔的 URI 对列表。每对中的第一个 URI 是命名空间的 URI，第二个 URI 是该命名空间的 XML 模式路径。如果设置为 `null`，[`GmlDriver`](../../gmldriver/) 将尝试从文档根元素读取 schemaLocation。默认值为 `null`。

```csharp
public string SchemaLocation { get; set; }
```

## 备注

Aspose.GIS 使用 GML 文件的 XML 架构来创建 [`FeatureAttributeCollection`](../../../aspose.gis/featureattributecollection/)。默认情况下，架构位置是从 schemaLocation 属性中提取的。如果没有此属性或它指向无效位置，Aspose.GIS 将无法读取 GML 文件。在这种情况下 - 设置此选项，以便 Aspose.GIS 能加载架构。

## 示例

"http://site.com/namespace http://site.com/schema.xsd"

### 另见

* class [GmlOptions](../)
* namespace [Aspose.Gis.Formats.Gml](../../gmloptions/)
* assembly [Aspose.GIS](../../../)


