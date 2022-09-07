---
title: Overlaps
second_title: Aspose.GIS for .NET API Referansı
description: Bu geometrinin belirtilen bir geometriyle örtüşüp örtüşmediğini belirler.
type: docs
weight: 280
url: /tr/net/aspose.gis.geometries/igeometry/overlaps/
---
## IGeometry.Overlaps method

Bu geometrinin belirtilen bir geometriyle örtüşüp örtüşmediğini belirler.

```csharp
public bool Overlaps(IGeometry other)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| other | IGeometry | Bir geometri. |

### Geri dönüş değeri

`true` eğer bu geometri başka bir geometri "uzaysal olarak örtüşüyorsa".`false` aksi halde.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | argüman`null`. |
| ArgumentException | İşlem tamamlanamayacak şekilde geometrilerden biri geçersiz. |
| ArgumentException | [`SpatialReferenceSystem`](../spatialreferencesystem) geometrilerin sayısı eşdeğer değil. Kullanabilirsiniz[`SpatialReferenceSystemTransformation`](../../../aspose.gis.spatialreferencing/spatialreferencesystemtransformation) geometrileri aynı uzamsal referans sistemine dönüştürmek için. |

### Notlar

Bu yöntem, geometrilerin DE-9IM kesişim matrisi açısından örtüşüp örtüşmediğini test eder. Bazı iç noktaların ortak olduğu ancak hepsinin ortak olmadığı iki geometri örtüşür ve geometrilerin kesişimi, geometrilerin kendileriyle aynı boyuta sahipse. İki kişilikPoint geometriler veya ikiSurface geometriler this yöntemi şuna eşittir: İki kişilikLine geometriler bu yöntem şuna eşittir: Eşit olmayan iki geometri için[`Dimension`](../dimension) bu yöntem her zaman döndürür`false`. DE-9IM ve "uzaysal örtüşmeler" ilişkisi hakkında daha fazla ayrıntı için OpenGIS Basit Özellikler Spesifikasyonuna bakın.

```csharp
this.Relate(other, "T*T***T**");
```

```csharp
this.Relate(other, "1*T***T**");
```

### Ayrıca bakınız

* interface [IGeometry](../../igeometry)
* ad alanı [Aspose.Gis.Geometries](../../igeometry)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->