---
title: "GeoJsonOptions Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.gis.formats.geojson/geojsonoptions/
---

**Summary:** Driver-specific options for GeoJSON format.

**Module:** [aspose.gis.formats.geojson](/psd/python-net/aspose.gis.formats.geojson/)

**Full Name:** aspose.gis.formats.geojson.GeoJsonOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GeoJsonOptions()](#GeoJsonOptions__1) | Maak een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| array_as_string | bool | r/w | Of JSON-arrays van strings, gehele getallen of reële getallen als string worden weergegeven. |
| attributes_skip | bool | r/w | beheert de vertaling van attributen: ja - sla alle attributen over |
| auto_id | [AutoIds](/psd/python-net/aspose.gis/autoids) | r/w | Genereer id's automatisch |
| close_linear_ring | bool | r/w | Bepaalt of een niet-gesloten [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) in elke geometrie moet worden gesloten. Standaard <see langword="false" />. |
| create_midpoints | bool | r/w | Bepaalt of een nieuw punt in het midden van elk segment van de geometrie moet worden toegevoegd. Standaard <see langword="false" />. |
| date_as_string | bool | r/w | Of JSON datum/tijd/datum-tijd als string worden weergegeven. |
| delete_near_points | bool | r/w | Bepaalt of naburige punten in elke geometrie moeten worden verwijderd. Standaard <see langword="false" />. |
| delete_near_points_distance | double | r/w | Bepaalt de afstand voor [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Standaard is <see langword="0" />. |
| beschrijving | string | r/w | Beschrijving op het niveau van de feature-collectie (voor het maken van een laag) |
| geometry_as_collection | bool | r/w | bestuur de vertaling van geometrieën: ja - wikkel geometrieën in het type GeometryCollection |
| linearization_tolerance | double | r/w | Een tolerantie die gebruikt wordt om kromme geometrieën te lineariseren. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op de M-coördinaat<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| naam | string | r/w | Naam op het niveau van de feature-collectie (voor het maken van een laag) |
| nested_properties_separator | string | r/w | Haalt een string op of stelt deze in die wordt gebruikt om componenten van geneste attributen te scheiden.<br/>            Standaard is "_". |
| read_bounding_boxes | bool | r/w | Bepaalt of Bounding Boxes ('bbox') gelezen moeten worden als attributen met de naam 'bbox_0', 'bbox_1', enz.<br/>            Standaardwaarde is <see langword="false" />.<br/>            De string [GeoJsonOptions.nested_properties_separator](/psd/python-net/aspose.gis.formats.geojson/geojsonoptions/) wordt gebruikt in bbox_0, bbox_1,.. namen. |
| simplify_segments | bool | r/w | Bepaalt of punten die op hetzelfde segment liggen in elke geometrie worden verwijderd. Standaard is <see langword="false" />. |
| simplify_segments_distance | double | r/w | Bepaalt de afstand voor [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Standaard is <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Bepaalt of geometrieën gevalideerd moeten worden wanneer ze aan de laag worden toegevoegd.<br/>            Als ingesteld op <see langword="true" />, wordt [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) voor elke<br/>            geometrie aangeroepen wanneer deze aan de laag wordt toegevoegd, en als validatie faalt ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) is <see langword="false" />), wordt [GisException](/psd/python-net/aspose.gis/gisexception/) gegooid. |
| write_bounding_boxes | bool | r/w | Bepaalt of GeoJSON-objecten informatie over het coördinatenbereik voor hun geometrieën moeten bevatten.<br/>            Als ingesteld op <see langword="true" />, wordt voor elke geometrie (niet null) een lid \"bbox\" gegenereerd wanneer deze aan de laag wordt toegevoegd.<br/>            Standaardwaarde is <see langword="false" />. |
| write_polygons_as_lines | bool | r/w | Bepaalt of transformatie van polygon of multipolygon naar linestring is toegestaan. Standaard is <see langword="false" />. |
| write_unset_attribute | bool | r/w | Of niet-ingestelde attributen moeten worden weggeschreven door een 'null' waarde toe te voegen |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op X- en Y-coördinaten<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op Z-coördinaat<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GeoJsonOptions() {#GeoJsonOptions__1}


```
 GeoJsonOptions() 
```

Maak een nieuw exemplaar.

