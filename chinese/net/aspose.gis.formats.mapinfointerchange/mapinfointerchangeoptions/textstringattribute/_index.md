---
title: "MapInfoInterchangeOptions.TextStringAttribute"
second_title: "Aspose.GIS for .NET API 参考"
description: "MapInfoInterchangeOptions 属性。指定表示 Text 图形对象文本的属性名称"
type: docs
weight: 20
url: /zh/net/aspose.gis.formats.mapinfointerchange/mapinfointerchangeoptions/textstringattribute/
---
## MapInfoInterchangeOptions.TextStringAttribute property

指定表示 'Text' 图形对象文本的属性名称。

```csharp
public string TextStringAttribute { get; set; }
```

## 备注

MapInfo Interchange 格式指定一种类型为 'Text' 的图形对象。'Text' 图形对象表示地图上的标签。我们将 'Text' 图形对象导出为一个 [`Feature`](../../../aspose.gis/feature/)，其几何形状为包围标签的 [`Polygon`](../../../aspose.gis.geometries/polygon/)。标签的文本导出为 [`FeatureAttribute`](../../../aspose.gis/featureattribute/)。此属性指定用于导出标签文本的属性名称。默认值为 `"textstring"`。

### 另见

* class [MapInfoInterchangeOptions](../)
* namespace [Aspose.Gis.Formats.MapInfoInterchange](../../mapinfointerchangeoptions/)
* assembly [Aspose.GIS](../../../)


