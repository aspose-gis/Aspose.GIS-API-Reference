---
title: "MarkerCluster.FeaturesBasedConfiguration"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "MarkerCluster 属性。用于在渲染聚类中心之前配置此符号化器的回调"
type: docs
weight: 20
url: /zh/net/aspose.gis.rendering.symbolizers/markercluster/featuresbasedconfiguration/
---
## MarkerCluster.FeaturesBasedConfiguration property

在渲染簇中心之前，用于配置此符号器的回调。

```csharp
public Action<IEnumerable<Feature>, MarkerCluster> FeaturesBasedConfiguration { get; set; }
```

## 备注

此回调在渲染每个聚类中心之前被调用。它接受即将渲染的要素和此符号化器的克隆。通过更改克隆的属性，可以根据要素的属性更新符号化器的行为。

### 另见

* class [Feature](../../../aspose.gis/feature/)
* class [MarkerCluster](../)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../markercluster/)
* assembly [Aspose.GIS](../../../)


