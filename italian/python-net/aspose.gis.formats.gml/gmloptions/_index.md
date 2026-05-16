---
title: "GmlOptions Classe"
type: docs
weight: 20
url: /it/python-net/aspose.gis.formats.gml/gmloptions/
---

**Summary:** Driver-specific options for GML format.

**Module:** [aspose.gis.formats.gml](/psd/python-net/aspose.gis.formats.gml/)

**Full Name:** aspose.gis.formats.gml.GmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descrizione** |
| :- | :- |
| [GmlOptions()](#GmlOptions__1) | Crea una nuova istanza. |
## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| application_namespace | string | r/w | Questo specifica uno spazio dei nomi personalizzato da utilizzare come spazio dei nomi dell'applicazione per generare il documento gml. |
| close_linear_ring | bool | r/w | Determina se chiudere un [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) non chiuso in ogni geometria. Il valore predefinito è <see langword="false" />. |
| create_midpoints | bool | r/w | Determina se aggiungere un nuovo punto al centro di ogni segmento della geometria. Il valore predefinito è <see langword="false" />. |
| delete_near_points | bool | r/w | Determina se eliminare i punti vicini in ogni geometria. Il valore predefinito è <see langword="false" />. |
| delete_near_points_distance | double | r/w | Determina la distanza per [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Il valore predefinito è <see langword="0" />. |
| linearization_tolerance | double | r/w | Una tolleranza da utilizzare per linearizzare le geometrie curve. |
| load_schemas_from_internet | bool | r/w | Determina se Aspose.GIS è autorizzato a caricare lo schema XML da Internet.<br/>            Se impostato su <see langword=\"false\" />, gli schemi con URI assoluti che non iniziano con 'file://' non verranno caricati.<br/>            Il valore predefinito è <see langword=\"false\" />. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) che verrà applicato alla coordinata M<br/>            quando le geometrie vengono aggiunte al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o quando vengono lette dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Il valore predefinito è [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | r/w | Ottiene o imposta una stringa utilizzata per separare i componenti degli attributi nidificati.<br/>            Il valore predefinito è "_". |
| restore_schema | bool | r/w | Determina se Aspose.GIS è autorizzato a analizzare gli attributi in un file Gml in cui uno schema XML è mancante o non può essere caricato.<br/>            Se impostato su <see langword=\"true\" />, il lettore Aspose.GIS non richiede la presenza di uno schema XML.<br/>            Il valore predefinito è <see langword=\"false\" />. |
| schema_location | string | r/w | Elenco di coppie di URI separati da spazi. Il primo URI di ogni coppia è l'URI dello spazio dei nomi, il secondo URI è un percorso allo schema XML dello spazio dei nomi.<br/>            Se impostato su <see langword=\"null\" />, [GmlDriver](/psd/python-net/aspose.gis.formats.gml/gmldriver/) proverà a leggere schemaLocation dall'elemento radice del documento.<br/>            Il valore predefinito è <see langword=\"null\" />. |
| simplify_segments | bool | r/w | Determina se eliminare i punti che giacciono sullo stesso segmento in ciascuna geometria. Il valore predefinito è <see langword="false" />. |
| simplify_segments_distance | double | r/w | Determina la distanza per [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Il valore predefinito è <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Determina se le geometrie devono essere validate quando vengono aggiunte al livello.<br/>            Se impostato su <see langword="true" />, viene chiamato [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) per ogni<br/>            geometria quando viene aggiunta al livello, e se la validazione fallisce ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) è <see langword="false" />), viene sollevata [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Determina se la trasformazione di poligono o multipoligono in linestring è consentita. Il valore predefinito è <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) che verrà applicato alle coordinate X e Y<br/>            quando le geometrie vengono aggiunte al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o quando vengono lette dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Il valore predefinito è [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) che verrà applicato alla coordinata Z<br/>            quando le geometrie vengono aggiunte al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o quando vengono lette dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Il valore predefinito è [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GmlOptions() {#GmlOptions__1}


```
 GmlOptions() 
```

Crea una nuova istanza.

