---
title: Projection.TryGetParameterValue
second_title: Aspose.GIS for .NET API Reference
description: Projection method. Gets parameter with specified name of this projection. If there are no such parameter  returns null
type: docs
weight: 60
url: /net/aspose.gis.spatialreferencing/projection/trygetparametervalue/
---
## Projection.TryGetParameterValue method

Gets parameter with specified name of this projection. If there are no such parameter - returns `null`.

```csharp
public double? TryGetParameterValue(string name, ParameterType type = ParameterType.Other)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Name of parameter. |
| type | ParameterType | Type of parameter. Defines unit factor that will be deapplied: if type is Linear then [`LinearParametersUnit`](../linearparametersunit/) will be deapplied and result will be in meters. if type is Angular then [`AngularParametersUnit`](../angularparametersunit/) will be deapplied and result will be in radians. if type is Other parameter value will be returned 'as is'. |

### Return Value

Parameter with specified name or `null` if it is not present.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Argument is null. |

### See Also

* enum [ParameterType](../../parametertype/)
* class [Projection](../)
* namespace [Aspose.Gis.SpatialReferencing](../../projection/)
* assembly [Aspose.GIS](../../../)


