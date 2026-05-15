---
title: "KmlOptions Klasse"
type: docs
weight: 190
url: /de/python-net/aspose.gis.formats.kml/kmloptions/
---

**Summary:** Driver-specific options for KML format.

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [KmlOptions()](#KmlOptions__1) | Neue Instanz erstellen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| altitude_mode | [AltitudeModes](/psd/python-net/aspose.gis.formats.kml/altitudemodes) | r/w | Ermöglicht das Festlegen der AltitudeModes, die für KML-Geometrien verwendet werden sollen |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | IDs automatisch generieren |
| close_linear_ring | bool | r/w | Bestimmt, ob ein nicht geschlossener [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) in jeder Geometrie geschlossen wird. Standardwert ist <see langword="false" />. |
| create_midpoints | bool | r/w | Bestimmt, ob ein neuer Punkt in der Mitte zu jedem Segment der Geometrie hinzugefügt wird. Standardwert ist <see langword="false" />. |
| delete_near_points | bool | r/w | Bestimmt, ob nahe Punkte in jeder Geometrie gelöscht werden. Standardwert ist <see langword="false" />. |
| delete_near_points_distance | double | r/w | Bestimmt die Entfernung für [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Standardwert ist <see langword=\"0\" />. |
| document_id | string | r/w | Wird verwendet, um die ID des Wurzel-'Document'-Knotens anzugeben |
| linearization_tolerance | double | r/w | Ein Toleranzwert, der zur Lineariserung von Kurvengeometrien verwendet wird. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ein [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), das auf die M‑Koordinate angewendet wird<br/>            wenn Geometrien zum [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) hinzugefügt werden oder wenn sie aus dem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) gelesen werden.<br/>            Der Standardwert ist [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | r/w | Bestimmt, ob Punkte, die auf demselben Segment jeder Geometrie liegen, gelöscht werden. Standardwert ist <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | Bestimmt die Entfernung für [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Standardwert ist <see langword=\"0\" />. |
| symbol_to_replace_invalid_chars | char | r/w | Bestimmt, welches Symbol beim Lesen zum Ersetzen ungültiger Zeichen verwendet wird.<br/>            Das Ersetzen wird übersprungen, wenn der Wert '\0' ist. Standardmäßig ist der Wert das Zeichen '\0'. |
| validate_geometries_on_write | bool | r/w | Bestimmt, ob Geometrien validiert werden sollen, wenn sie zur Ebene hinzugefügt werden.<br/>            Wenn auf <see langword=\"true\" /> gesetzt, wird für jede<br/>            Geometrie, die zur Ebene hinzugefügt wird, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) aufgerufen, und wenn die Validierung fehlschlägt ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) ist <see langword=\"false\" />), wird eine [GisException](/psd/python-net/aspose.gis/gisexception/) ausgelöst. |
| write_polygons_as_lines | bool | r/w | Bestimmt, ob die Umwandlung von Polygon oder Multipolygon in einen Linestring erlaubt ist. Standardwert ist <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ein [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), das auf X‑ und Y‑Koordinaten angewendet wird<br/>            wenn Geometrien zum [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) hinzugefügt werden oder wenn sie aus dem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) gelesen werden.<br/>            Der Standardwert ist [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ein [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), das auf die Z‑Koordinate angewendet wird<br/>            wenn Geometrien zum [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) hinzugefügt werden oder wenn sie aus dem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) gelesen werden.<br/>            Der Standardwert ist [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: KmlOptions() {#KmlOptions__1}


```
 KmlOptions() 
```

Neue Instanz erstellen.

