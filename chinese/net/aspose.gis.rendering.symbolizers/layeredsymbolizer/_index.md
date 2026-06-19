---
title: "类 LayeredSymbolizer"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Rendering.Symbolizers.LayeredSymbolizer 类。一个渲染多个其他符号器的符号器"
type: docs
weight: 4280
url: /zh/net/aspose.gis.rendering.symbolizers/layeredsymbolizer/
---
## LayeredSymbolizer class

一个渲染多个其他符号器的符号器。

```csharp
public class LayeredSymbolizer : VectorSymbolizer, IReadOnlyList<VectorSymbolizer>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [LayeredSymbolizer](layeredsymbolizer/#constructor)() | 创建新实例。 |
| [LayeredSymbolizer](layeredsymbolizer/#constructor_1)(RenderingOrder) | 创建新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/count/) { get; } | 获取符号器的数量。 |
| [Item](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/item/) { get; } | 获取指定索引处的符号器。 |
| [RenderingOrder](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/renderingorder/) { get; set; } | 确定渲染顺序。ByFeatures - 为特征渲染所有符号器，然后继续下一个特征。ByLayers - 使用该符号器渲染所有特征，然后继续下一个符号器。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/add/)(VectorSymbolizer) | 添加指定的符号器。 |
| [GetEnumerator](../../aspose.gis.rendering.symbolizers/layeredsymbolizer/getenumerator/)() | 返回一个遍历集合的枚举器。 |

### 另见

* class [VectorSymbolizer](../vectorsymbolizer/)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../aspose.gis.rendering.symbolizers/)
* assembly [Aspose.GIS](../../)


