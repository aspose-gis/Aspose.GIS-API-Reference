---
title: Class DriverOptions
second_title: Aspose.GIS for .NET API Referansı
description: Aspose.Gis.DriverOptions sınıf. için seçeneklerDriver .
type: docs
weight: 100
url: /tr/net/aspose.gis/driveroptions/
---
## DriverOptions class

için seçenekler[`Driver`](../driver/) .

```csharp
public abstract class DriverOptions
```

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | Kapatılmayanların kapatılıp kapatılmadığını belirlerLinearRing her geometride varsayılanlar`false` . |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | Her bir geometri parçasının ortasına yeni bir nokta eklenip eklenmeyeceğini belirler. varsayılanlar`false` . |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | Her bir geometrideki yakın noktaların silinip silinmediğini belirler. varsayılanlar`false` . |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | için mesafeyi belirler[`DeleteNearPoints`](./deletenearpoints/) . varsayılanlar`0` . |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | Eğri geometrilerini doğrusallaştırmak için kullanılacak bir tolerans. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | bir[`PrecisionModel`](../precisionmodel/) geometriler eklendiğinde M koordinatına uygulanacak[`VectorLayer`](../vectorlayer/) veya sayfadan okunduklarında[`VectorLayer`](../vectorlayer/) . Varsayılan değer:[`Exact`](../precisionmodel/exact/) . |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | Her geometride aynı parça üzerinde bulunan noktaların silinip silinmediğini belirler. varsayılanlar`false` . |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | için mesafeyi belirler[`SimplifySegments`](./simplifysegments/) . varsayılanlar`0` . |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | Katmana eklendiklerinde geometrilerin doğrulanması gerekip gerekmediğini belirler. Eğer ayarlanırsa`true` ,[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) katmana eklendiğinde ve doğrulama başarısız olursa ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) dır-dir`false` ),[`GisException`](../gisexception/) atılır. |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | Çokgen veya çoklu çokgenin çizgi dizisine dönüştürülmesine izin verilip verilmediğini belirler. varsayılanlar`false` . |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | bir[`PrecisionModel`](../precisionmodel/) geometriler eklendiğinde X ve Y koordinatlarına uygulanacak[`VectorLayer`](../vectorlayer/) veya sayfadan okunduklarında[`VectorLayer`](../vectorlayer/) . Varsayılan değer:[`Exact`](../precisionmodel/exact/) . |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | bir[`PrecisionModel`](../precisionmodel/) geometriler eklendiğinde Z koordinatına uygulanacaktır.[`VectorLayer`](../vectorlayer/) veya sayfadan okunduklarında[`VectorLayer`](../vectorlayer/) . Varsayılan değer:[`Exact`](../precisionmodel/exact/) . |

### Ayrıca bakınız

* ad alanı [Aspose.Gis](../../aspose.gis/)
* toplantı [Aspose.GIS](../../)


