---
title: "SimpleLabeling.FeatureBasedConfiguration"
second_title: "Aspose.GIS for .NET API 参考"
description: "SimpleLabeling 属性。用于在处理要素之前配置此标注的回调"
type: docs
weight: 20
url: /zh/net/aspose.gis.rendering.labelings/simplelabeling/featurebasedconfiguration/
---
## SimpleLabeling.FeatureBasedConfiguration property

在处理要素之前用于配置此标注的回调函数。

```csharp
public Action<Feature, SimpleLabeling> FeatureBasedConfiguration { get; set; }
```

## 备注

此回调在标注每个要素之前被调用。它接受即将被标注的要素以及此标注的克隆。通过更改克隆的属性，可以根据要素的属性更新标注的行为。

### 另见

* class [Feature](../../../aspose.gis/feature/)
* class [SimpleLabeling](../)
* namespace [Aspose.Gis.Rendering.Labelings](../../simplelabeling/)
* assembly [Aspose.GIS](../../../)


