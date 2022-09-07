---
title: OsmXmlOptions
second_title: Aspose.GIS for .NET API Referansı
description: OSM XML formatı için sürücüye özel seçenekler.
type: docs
weight: 560
url: /tr/net/aspose.gis.formats.osmxml/osmxmloptions/
---
## OsmXmlOptions class

OSM XML formatı için sürücüye özel seçenekler.

```csharp
public class OsmXmlOptions : DriverOptions
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [OsmXmlOptions](osmxmloptions)() | Yeni örnek oluştur. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring) { get; set; } | Kapatılmamış birLinearRing her geometride Varsayılan`false` . |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints) { get; set; } | Her geometri parçasının ortasına yeni bir nokta eklenip eklenmeyeceğini belirler. Varsayılan`false` . |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints) { get; set; } | Her geometrideki yakın noktaların silinip silinmeyeceğini belirler. Varsayılan`false` . |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance) { get; set; } | için mesafeyi belirler[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints) . Varsayılan`0` . |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance) { get; set; } | Eğri geometrilerini doğrusallaştırmak için kullanılacak bir tolerans. |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel) geometriler eklendiğinde M koordinat öğesine uygulanacak[`VectorLayer`](../../aspose.gis/vectorlayer) ya da oradan okunduklarında[`VectorLayer`](../../aspose.gis/vectorlayer) . Varsayılan değer[`Exact`](../../aspose.gis/precisionmodel/exact) . |
| [ReportAllNodes](../../aspose.gis.formats.osmxml/osmxmloptions/reportallnodes) { get; set; } | Önemli etiketleri olmasa bile tüm düğümleri özellik olarak bildirin. |
| [ReportAllWays](../../aspose.gis.formats.osmxml/osmxmloptions/reportallways) { get; set; } | Önemli etiketleri veya düğümleri olmasa bile tüm yolları özellik olarak bildirin. |
| [ReportCommonAttributes](../../aspose.gis.formats.osmxml/osmxmloptions/reportcommonattributes) { get; set; } | Ortak OSM özniteliklerini bildirin: görünür, sürüm, değişiklik kümesi, zaman damgası, kullanıcı ve kullanıcı kimliği. Ortak öznitelikler, "osm_" öneki ile özellik öznitelikleri olarak rapor edilecektir, ör. osm_user, osm_timestamp, vb. |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments) { get; set; } | Her geometride aynı segment üzerinde bulunan noktaların silinip silinmeyeceğini belirler. Varsayılan`false` . |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance) { get; set; } | için mesafeyi belirler[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments) . Varsayılan`0` . |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite) { get; set; } | Katmana eklendiklerinde geometrilerin doğrulanıp doğrulanmayacağını belirler. olarak ayarlanırsa`true` ,[`IsValid`](../../aspose.gis.geometries/geometry/isvalid)katmana eklendiğinde ve doğrulama başarısız olursa her geometrisi için çağrılır ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid) dır-dir`false` ),[`GisException`](../../aspose.gis/gisexception) atılır. |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines) { get; set; } | Çokgenin veya çok çokgenin çizgi dizisine dönüştürülmesine izin verilip verilmediğini belirler. Varsayılan`false` . |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel)geometriler eklendiğinde X ve Y koordinatlarına uygulanacak[`VectorLayer`](../../aspose.gis/vectorlayer) ya da oradan okunduklarında[`VectorLayer`](../../aspose.gis/vectorlayer) . Varsayılan değer[`Exact`](../../aspose.gis/precisionmodel/exact) . |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel) { get; set; } | A[`PrecisionModel`](../../aspose.gis/precisionmodel) geometriler eklendiğinde Z koordinat öğesine uygulanacak[`VectorLayer`](../../aspose.gis/vectorlayer) ya da oradan okunduklarında[`VectorLayer`](../../aspose.gis/vectorlayer) . Varsayılan değer[`Exact`](../../aspose.gis/precisionmodel/exact) . |

### Ayrıca bakınız

* class [DriverOptions](../../aspose.gis/driveroptions)
* ad alanı [Aspose.Gis.Formats.OsmXml](../../aspose.gis.formats.osmxml)
* toplantı [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->