---
title: "MapInfoTabOptions.TextStringAttribute"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "MapInfoTabOptions 属性。指定表示 Text 图形对象文本的属性名称"
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.mapinfotab/mapinfotaboptions/textstringattribute/
---
## MapInfoTabOptions.TextStringAttribute property

指定表示 'Text' 图形对象文本的属性名称。

```csharp
public string TextStringAttribute { get; set; }
```

## 备注

MapInfo Tab 格式指定一种类型为 'Text' 的图形对象。'Text' 图形对象表示地图上的标签。我们将 'Text' 图形对象导出为一个带有 [`Feature`](../../../aspose.gis/feature/) 的对象，使用 [`Polygon`](../../../aspose.gis.geometries/polygon/) 几何来界定标签范围。标签的文本导出为 [`FeatureAttribute`](../../../aspose.gis/featureattribute/)。此属性指定用于导出标签文本的属性名称。默认值为 `\"textstring\"`。

### 另见

* class [MapInfoTabOptions](../)
* namespace [Aspose.Gis.Formats.MapInfoTab](../../mapinfotaboptions/)
* assembly [Aspose.GIS](../../../)


