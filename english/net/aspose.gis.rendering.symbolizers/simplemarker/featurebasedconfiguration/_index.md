---
title: FeatureBasedConfiguration
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 20
url: /net/aspose.gis.rendering.symbolizers/simplemarker/featurebasedconfiguration/
---
## SimpleMarker.FeatureBasedConfiguration property

A callback that is used to configure this symbolizer before rendering a feature.

```csharp
public Action<Feature, SimpleMarker> FeatureBasedConfiguration { get; set; }
```

### Remarks

This callback is invoked before rendering every feature. It accepts a feature that is about to be rendered and a clone of this symbolizer. By changing properties of the clone, it is possible to update symbolizer's behavior based on feature's attributes.

### See Also

* class [Feature](../../../aspose.gis/feature)
* class [SimpleMarker](../../simplemarker)
* namespace [Aspose.Gis.Rendering.Symbolizers](../../simplemarker)
* assembly [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
