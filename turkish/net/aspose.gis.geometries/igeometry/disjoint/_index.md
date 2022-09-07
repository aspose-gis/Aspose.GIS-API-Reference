---
title: Disjoint
second_title: Aspose.GIS for .NET API Referansı
description: Bu geometrinin belirtilen bir geometriden ayrı olup olmadığını belirler.
type: docs
weight: 180
url: /tr/net/aspose.gis.geometries/igeometry/disjoint/
---
## IGeometry.Disjoint method

Bu geometrinin belirtilen bir geometriden ayrı olup olmadığını belirler.

```csharp
public bool Disjoint(IGeometry other)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| other | IGeometry | Bir geometri. |

### Geri dönüş değeri

`true` eğer bu geometri başka bir geometriden "mekansal olarak ayrık" ise.`false` aksi halde.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | argüman`null`. |
| ArgumentException | İşlem tamamlanamayacak şekilde geometrilerden biri geçersiz. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) geometrilerin sayısı eşdeğer değil. Kullanabilirsiniz[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) geometrileri aynı uzamsal referans sistemine dönüştürmek için. |

### Notlar

Bu yöntem, geometrilerin DE-9IM kesişim matrisi açısından ayrık olup olmadığını test eder. Temel olarak, iki geometrinin ortak noktası olmadığını test eder. Bu yöntem şuna eşdeğerdir: DE-9IM hakkında daha fazla ayrıntı için OpenGIS Basit Özellikler Spesifikasyonuna bakın.

```csharp
this.Relate(other, "FF*FF****");
```

### Ayrıca bakınız

* method [Intersects](../intersects)
* interface [IGeometry](../../igeometry)
* ad alanı [Aspose.Gis.Geometries](../../igeometry)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->