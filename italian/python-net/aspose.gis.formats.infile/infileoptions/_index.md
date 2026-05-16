---
title: "Classe InFileOptions"
type: docs
weight: 20
url: /it/python-net/aspose.gis.formats.infile/infileoptions/
---

**Summary:** Driver-specific options for InFile layer.

**Module:** [aspose.gis.formats.infile](/psd/python-net/aspose.gis.formats.infile/)

**Full Name:** aspose.gis.formats.infile.InFileOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [InFileOptions()](#InFileOptions__1) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| array_as_string | bool | r/w | Indica se esporre gli array JSON di stringhe, interi o numeri reali come stringa. |
| attributes_skip | bool | r/w | controlla la traduzione degli attributi: sì - ignora tutti gli attributi |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | Genera automaticamente gli ID |
| close_linear_ring | bool | r/w | Determina se chiudere un [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) non chiuso in ogni geometria. Il valore predefinito è <see langword="false" />. |
| count_of_feature_in_part | int | r/w | Numero massimo di feature in ogni parte del file |
| create_midpoints | bool | r/w | Determina se aggiungere un nuovo punto al centro di ogni segmento della geometria. Il valore predefinito è <see langword="false" />. |
| date_as_string | bool | r/w | Indica se esporre le date/ore/date-time JSON come stringa. |
| delete_near_points | bool | r/w | Determina se eliminare i punti vicini in ogni geometria. Il valore predefinito è <see langword="false" />. |
| delete_near_points_distance | double | r/w | Determina la distanza per [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Il valore predefinito è <see langword="0" />. |
| geometry_as_collection | bool | r/w | controlla la traduzione delle geometrie: sì - avvolge le geometrie con il tipo GeometryCollection |
| linearization_tolerance | double | r/w | Una tolleranza da utilizzare per linearizzare le geometrie curve. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) che verrà applicato alla coordinata M<br/>            quando le geometrie vengono aggiunte al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o quando vengono lette dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Il valore predefinito è [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | r/w | Ottiene o imposta una stringa utilizzata per separare i componenti degli attributi nidificati.<br/>            Il valore predefinito è "_". |
| simplify_segments | bool | r/w | Determina se eliminare i punti che giacciono sullo stesso segmento in ciascuna geometria. Il valore predefinito è <see langword="false" />. |
| simplify_segments_distance | double | r/w | Determina la distanza per [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Il valore predefinito è <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Determina se le geometrie devono essere validate quando vengono aggiunte al livello.<br/>            Se impostato su <see langword="true" />, viene chiamato [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) per ogni<br/>            geometria quando viene aggiunta al livello, e se la validazione fallisce ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) è <see langword="false" />), viene sollevata [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Determina se la trasformazione di poligono o multipoligono in linestring è consentita. Il valore predefinito è <see langword="false" />. |
| write_unset_attribute | bool | r/w | Indica se scrivere gli attributi non impostati aggiungendo il valore 'null' |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) che verrà applicato alle coordinate X e Y<br/>            quando le geometrie vengono aggiunte al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o quando vengono lette dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Il valore predefinito è [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) che verrà applicato alla coordinata Z<br/>            quando le geometrie vengono aggiunte al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o quando vengono lette dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Il valore predefinito è [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: InFileOptions() {#InFileOptions__1}


```
 InFileOptions() 
```

Crea una nuova istanza.

