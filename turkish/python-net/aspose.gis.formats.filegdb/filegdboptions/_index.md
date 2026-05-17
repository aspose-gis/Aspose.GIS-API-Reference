---
title: "FileGdbOptions Sınıfı"
type: docs
weight: 30
url: /tr/python-net/aspose.gis.formats.filegdb/filegdboptions/
---

**Summary:** Driver-specific options for FileGDB format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbOptions()](#FileGdbOptions__1) | Yeni bir örnek oluştur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Her geometri içinde kapatılmamış bir [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) kapatılıp kapatılmayacağını belirler. Varsayılan <see langword="false" />. |
| coordinate_precision_grid | [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | r/w | Yeni katmanda kullanılacak bir koordinat hassasiyet ızgarası. |
| create_midpoints | bool | r/w | Geometri her segmentine ortada yeni bir nokta ekleyip eklemeyeceğini belirler. Varsayılan <see langword="false" />. |
| delete_near_points | bool | r/w | Her geometri içinde yakın noktaları silip silmeyeceğini belirler. Varsayılan <see langword="false" />. |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| ensure_valid_coordinates_range | bool | r/w | Koordinatların geçerli bir aralıkta olup olmaması. |
| expected_geometry_type | Nullable<Aspose.Gis.Geometries.GeometryType> | r/w | Katman için beklenen geometri türü. Bu seçenek ayarlanırsa, yalnızca bu türdeki geometrilerin eklenmesine izin verilir. |
| geometry_field_name | string | r/w | Geometri alanının adı. |
| has_m | bool | r/w | Katmanın geometrileri 'm' koordinatına sahip olabilir. Varsayılan olarak true. |
| has_z | bool | r/w | Katmanın geometrileri 'z' koordinatına sahip olabilir. Varsayılan olarak true. |
| linearization_tolerance | double | r/w | Eğri geometrileri doğrusal hale getirmek için kullanılacak bir tolerans. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | M koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| m_tolerance | Nullable<double> | r/w | M yakalama toleransı. |
| object_id_field_name | string | r/w | Nesne kimliği alanının adı. |
| simplify_segments | bool | r/w | Her geometride aynı segment üzerinde bulunan noktaların silinip silinmeyeceğini belirler. Varsayılan değer <see langword="false" />. |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Geometrilerin katmana eklendiğinde doğrulanıp doğrulanmayacağını belirler.<br/>            <see langword="true" /> olarak ayarlanırsa, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) katmana eklenen her geometri için çağrılır ve doğrulama başarısız olursa ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) fırlatılır. |
| write_polygons_as_lines | bool | r/w | Poligon veya çoklu poligonun linestring'e dönüştürülmesinin izin verilip verilmediğini belirler. Varsayılan değer <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | X ve Y koordinatlarına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| xy_tolerance | Nullable<double> | r/w | X ve Y yakalama toleransı. |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Z koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_tolerance | Nullable<double> | r/w | Z yakalama toleransı. |


### Constructor: FileGdbOptions() {#FileGdbOptions__1}


```
 FileGdbOptions() 
```

Yeni bir örnek oluştur.

