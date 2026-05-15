---
title: "GeoJsonOptions Klasse"
type: docs
weight: 20
url: /de/python-net/aspose.gis.formats.geojson/geojsonoptions/
---

**Summary:** Driver-specific options for GeoJSON format.

**Module:** [aspose.gis.formats.geojson](/psd/python-net/aspose.gis.formats.geojson/)

**Full Name:** aspose.gis.formats.geojson.GeoJsonOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschreibung** |
| :- | :- |
| [GeoJsonOptions()](#GeoJsonOptions__1) | Neue Instanz erstellen. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| array_as_string | bool | r/w | Ob JSon-Arrays von Zeichenketten, Ganzzahlen oder Gleitkommazahlen als Zeichenkette dargestellt werden sollen. |
| attributes_skip | bool | r/w | Steuert die Übersetzung von Attributen: ja – alle Attribute überspringen |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | IDs automatisch generieren |
| close_linear_ring | bool | r/w | Bestimmt, ob ein nicht geschlossener [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) in jeder Geometrie geschlossen wird. Standardwert ist <see langword="false" />. |
| create_midpoints | bool | r/w | Bestimmt, ob ein neuer Punkt in der Mitte zu jedem Segment der Geometrie hinzugefügt wird. Standardwert ist <see langword="false" />. |
| date_as_string | bool | r/w | Ob JSon-Datum/Uhrzeit/Datum-Uhrzeit als Zeichenkette dargestellt werden soll. |
| delete_near_points | bool | r/w | Bestimmt, ob nahe Punkte in jeder Geometrie gelöscht werden. Standardwert ist <see langword="false" />. |
| delete_near_points_distance | double | r/w | Bestimmt die Entfernung für [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Standardwert ist <see langword=\"0\" />. |
| Beschreibung | string | r/w | Beschreibung auf Ebene der Feature‑Sammlung (für die Layer‑Erstellung) |
| geometry_as_collection | bool | r/w | Steuert die Übersetzung von Geometrien: ja – umschließt Geometrien mit dem Typ GeometryCollection |
| linearization_tolerance | double | r/w | Ein Toleranzwert, der zur Lineariserung von Kurvengeometrien verwendet wird. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ein [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), das auf die M‑Koordinate angewendet wird<br/>            wenn Geometrien zum [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) hinzugefügt werden oder wenn sie aus dem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) gelesen werden.<br/>            Der Standardwert ist [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| Name | string | r/w | Name auf Ebene der Feature‑Sammlung (für die Layer‑Erstellung) |
| nested_properties_separator | string | r/w | Liest oder setzt eine Zeichenfolge, die zum Trennen von Komponenten verschachtelter Attribute verwendet wird.<br/>            Standard ist \"_\". |
| read_bounding_boxes | bool | r/w | Bestimmt, ob Bounding Boxes ('bbox') als Attribute mit dem Namen 'bbox_0', 'bbox_1' usw. gelesen werden sollen.<br/>            Standardwert ist <see langword="false" />.<br/>            Die Zeichenkette [GeoJsonOptions.nested_properties_separator](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions/) wird in den Namen bbox_0, bbox_1,.. verwendet. |
| simplify_segments | bool | r/w | Bestimmt, ob Punkte, die auf demselben Segment jeder Geometrie liegen, gelöscht werden. Standardwert ist <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | Bestimmt die Entfernung für [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Standardwert ist <see langword=\"0\" />. |
| validate_geometries_on_write | bool | r/w | Bestimmt, ob Geometrien validiert werden sollen, wenn sie zur Ebene hinzugefügt werden.<br/>            Wenn auf <see langword=\"true\" /> gesetzt, wird für jede<br/>            Geometrie, die zur Ebene hinzugefügt wird, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) aufgerufen, und wenn die Validierung fehlschlägt ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) ist <see langword=\"false\" />), wird eine [GisException](/psd/python-net/aspose.gis/gisexception/) ausgelöst. |
| write_bounding_boxes | bool | r/w | Bestimmt, ob GeoJSON-Objekte Informationen über den Koordinatenbereich ihrer Geometrien enthalten sollen.<br/>            Wenn auf <see langword="true" /> gesetzt, wird für jede Geometrie (nicht null), die dem Layer hinzugefügt wird, ein Mitglied "bbox" erzeugt.<br/>            Standardwert ist <see langword="false" />. |
| write_polygons_as_lines | bool | r/w | Bestimmt, ob die Umwandlung von Polygon oder Multipolygon in einen Linestring erlaubt ist. Standardwert ist <see langword=\"false\" />. |
| write_unset_attribute | bool | r/w | Ob nicht gesetzte Attribute durch Hinzufügen des Werts 'null' geschrieben werden sollen |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ein [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), das auf X‑ und Y‑Koordinaten angewendet wird<br/>            wenn Geometrien zum [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) hinzugefügt werden oder wenn sie aus dem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) gelesen werden.<br/>            Der Standardwert ist [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Ein [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/), das auf die Z‑Koordinate angewendet wird<br/>            wenn Geometrien zum [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) hinzugefügt werden oder wenn sie aus dem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) gelesen werden.<br/>            Der Standardwert ist [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GeoJsonOptions() {#GeoJsonOptions__1}


```
 GeoJsonOptions() 
```

Neue Instanz erstellen.

