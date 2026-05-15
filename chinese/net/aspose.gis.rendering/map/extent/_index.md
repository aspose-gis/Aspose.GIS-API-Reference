---
title: "Map.Extent"
second_title: "Aspose.GIS for .NET API 参考"
description: "Map 属性。指定要渲染的地图范围。如果设置为 null，则在渲染期间计算范围，以包含所有图层中的所有几何体。"
type: docs
weight: 40
url: /zh/net/aspose.gis.rendering/map/extent/
---
## Map.Extent property

指定要渲染的地图范围。如果设置为 `null`，则在渲染期间计算范围，以包含所有图层中的所有几何体。

```csharp
public Extent Extent { get; set; }
```

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentException | [`IsValid`](../../../aspose.gis/extent/isvalid/) 为 `false`。[`Width`](../../../aspose.gis/extent/width/) 小于或等于零。[`Height`](../../../aspose.gis/extent/height/) 小于或等于零。[`SpatialReferenceSystem`](../../../aspose.gis/extent/spatialreferencesystem/) 为 `null`。 |

## 备注

如果范围的空间参考系统不等于地图的空间参考系统，范围将在渲染期间被转换到目标空间参考系统。

### 另见

* class [Extent](../../../aspose.gis/extent/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)


