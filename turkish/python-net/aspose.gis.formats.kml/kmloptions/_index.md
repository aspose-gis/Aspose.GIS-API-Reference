---
title: "KmlOptions Sınıfı"
type: docs
weight: 190
url: /tr/python-net/aspose.gis.formats.kml/kmloptions/
---

**Summary:** Driver-specific options for KML format.

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [KmlOptions()](#KmlOptions__1) | Yeni bir örnek oluştur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| altitude_mode | [AltitudeModes](/psd/python-net/aspose.gis.formats.kml/altitudemodes) | r/w | KML geometrileri için kullanılacak AltitudeModes değerlerini belirtmenizi sağlar |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | Kimlikleri otomatik oluştur |
| close_linear_ring | bool | r/w | Her geometri içinde kapatılmamış bir [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) kapatılıp kapatılmayacağını belirler. Varsayılan <see langword="false" />. |
| create_midpoints | bool | r/w | Geometri her segmentine ortada yeni bir nokta ekleyip eklemeyeceğini belirler. Varsayılan <see langword="false" />. |
| delete_near_points | bool | r/w | Her geometri içinde yakın noktaları silip silmeyeceğini belirler. Varsayılan <see langword="false" />. |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| document_id | string | r/w | Kök 'Document' düğümünün kimliğini belirtmek için kullanılır |
| linearization_tolerance | double | r/w | Eğri geometrileri doğrusal hale getirmek için kullanılacak bir tolerans. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | M koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | r/w | Her geometride aynı segment üzerinde bulunan noktaların silinip silinmeyeceğini belirler. Varsayılan değer <see langword="false" />. |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| symbol_to_replace_invalid_chars | char | r/w | Okuma sırasında geçersiz karakterleri değiştirmek için hangi sembolün kullanılacağını belirler.<br/>            Değer '\0' ise değiştirme atlanır. Varsayılan değer '\0' karakteridir. |
| validate_geometries_on_write | bool | r/w | Geometrilerin katmana eklendiğinde doğrulanıp doğrulanmayacağını belirler.<br/>            <see langword="true" /> olarak ayarlanırsa, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) katmana eklenen her geometri için çağrılır ve doğrulama başarısız olursa ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) fırlatılır. |
| write_polygons_as_lines | bool | r/w | Poligon veya çoklu poligonun linestring'e dönüştürülmesinin izin verilip verilmediğini belirler. Varsayılan değer <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | X ve Y koordinatlarına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Z koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: KmlOptions() {#KmlOptions__1}


```
 KmlOptions() 
```

Yeni bir örnek oluştur.

