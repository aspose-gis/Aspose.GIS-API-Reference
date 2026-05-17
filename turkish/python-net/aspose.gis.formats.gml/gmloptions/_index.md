---
title: "GmlOptions Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.gis.formats.gml/gmloptions/
---

**Summary:** Driver-specific options for GML format.

**Module:** [aspose.gis.formats.gml](/psd/python-net/aspose.gis.formats.gml/)

**Full Name:** aspose.gis.formats.gml.GmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GmlOptions()](#GmlOptions__1) | Yeni bir örnek oluştur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| application_namespace | string | r/w | Bu, gml belgesi oluşturulurken uygulama ad alanı olarak kullanılacak özel bir ad alanı belirtir. |
| close_linear_ring | bool | r/w | Her geometri içinde kapatılmamış bir [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) kapatılıp kapatılmayacağını belirler. Varsayılan <see langword="false" />. |
| create_midpoints | bool | r/w | Geometri her segmentine ortada yeni bir nokta ekleyip eklemeyeceğini belirler. Varsayılan <see langword="false" />. |
| delete_near_points | bool | r/w | Her geometri içinde yakın noktaları silip silmeyeceğini belirler. Varsayılan <see langword="false" />. |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| linearization_tolerance | double | r/w | Eğri geometrileri doğrusal hale getirmek için kullanılacak bir tolerans. |
| load_schemas_from_internet | bool | r/w | Aspose.GIS'in Internet'ten XML şeması yüklemesine izin verilip verilmediğini belirler.<br/>            Eğer <see langword=\"false\" /> olarak ayarlanırsa, 'file://' ile başlamayan mutlak URI'lere sahip şemalar yüklenmez.<br/>            Varsayılan <see langword=\"false\" /> değeridir. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | M koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | r/w | İç içe öznitelik bileşenlerini ayırmak için kullanılan bir dizeyi alır veya ayarlar.<br/>            Varsayılan "_". |
| restore_schema | bool | r/w | Aspose.GIS'in eksik veya yüklenemeyen bir XML şeması bulunan bir Gml dosyasındaki öznitelikleri ayrıştırmasına izin verilip verilmediğini belirler.<br/>            Eğer <see langword=\"true\" /> olarak ayarlanırsa, Aspose.GIS okuyucu bir XML Şemasının varlığını gerektirmez.<br/>            Varsayılan <see langword=\"false\" /> değeridir. |
| schema_location | string | r/w | URI çiftlerinin boşlukla ayrılmış listesi. Her çiftin ilk URI'si ad alanının URI'si, ikinci URI ise ad alanının XML şemasının yolu olur.<br/>            Eğer <see langword=\"null\" /> olarak ayarlanırsa, [GmlDriver](/psd/python-net/aspose.gis.formats.gml/gmldriver/) belge kök öğesinden schemaLocation'ı okumaya çalışır.<br/>            Varsayılan <see langword=\"null\" /> değeridir. |
| simplify_segments | bool | r/w | Her geometride aynı segment üzerinde bulunan noktaların silinip silinmeyeceğini belirler. Varsayılan değer <see langword="false" />. |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Geometrilerin katmana eklendiğinde doğrulanıp doğrulanmayacağını belirler.<br/>            <see langword="true" /> olarak ayarlanırsa, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) katmana eklenen her geometri için çağrılır ve doğrulama başarısız olursa ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) fırlatılır. |
| write_polygons_as_lines | bool | r/w | Poligon veya çoklu poligonun linestring'e dönüştürülmesinin izin verilip verilmediğini belirler. Varsayılan değer <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | X ve Y koordinatlarına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Z koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GmlOptions() {#GmlOptions__1}


```
 GmlOptions() 
```

Yeni bir örnek oluştur.

