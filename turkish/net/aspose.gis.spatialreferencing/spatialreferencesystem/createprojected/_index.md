---
title: CreateProjected
second_title: Aspose.GIS for .NET API Referansı
description: Özel parametrelerden tahmini SRS oluşturun.
type: docs
weight: 380
url: /tr/net/aspose.gis.spatialreferencing/spatialreferencesystem/createprojected/
---
## SpatialReferenceSystem.CreateProjected method

Özel parametrelerden tahmini SRS oluşturun.

```csharp
public static ProjectedSpatialReferenceSystem CreateProjected(
    ProjectedSpatialReferenceSystemParameters parameters, Identifier identifier = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| parameters | ProjectedSpatialReferenceSystemParameters | Oluşturulacak parametreler. |
| identifier | Identifier | SRS'ye eklenecek olan tanımlayıcı. Bir Tanımlayıcı eklemek diğer SRS parametrelerini değiştirmeyecektir. Tanımlayıcı ve SRS parametrelerinin tutarlılığını sağlamak size kalmıştır. |

### Geri dönüş değeri

Yeni Öngörülen SRS.

### istisnalar

| istisna | şart |
| --- | --- |
| InvalidOperationException | Parametrelerdeki Temel SRS:`null` . Parametrelerdeki projeksiyon yöntemi`null` . |

### Ayrıca bakınız

* class [ProjectedSpatialReferenceSystem](../../projectedspatialreferencesystem)
* class [ProjectedSpatialReferenceSystemParameters](../../projectedspatialreferencesystemparameters)
* class [Identifier](../../identifier)
* class [SpatialReferenceSystem](../../spatialreferencesystem)
* ad alanı [Aspose.Gis.SpatialReferencing](../../spatialreferencesystem)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->