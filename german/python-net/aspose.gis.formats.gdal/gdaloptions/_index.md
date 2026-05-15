---
title: "GdalOptions Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.gis.formats.gdal/gdaloptions/
---

**Summary:** Driver-specific options for GDAL format.

**Module:** [aspose.gis.formats.gdal](/psd/python-net/aspose.gis.formats.gdal/)

**Full Name:** aspose.gis.formats.gdal.GdalOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GdalOptions(temp_directory)](#GdalOptions_temp_directory_1) | Erstelle eine neue Instanz. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Bestimmt, ob ein nicht geschlossener [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) in jeder Geometrie geschlossen wird. Standardwert ist <see langword="false" />. |
| create_midpoints | bool | r/w | Bestimmt, ob ein neuer Punkt in der Mitte zu jedem Segment der Geometrie hinzugefügt wird. Standardwert ist <see langword="false" />. |
| delete_near_points | bool | r/w | Bestimmt, ob nahe Punkte in jeder Geometrie gelöscht werden. Standardwert ist <see langword="false" />. |
| delete_near_points_distance | double | r/w | Bestimmt die Entfernung für [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Standardwert ist <see langword=\"0\" />. |
| file_name | string | r/w | Name der zu startenden Anwendung |
| linearization_tolerance | double | r/w | Ein Toleranzwert, der zur Lineariserung von Kurvengeometrien verwendet wird. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ein [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), das auf die M‑Koordinate angewendet wird<br/>            wenn Geometrien zum [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) hinzugefügt werden oder wenn sie aus dem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) gelesen werden.<br/>            Der Standardwert ist [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| path_to_temp_file | string | r | Pfad zu temporären Dateien. |
| simplify_segments | bool | r/w | Bestimmt, ob Punkte, die auf demselben Segment jeder Geometrie liegen, gelöscht werden. Standardwert ist <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | Bestimmt die Entfernung für [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Standardwert ist <see langword=\"0\" />. |
| validate_geometries_on_write | bool | r/w | Bestimmt, ob Geometrien validiert werden sollen, wenn sie zur Ebene hinzugefügt werden.<br/>            Wenn auf <see langword=\"true\" /> gesetzt, wird für jede<br/>            Geometrie, die zur Ebene hinzugefügt wird, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) aufgerufen, und wenn die Validierung fehlschlägt ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) ist <see langword=\"false\" />), wird eine [GisException](/psd/python-net/aspose.gis/gisexception/) ausgelöst. |
| write_polygons_as_lines | bool | r/w | Bestimmt, ob die Umwandlung von Polygon oder Multipolygon in einen Linestring erlaubt ist. Standardwert ist <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ein [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), das auf X‑ und Y‑Koordinaten angewendet wird<br/>            wenn Geometrien zum [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) hinzugefügt werden oder wenn sie aus dem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) gelesen werden.<br/>            Der Standardwert ist [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ein [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), das auf die Z‑Koordinate angewendet wird<br/>            wenn Geometrien zum [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) hinzugefügt werden oder wenn sie aus dem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) gelesen werden.<br/>            Der Standardwert ist [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GdalOptions(temp_directory) {#GdalOptions_temp_directory_1}


```
 GdalOptions(temp_directory) 
```

Erstelle eine neue Instanz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| temp_directory | string | Pfad zu temporären Dateien. Standardmäßig das temporäre Verzeichnis des Benutzers. |

