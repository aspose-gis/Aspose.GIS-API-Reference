---
title: "GeoJsonSeqOptions Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.gis.formats.geojsonseq/geojsonseqoptions/
---

**Summary:** Driver-specific options for GeoJsonSeq.

**Module:** [aspose.gis.formats.geojsonseq](/psd/python-net/aspose.gis.formats.geojsonseq/)

**Full Name:** aspose.gis.formats.geojsonseq.GeoJsonSeqOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeoJsonSeqOptions()](#GeoJsonSeqOptions__1) | Yeni bir örnek oluştur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| array_as_string | bool | r/w | JSon dizi string, tamsayı veya gerçek değerlerini string olarak ortaya çıkarmak. |
| attributes_skip | bool | r/w | Özelliklerin çevirisini kontrol eder: evet - tüm özellikleri atla |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | Kimlikleri otomatik oluştur |
| close_linear_ring | bool | r/w | Her geometri içinde kapatılmamış bir [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) kapatılıp kapatılmayacağını belirler. Varsayılan <see langword="false" />. |
| create_midpoints | bool | r/w | Geometri her segmentine ortada yeni bir nokta ekleyip eklemeyeceğini belirler. Varsayılan <see langword="false" />. |
| date_as_string | bool | r/w | JSon tarih/zaman/tarih-zaman değerlerini string olarak ortaya çıkarmak isteyip istemediği. |
| delete_near_points | bool | r/w | Her geometri içinde yakın noktaları silip silmeyeceğini belirler. Varsayılan <see langword="false" />. |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| geometry_as_collection | bool | r/w | geometrilerin çevirisini kontrol et: evet - geometrileri GeometryCollection türüyle sar |
| linearization_tolerance | double | r/w | Eğri geometrileri doğrusal hale getirmek için kullanılacak bir tolerans. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | M koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | r/w | İç içe öznitelik bileşenlerini ayırmak için kullanılan bir dizeyi alır veya ayarlar.<br/>            Varsayılan "_". |
| simplify_segments | bool | r/w | Her geometride aynı segment üzerinde bulunan noktaların silinip silinmeyeceğini belirler. Varsayılan değer <see langword="false" />. |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Geometrilerin katmana eklendiğinde doğrulanıp doğrulanmayacağını belirler.<br/>            <see langword="true" /> olarak ayarlanırsa, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) katmana eklenen her geometri için çağrılır ve doğrulama başarısız olursa ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) fırlatılır. |
| write_polygons_as_lines | bool | r/w | Poligon veya çoklu poligonun linestring'e dönüştürülmesinin izin verilip verilmediğini belirler. Varsayılan değer <see langword="false" />. |
| write_unset_attribute | bool | r/w | Ayarlanmamış özniteliklerin 'null' değeri eklenerek yazılıp yazılmayacağını belirler. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | X ve Y koordinatlarına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Z koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GeoJsonSeqOptions() {#GeoJsonSeqOptions__1}


```
 GeoJsonSeqOptions() 
```

Yeni bir örnek oluştur.

