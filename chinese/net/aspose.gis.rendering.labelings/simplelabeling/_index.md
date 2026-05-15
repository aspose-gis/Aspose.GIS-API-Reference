---
title: "类 SimpleLabeling"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Rendering.Labelings.SimpleLabeling 类。简单标注将在每个要素上放置标签"
type: docs
weight: 4150
url: /zh/net/aspose.gis.rendering.labelings/simplelabeling/
---
## SimpleLabeling class

简单标注在每个要素上放置标签。

```csharp
public class SimpleLabeling : Labeling
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [SimpleLabeling](simplelabeling/#constructor)() | 初始化 `SimpleLabeling` 类的新实例。 |
| [SimpleLabeling](simplelabeling/#constructor_1)(SimpleLabeling) | 初始化 `SimpleLabeling` 类的新实例。 |
| [SimpleLabeling](simplelabeling/#constructor_2)(string) | 初始化 `SimpleLabeling` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [FeatureBasedConfiguration](../../aspose.gis.rendering.labelings/simplelabeling/featurebasedconfiguration/) { get; set; } | 在处理要素之前用于配置此标注的回调函数。 |
| [FontColor](../../aspose.gis.rendering.labelings/simplelabeling/fontcolor/) { get; set; } | 确定文本颜色。 |
| [FontFamily](../../aspose.gis.rendering.labelings/simplelabeling/fontfamily/) { get; set; } | 用于渲染文本的字体族。默认值取决于系统。 |
| [FontSize](../../aspose.gis.rendering.labelings/simplelabeling/fontsize/) { get; set; } | 文本大小。 |
| [FontStyle](../../aspose.gis.rendering.labelings/simplelabeling/fontstyle/) { get; set; } | 应用于文本的样式。 |
| [GeometryExpression](../../aspose.gis.rendering.labelings/simplelabeling/geometryexpression/) { get; set; } | 提供一种方法，用标注修改后的几何体替代要素几何体。此回调在 [`FeatureBasedConfiguration`](./featurebasedconfiguration/) 之后首次被调用。默认值为 `null`（使用原始要素几何体）。 |
| [HaloColor](../../aspose.gis.rendering.labelings/simplelabeling/halocolor/) { get; set; } | 文本周围光晕（描边）的颜色。 |
| [HaloSize](../../aspose.gis.rendering.labelings/simplelabeling/halosize/) { get; set; } | 文本周围光晕（描边）的大小。 |
| [LabelAttribute](../../aspose.gis.rendering.labelings/simplelabeling/labelattribute/) { get; set; } | 用作标签来源的属性名称。如果已设置 [`LabelExpression`](./labelexpression/) 则忽略。必须在渲染前设置 [`LabelAttribute`](./labelattribute/) 或 [`LabelExpression`](./labelexpression/) 之一；否则会抛出 InvalidOperationException。 |
| [LabelExpression](../../aspose.gis.rendering.labelings/simplelabeling/labelexpression/) { get; set; } | 提供一种自定义和格式化标签文本的方法。如果设置，则覆盖 [`LabelAttribute`](./labelattribute/)。必须在渲染前设置 [`LabelAttribute`](./labelattribute/) 或 [`LabelExpression`](./labelexpression/) 之一；否则会抛出 InvalidOperationException。 |
| [MultipartMode](../../aspose.gis.rendering.labelings/simplelabeling/multipartmode/) { get; set; } | 指定多部件几何体的渲染行为。默认是 All。 |
| [Placement](../../aspose.gis.rendering.labelings/simplelabeling/placement/) { get; set; } | 标签放置指定标签相对于要素几何体的放置方式。 |
| [Priority](../../aspose.gis.rendering.labelings/simplelabeling/priority/) { get; set; } | 指示该标签在与其他标签重叠时的优先级。优先级较低的标签不会被渲染。默认值为 1000。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Clone](../../aspose.gis.rendering.labelings/simplelabeling/clone/)() | 克隆此实例。 |

### 另见

* class [Labeling](../labeling/)
* namespace [Aspose.Gis.Rendering.Labelings](../../aspose.gis.rendering.labelings/)
* assembly [Aspose.GIS](../../)


