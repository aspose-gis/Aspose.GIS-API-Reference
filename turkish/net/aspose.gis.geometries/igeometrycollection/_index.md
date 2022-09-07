---
title: IGeometryCollection
second_title: Aspose.GIS for .NET API Referansı
description: AIGeometryCollection./igeometrycollection birIGeometry./igeometry bu bir veya daha fazla geometrinin bir koleksiyonudur.
type: docs
weight: 910
url: /tr/net/aspose.gis.geometries/igeometrycollection/
---
## IGeometryCollection interface

A[`IGeometryCollection`](../igeometrycollection) bir[`IGeometry`](../igeometry) bu, bir veya daha fazla geometrinin bir koleksiyonudur.

```csharp
public interface IGeometryCollection : IEnumerable<IGeometry>, IEquatable<IGeometryCollection>, 
    IGeometry
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [Count](../../aspose.gis.geometries/igeometrycollection/count) { get; } | Bu koleksiyondaki geometrilerin sayısını alır. |
| [Item](../../aspose.gis.geometries/igeometrycollection/item) { get; } | [`IGeometry`](../igeometry) belirtilen dizinde. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [GetPointOnSurface](../../aspose.gis.geometries/igeometrycollection/getpointonsurface)() | Bu koleksiyondaki yüzeylerden birinde olması garanti edilen bir nokta bulur. |
| [ReplacePolygonsByLines](../../aspose.gis.geometries/igeometrycollection/replacepolygonsbylines)() | Bu geometrinin çizgileri olarak temsil edilen çokgenleri alır. |
| [ToEditable](../../aspose.gis.geometries/igeometrycollection/toeditable)() | Bu geometrinin düzenlenebilir bir kopyasını alır. |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometrycollection/tolineargeometry#tolineargeometry)() | Varsayılanı kullanarak bu geometrinin yaklaşık veya eşdeğer eğri olmayan sürümünü alır`hata payı` . |
| [ToLinearGeometry](../../aspose.gis.geometries/igeometrycollection/tolineargeometry#tolineargeometry_1)(double) | Belirtilen geometriyi kullanarak bu geometrinin yaklaşık veya eşdeğer eğri olmayan sürümünü alır`hata payı` . |

### Ayrıca bakınız

* interface [IGeometry](../igeometry)
* ad alanı [Aspose.Gis.Geometries](../../aspose.gis.geometries)
* toplantı [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->