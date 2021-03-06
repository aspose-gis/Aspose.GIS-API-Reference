---
title: AsText
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 110
url: /net/aspose.gis.geometries/igeometry/astext/
---
## IGeometry.AsText method (1 of 2)

Translates this geometry to its Well-Known Text representation.

```csharp
public string AsText()
```

## Return Value

Well-Known Text representation of this geometry.

### Remarks

Output of this method is in Iso WKT variant.

### See Also

* interface [IGeometry](../../igeometry)
* namespace [Aspose.Gis.Geometries](../../igeometry)
* assembly [Aspose.GIS](../../../)

---

## IGeometry.AsText method (2 of 2)

Translates this geometry to its Well-Known Text representation.

```csharp
public string AsText(WktVariant variant)
```

| Parameter | Type | Description |
| --- | --- | --- |
| variant | WktVariant | Well-Known Text variant to use. |

## Return Value

Well-Known Text representation of this geometry.

### Exceptions

| exception | condition |
| --- | --- |
| NotSupportedException | The geometry is not supported by requested WKT variant. The following geometries are supported only by Iso WKT variant: [`CircularString`](../../circularstring)[`CompoundCurve`](../../compoundcurve)[`CurvePolygon`](../../curvepolygon)[`MultiCurve`](../../multicurve)[`MultiSurface`](../../multisurface) All other geometries are supported by any WKT variant. |
| ArgumentOutOfRangeException | *variant* is not a valid [`WktVariant`](../../wktvariant). |

### See Also

* enum [WktVariant](../../wktvariant)
* interface [IGeometry](../../igeometry)
* namespace [Aspose.Gis.Geometries](../../igeometry)
* assembly [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
