---
title: "类 VectorMapLayer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Rendering.VectorMapLayer 类。Map 中表示矢量图层数据的图层"
type: docs
weight: 4450
url: /zh/net/aspose.gis.rendering/vectormaplayer/
---
## VectorMapLayer class

[`Map`](../map/) 中表示矢量图层数据的图层。

```csharp
public class VectorMapLayer : MapLayer
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [VectorMapLayer](vectormaplayer/#constructor)(FeaturesSequence) | 使用默认符号器创建新实例。 |
| [VectorMapLayer](vectormaplayer/#constructor_1)(FeaturesSequence, VectorSymbolizer) | 使用默认符号器创建新实例。 |
| [VectorMapLayer](vectormaplayer/#constructor_6)(VectorLayer, bool) | 使用默认符号器创建新实例。 |
| [VectorMapLayer](vectormaplayer/#constructor_5)(VectorLayer, VectorSymbolizer, bool) | 创建新实例。 |
| [VectorMapLayer](vectormaplayer/#constructor_2)(FeaturesSequence, VectorSymbolizer, Labeling, SpatialReferenceSystem) | 使用默认符号器创建新实例。 |
| [VectorMapLayer](vectormaplayer/#constructor_4)(VectorLayer, VectorSymbolizer, Labeling, bool) | 创建新实例。 |
| [VectorMapLayer](vectormaplayer/#constructor_3)(VectorLayer, VectorSymbolizer, Labeling, SpatialReferenceSystem, bool) | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FeaturesSequence](../../aspose.gis.rendering/vectormaplayer/featuressequence/) { get; } | 此 `VectorMapLayer` 所表示的要素序列。 |
| [Labeling](../../aspose.gis.rendering/vectormaplayer/labeling/) { get; set; } | 指定地图图层的扭曲选项。 |
| [Opacity](../../aspose.gis.rendering/maplayer/opacity/) { get; set; } | 图层的不透明度。 |
| [Symbolizer](../../aspose.gis.rendering/vectormaplayer/symbolizer/) { get; set; } | 用于渲染图层要素的符号器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| override [Dispose](../../aspose.gis.rendering/vectormaplayer/dispose/)() | 释放资源。 |
| [ImportSld](../../aspose.gis.rendering/vectormaplayer/importsld/#importsld)(AbstractPath, SldImportOptions) | 从指定路径下的 Styled Layer Descriptor 文件导入样式。 |
| [ImportSld](../../aspose.gis.rendering/vectormaplayer/importsld/#importsld_1)(string, SldImportOptions) | 从指定路径下的 Styled Layer Descriptor 文件导入样式。 |
| [ImportSldFromString](../../aspose.gis.rendering/vectormaplayer/importsldfromstring/)(string, SldImportOptions) | 从指定的 Styled Layer Descriptor 字符串导入样式。 |

### 另见

* class [MapLayer](../maplayer/)
* namespace [Aspose.Gis.Rendering](../../aspose.gis.rendering/)
* assembly [Aspose.GIS](../../)


