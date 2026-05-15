---
title: "VectorMapLayer.ImportSld"
second_title: "Aspose.GIS for .NET API 参考"
description: "VectorMapLayer 方法。从指定路径下的 Styled Layer Descriptor 文件导入样式"
type: docs
weight: 60
url: /zh/net/aspose.gis.rendering/vectormaplayer/importsld/
---
## ImportSld(string, SldImportOptions) {#importsld_1}

从指定路径的 Styled Layer Descriptor 文件导入样式。

```csharp
public void ImportSld(string path, SldImportOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | String | Styled Layer Descriptor 文件的路径。 |
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

---

## ImportSld(AbstractPath, SldImportOptions) {#importsld}

从指定路径的 Styled Layer Descriptor 文件导入样式。

```csharp
public void ImportSld(AbstractPath path, SldImportOptions options = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | Styled Layer Descriptor 文件的路径。 |
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

* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [SldImportOptions](../../../aspose.gis.rendering.sld/sldimportoptions/)
* class [VectorMapLayer](../)
* namespace [Aspose.Gis.Rendering](../../vectormaplayer/)
* assembly [Aspose.GIS](../../../)


