---
title: SpatialReferenceSystem.CreateCompound
second_title: Aspose.GIS for .NET API Reference
description: SpatialReferenceSystem method. Create compound SRS
type: docs
weight: 340
url: /net/aspose.gis.spatialreferencing/spatialreferencesystem/createcompound/
---
## SpatialReferenceSystem.CreateCompound method

Create compound SRS.

```csharp
public static CompoundSpatialReferenceSystem CreateCompound(string name, 
    SpatialReferenceSystem head, SpatialReferenceSystem tail, Identifier identifier = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| name | String | Name of new SRS. |
| head | SpatialReferenceSystem | Head SRS of new SRS. |
| tail | SpatialReferenceSystem | Tail SRS of new SRS. |
| identifier | Identifier | Identifier, that will be attached to SRS. Attaching an Identifier will not modify other SRS parameters. Its up to you to ensure consistency of identifier and SRS parameters. |

### Return Value

New Compound SRS.

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentNullException | Any argument except *identifier* is `null`. |
| InvalidOperationException | *head* or *tail* are compound SRS themselves. |

### See Also

* class [CompoundSpatialReferenceSystem](../../compoundspatialreferencesystem/)
* class [Identifier](../../identifier/)
* class [SpatialReferenceSystem](../)
* namespace [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem/)
* assembly [Aspose.GIS](../../../)


