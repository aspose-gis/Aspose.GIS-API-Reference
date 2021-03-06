---
title: AsBinary
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 110
url: /net/aspose.gis.geometries/geometry/asbinary/
---
## Geometry.AsBinary method (1 of 2)

Translates this geometry to its Well-Known Binary representation.

```csharp
public byte[] AsBinary()
```

## Return Value

Well-Known Binary representation of this geometry.

### Remarks

Output of this method is in Iso WKB variant.

### See Also

* class [Geometry](../../geometry)
* namespace [Aspose.Gis.Geometries](../../geometry)
* assembly [Aspose.GIS](../../../)

---

## Geometry.AsBinary method (2 of 2)

Translates this geometry to its Well-Known Binary representation.

```csharp
public byte[] AsBinary(WkbVariant variant)
```

| Parameter | Type | Description |
| --- | --- | --- |
| variant | WkbVariant | Well-Known Binary variant to use. |

## Return Value

Well-Known Binary representation of this geometry.

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | Geometry can not be represented in requested WKB variant. Currently this happens when [`HasCurveGeometry`](../hascurvegeometry) of geometry is `true` and WKB variant is SimpleFeatureAccessOutdated. |
| ArgumentOutOfRangeException | *variant* is not a valid [`WkbVariant`](../../wkbvariant). |

### See Also

* enum [WkbVariant](../../wkbvariant)
* class [Geometry](../../geometry)
* namespace [Aspose.Gis.Geometries](../../geometry)
* assembly [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
