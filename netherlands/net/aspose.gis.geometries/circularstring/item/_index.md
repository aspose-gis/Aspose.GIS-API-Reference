---
title: CircularString.Item
second_title: Aspose.GIS voor .NET API-referentie
description: CircularString eigendom. Haalt of stelt deIPoint op de opgegeven index.
type: docs
weight: 90
url: /nl/net/aspose.gis.geometries/circularstring/item/
---
## CircularString indexer

Haalt of stelt de[`IPoint`](../../ipoint/) op de opgegeven index.

```csharp
public IPoint this[int index] { get; set; }
```

| Parameter | Beschrijving |
| --- | --- |
| index | De index. |

### Eigendoms-waarde

De[`IPoint`](../../ipoint/) .

### Uitzonderingen

| uitzondering | voorwaarde |
| --- | --- |
| ArgumentOutOfRangeException | Index is buiten bereik. |
| ArgumentNullException | De waarde is`null`. |
| ArgumentException | Punt is leeg. |
| ArgumentException | [`SpatialReferenceSystem`](../../igeometry/spatialreferencesystem/) van deze geometrie en[`SpatialReferenceSystem`](../spatialreferencesystem/) van argument zijn beide niet`null` en zijn niet gelijk aan elkaar. |

### Zie ook

* interface [IPoint](../../ipoint/)
* class [CircularString](../)
* naamruimte [Aspose.Gis.Geometries](../../circularstring/)
* montage [Aspose.GIS](../../../)


