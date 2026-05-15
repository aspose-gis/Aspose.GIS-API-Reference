---
title: "类 Map"
second_title: "Aspose.GIS for .NET API 参考"
description: "Aspose.Gis.Rendering.Map 类。Map 是一个图层集合，可通过 Renderer 叠加渲染。"
type: docs
weight: 4170
url: /zh/net/aspose.gis.rendering/map/
---
## Map class

Map 是一个图层集合，可通过 [`Renderer`](../renderer/) 叠加渲染。

```csharp
public class Map : IDisposable, IReadOnlyList<MapLayer>
```

## 构造函数

| 名称 | 描述 |
| --- | --- |
| [Map](map/#constructor)() | 创建 `Map` 类的新实例。 |
| [Map](map/#constructor_1)(Measurement, Measurement) | 创建 `Map` 类的新实例。 |

## 属性

| 名称 | 描述 |
| --- | --- |
| [BackgroundColor](../../aspose.gis.rendering/map/backgroundcolor/) { get; set; } | 地图的背景颜色。默认是透明。 |
| [Count](../../aspose.gis.rendering/map/count/) { get; } | 获取地图中图层的数量。 |
| [Extent](../../aspose.gis.rendering/map/extent/) { get; set; } | 指定要渲染的地图范围。如果设置为 `null`，则在渲染期间计算范围，以包含所有图层中的所有几何体。 |
| [Height](../../aspose.gis.rendering/map/height/) { get; set; } | 地图的可视高度。 |
| [Item](../../aspose.gis.rendering/map/item/) { get; } | 获取指定索引处的图层。 |
| [Padding](../../aspose.gis.rendering/map/padding/) { get; set; } | 指定要添加到范围的填充。 |
| [Resolution](../../aspose.gis.rendering/map/resolution/) { get; set; } | 用于渲染此地图以及在 [`Measurement`](../measurement/) 之间转换的分辨率。默认值为 96。 |
| [SpatialReferenceSystem](../../aspose.gis.rendering/map/spatialreferencesystem/) { get; set; } | 地图的 [`SpatialReferenceSystem`](./spatialreferencesystem/)。 |
| [Width](../../aspose.gis.rendering/map/width/) { get; set; } | 地图的可视宽度。 |

## 方法

| 名称 | 描述 |
| --- | --- |
| [Add](../../aspose.gis.rendering/map/add/#add)(FeaturesSequence) | 创建并添加一个 [`VectorMapLayer`](../vectormaplayer/) 到地图。图层按添加顺序渲染。 |
| [Add](../../aspose.gis.rendering/map/add/#add_4)(MapLayer) | 向地图添加图层。图层按添加顺序渲染。 |
| [Add](../../aspose.gis.rendering/map/add/#add_1)(FeaturesSequence, VectorSymbolizer) | 创建并添加一个 [`VectorMapLayer`](../vectormaplayer/) 到地图。图层按添加顺序渲染。 |
| [Add](../../aspose.gis.rendering/map/add/#add_8)(VectorLayer, bool) | 创建一个带有默认符号化器的 [`VectorMapLayer`](../vectormaplayer/)，并将其添加到地图。图层按添加顺序渲染。 |
| [Add](../../aspose.gis.rendering/map/add/#add_2)(FeaturesSequence, VectorSymbolizer, Labeling) | 创建并添加一个 [`VectorMapLayer`](../vectormaplayer/) 到地图。图层按添加顺序渲染。 |
| [Add](../../aspose.gis.rendering/map/add/#add_3)(RasterLayer, RasterColorizer, bool) | 创建一个带有默认颜色化器的 [`RasterMapLayer`](../rastermaplayer/)，并将其添加到地图。 |
| [Add](../../aspose.gis.rendering/map/add/#add_7)(VectorLayer, VectorSymbolizer, bool) | 创建并添加一个 [`VectorMapLayer`](../vectormaplayer/) 到地图。图层按添加顺序渲染。 |
| [Add](../../aspose.gis.rendering/map/add/#add_6)(VectorLayer, VectorSymbolizer, Labeling, bool) | 创建并添加一个 [`VectorMapLayer`](../vectormaplayer/) 到地图。图层按添加顺序渲染。 |
| [Add](../../aspose.gis.rendering/map/add/#add_5)(VectorLayer, VectorSymbolizer, Labeling, SpatialReferenceSystem, bool) | 创建并添加一个 [`VectorMapLayer`](../vectormaplayer/) 到地图。图层按添加顺序渲染。 |
| [Dispose](../../aspose.gis.rendering/map/dispose/)() | 释放资源。 |
| [GetEnumerator](../../aspose.gis.rendering/map/getenumerator/)() | 返回一个枚举器，用于遍历地图中的图层。 |
| [Render](../../aspose.gis.rendering/map/render/#render)(AbstractPath, Renderer) | 将地图渲染到文件中。 |
| [Render](../../aspose.gis.rendering/map/render/#render_1)(string, Renderer) | 将地图渲染到文件中。 |

### 另见

* class [MapLayer](../maplayer/)
* namespace [Aspose.Gis.Rendering](../../aspose.gis.rendering/)
* assembly [Aspose.GIS](../../)


