---
title: "OsmXmlOptions Sınıfı"
type: docs
weight: 20
url: /tr/python-net/aspose.gis.formats.osmxml/osmxmloptions/
---

**Summary:** Driver-specific options for OSM XML format.

**Module:** [aspose.gis.formats.osmxml](/psd/python-net/aspose.gis.formats.osmxml/)

**Full Name:** aspose.gis.formats.osmxml.OsmXmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [OsmXmlOptions()](#OsmXmlOptions__1) | Yeni bir örnek oluştur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Her geometri içinde kapatılmamış bir [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) kapatılıp kapatılmayacağını belirler. Varsayılan <see langword="false" />. |
| create_midpoints | bool | r/w | Geometri her segmentine ortada yeni bir nokta ekleyip eklemeyeceğini belirler. Varsayılan <see langword="false" />. |
| delete_near_points | bool | r/w | Her geometri içinde yakın noktaları silip silmeyeceğini belirler. Varsayılan <see langword="false" />. |
| delete_near_points_distance | double | r/w | [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| linearization_tolerance | double | r/w | Eğri geometrileri doğrusal hale getirmek için kullanılacak bir tolerans. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | M koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| report_all_nodes | bool | r/w | Tüm düğümleri özellik olarak raporlar, hatta önemli etiketleri olmasa bile. |
| report_all_ways | bool | r/w | Tüm yolları özellik olarak raporlar, hatta önemli etiketleri olmasa ya da düğüm içermese bile. |
| report_common_attributes | bool | r/w | Ortak OSM niteliklerini raporla: visible, version, changeset, timestamp, user ve uid.<br/>            Ortak nitelikler, "osm_" önekiyle özellik nitelikleri olarak raporlanacaktır, ör. osm_user, osm_timestamp, vb. |
| simplify_segments | bool | r/w | Her geometride aynı segment üzerinde bulunan noktaların silinip silinmeyeceğini belirler. Varsayılan değer <see langword="false" />. |
| simplify_segments_distance | double | r/w | [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) için mesafeyi belirler. Varsayılan değer <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Geometrilerin katmana eklendiğinde doğrulanıp doğrulanmayacağını belirler.<br/>            <see langword="true" /> olarak ayarlanırsa, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) katmana eklenen her geometri için çağrılır ve doğrulama başarısız olursa ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) fırlatılır. |
| write_common_attributes | bool | r/w | Ortak OSM niteliklerini yaz: visible, version, changeset, timestamp, user ve uid. |
| write_polygons_as_lines | bool | r/w | Poligon veya çoklu poligonun linestring'e dönüştürülmesinin izin verilip verilmediğini belirler. Varsayılan değer <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | X ve Y koordinatlarına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Z koordinatına uygulanacak bir [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) <br/>            geometriler [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eklendiğinde veya [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) den okunduğunda.<br/>            Varsayılan değer [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: OsmXmlOptions() {#OsmXmlOptions__1}


```
 OsmXmlOptions() 
```

Yeni bir örnek oluştur.

