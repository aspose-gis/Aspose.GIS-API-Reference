---
title: MultiCurve
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 1000
url: /net/aspose.gis.geometries/multicurve/
---
## MultiCurve class

A [`MultiCurve`](../multicurve) is a one-dimensional [`GeometryCollection`](../geometrycollection) whose elements are [`Curve`](../curve)s.

```csharp
public class MultiCurve : GeometryCollection, IMultiCurve
```

## Constructors

| Name | Description |
| --- | --- |
| [MultiCurve](multicurve)() | Initializes a new instance of the [`MultiCurve`](../multicurve) class. |

## Properties

| Name | Description |
| --- | --- |
| [Dimension](dimension) { get; } | Gets the topological dimension of this [`Geometry`](../geometry). |
| override [GeometryType](geometrytype) { get; } | Gets the type of the geometry. |
| virtual [IsClosed](isclosed) { get; } | Determines whether this curve is closed. |

## Methods

| Name | Description |
| --- | --- |
| override [Clone](clone)() | Clones this instance. |
| [ToEditable](toeditable)() | Gets an editable copy of this geometry. |
| [ToLinearGeometry](tolineargeometry)() | Gets approximate or equivalent non-curve version of this geometry using the default `tolerance`. |
| [ToLinearGeometry](tolineargeometry)(double) | Gets approximate or equivalent non-curve version of this geometry using the specified `tolerance`. |

### See Also

* class [GeometryCollection](../geometrycollection)
* interface [IMultiCurve](../imulticurve)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries)
* assembly [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->