---
title: "MarkerLine.FeatureBasedConfiguration"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "MarkerLine 属性。用于在渲染要素之前配置此符号化器的回调函数"
type: docs
weight: 20
url: /zh/net/aspose.gis.rendering.symbolizers/markerline/featurebasedconfiguration/
---
## MarkerLine.FeatureBasedConfiguration property

用于在渲染要素之前配置此符号器的回调。

```csharp
public Action<Feature, MarkerLine> FeatureBasedConfiguration { get; set; }
```

## 备注

此回调在渲染每个要素之前被调用。它接受即将渲染的要素以及此符号化器的克隆。通过更改克隆的属性，可以根据要素的属性更新符号化器的行为。

### 另见

* class [Feature](../../../aspose.gis/feature/)
* class [MarkerLine](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../markerline/)
* assembly [Aspose.GIS](../../../)


