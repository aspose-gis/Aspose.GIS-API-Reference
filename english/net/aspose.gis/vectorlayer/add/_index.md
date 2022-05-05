---
title: Add
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 80
url: /net/aspose.gis/vectorlayer/add/
---
## VectorLayer.Add method (1 of 2)

Adds a new feature to the layer, if supported by the [`VectorLayer`](../../vectorlayer)'s [`Driver`](../driver).

```csharp
public void Add(Feature feature)
```

| Parameter | Type | Description |
| --- | --- | --- |
| feature | Feature | The feature to add. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | is thrown if the layer is read-only. |

### See Also

* class [Feature](../../feature)
* class [VectorLayer](../../vectorlayer)
* namespace [Aspose.Gis](../../vectorlayer)
* assembly [Aspose.GIS](../../../)

---

## VectorLayer.Add method (2 of 2)

Adds a new feature with the specified style to the layer, if supported by the [`VectorLayer`](../../vectorlayer)'s [`Driver`](../driver).

```csharp
public virtual void Add(Feature feature, IFeatureStyle style)
```

| Parameter | Type | Description |
| --- | --- | --- |
| feature | Feature | The feature to add. |
| style | IFeatureStyle | The feature style. Use `null` to indicate missing style. |

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | is thrown if the layer does not support styles or the layer is read-only. |
| InvalidOperationException | is thrown if the the editable layers does not support styles. |
| ArgumentException | is thrown if the style does not match driver type. |

### See Also

* class [Feature](../../feature)
* interface [IFeatureStyle](../../ifeaturestyle)
* class [VectorLayer](../../vectorlayer)
* namespace [Aspose.Gis](../../vectorlayer)
* assembly [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->