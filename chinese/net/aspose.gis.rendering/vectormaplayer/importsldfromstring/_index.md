---
title: "VectorMapLayer.ImportSldFromString"
second_title: "Aspose.GIS for .NET API 参考"
description: "VectorMapLayer 方法。从指定的 Styled Layer Descriptor 字符串导入样式"
type: docs
weight: 70
url: /zh/net/aspose.gis.rendering/vectormaplayer/importsldfromstring/
---
## VectorMapLayer.ImportSldFromString method

从指定的 Styled Layer Descriptor 字符串导入样式。

```csharp
public void ImportSldFromString(string sld, SldImportOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| sld | String | Styled Layer Descriptor。 |
| options | SldImportOptions | 导入选项。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 参数为 `null`。 |
| XmlException | 解析 XML 时发生错误。 |
| FormatException | 在 XML 中未找到 SLD 样式。 |

## 备注

此方法会覆盖 [`Symbolizer`](../symbolizer/) 属性的值。

### 另见

* class [SldImportOptions](../../../aspose.gis.rendering.sld/sldimportoptions/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)


