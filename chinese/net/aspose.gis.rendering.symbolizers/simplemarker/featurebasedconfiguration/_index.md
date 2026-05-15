---
title: "SimpleMarker.FeatureBasedConfiguration"
second_title: "Aspose.GIS for .NET API 参考"
description: "SimpleMarker 属性。一个回调，用于在渲染特征之前配置此符号化器"
type: docs
weight: 20
url: /zh/net/aspose.gis.rendering.symbolizers/simplemarker/featurebasedconfiguration/
---
## SimpleMarker.FeatureBasedConfiguration property

一个回调，用于在渲染要素之前配置此symbolizer。

```csharp
public Action<Feature, SimpleMarker> FeatureBasedConfiguration { get; set; }
```

## 备注

此回调在渲染每个要素之前被调用。它接受即将渲染的要素以及此符号化器的克隆。通过更改克隆的属性，可以根据要素的属性更新符号化器的行为。

### 另见

* class [Feature](../../../aspose.gis/feature/)
* class [SimpleMarker](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../simplemarker/)
* assembly [Aspose.GIS](../../../)


