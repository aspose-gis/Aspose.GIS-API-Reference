---
title: CoveredBy
second_title: Aspose.GIS for .NET API Referansı
description: Bu geometrinin belirtilen bir geometri tarafından kapsanıp kapsanmadığını belirler.
type: docs
weight: 140
url: /tr/net/aspose.gis.geometries/igeometry/coveredby/
---
## IGeometry.CoveredBy method

Bu geometrinin belirtilen bir geometri tarafından kapsanıp kapsanmadığını belirler.

```csharp
public bool CoveredBy(IGeometry other)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| other | IGeometry | Bir geometri. |

### Geri dönüş değeri

`true`eğer bu geometri başka bir geometri tarafından "uzaysal olarak kapsanıyorsa".`false` aksi halde.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | argüman`null`. |
| ArgumentException | İşlem tamamlanamayacak şekilde geometrilerden biri geçersiz. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) geometrilerin sayısı eşdeğer değil. Kullanabilirsiniz[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) geometrileri aynı uzamsal referans sistemine dönüştürmek için. |

### Notlar

Bu yöntem, DE-9IM kesişim matrisi açısından bir geometrinin başka bir geometri tarafından kapsanıp kapsanmadığını test eder. Bu yöntem şuna eşdeğerdir:

```csharp
other.Covers(this);
```

### Ayrıca bakınız

* method [SpatiallyContains](../spatiallycontains)
* method [Covers](../covers)
* interface [IGeometry](../../igeometry)
* ad alanı [Aspose.Gis.Geometries](../../igeometry)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->