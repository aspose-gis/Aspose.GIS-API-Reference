---
title: "GpxOptions klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.gis.formats.gpx/gpxoptions/
---

**Summary:** Driver-specific options for GPX format.

**Module:** [aspose.gis.formats.gpx](/psd/python-net/aspose.gis.formats.gpx/)

**Full Name:** aspose.gis.formats.gpx.GpxOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [GpxOptions()](#GpxOptions__1) | Maak een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Bepaalt of een niet-gesloten [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) in elke geometrie moet worden gesloten. Standaard <see langword="false" />. |
| create_midpoints | bool | r/w | Bepaalt of een nieuw punt in het midden van elk segment van de geometrie moet worden toegevoegd. Standaard <see langword="false" />. |
| delete_near_points | bool | r/w | Bepaalt of naburige punten in elke geometrie moeten worden verwijderd. Standaard <see langword="false" />. |
| delete_near_points_distance | double | r/w | Bepaalt de afstand voor [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Standaard is <see langword="0" />. |
| linearization_tolerance | double | r/w | Een tolerantie die gebruikt wordt om kromme geometrieën te lineariseren. |
| m_attribute | string | r/w | Bepaalt welk GPX-attribuut wordt geëxporteerd als 'M'-coördinaat van waypoints, routepunten en trackpunten.<br/>            Het gedrag is hetzelfde als bij [GpxOptions.z_attribute](/psd/python-net/aspose.gis.formats.gpx/gpxoptions/), standaard <see langword="null" />. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op de M-coördinaat<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_attribute_separator | string | r | Een string om de naam van een genest attribuut en de bijbehorende indexen te scheiden. Standaard is dubbele onderstreping "__". |
| read_nested_attributes | bool | r/w | Bepaalt of GPX-punten, zoals 'trkpt' en 'rtept', interne attributen bevatten en of deze gelezen moeten worden. Standaard <see langword="false" />. |
| simplify_segments | bool | r/w | Bepaalt of punten die op hetzelfde segment liggen in elke geometrie worden verwijderd. Standaard is <see langword="false" />. |
| simplify_segments_distance | double | r/w | Bepaalt de afstand voor [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Standaard is <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Bepaalt of geometrieën gevalideerd moeten worden wanneer ze aan de laag worden toegevoegd.<br/>            Als ingesteld op <see langword="true" />, wordt [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) voor elke<br/>            geometrie aangeroepen wanneer deze aan de laag wordt toegevoegd, en als validatie faalt ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) is <see langword="false" />), wordt [GisException](/psd/python-net/aspose.gis/gisexception/) gegooid. |
| write_polygons_as_lines | bool | r/w | Bepaalt of transformatie van polygon of multipolygon naar linestring is toegestaan. Standaard is <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op X- en Y-coördinaten<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_attribute | string | r/w | Bepaalt welk GPX-attribuut wordt geëxporteerd als 'Z'-coördinaat van waypoints, routepunten en trackpunten.<br/>            Als <see langword="null" /> - wordt er geen attribuut geëxporteerd als 'Z'-coördinaat.<br/>            Standaard "ele".<br/>            Mogelijke waarden zijn namen van alle GPX XML-attributen die als double kunnen worden weergegeven (bijv. "speed", "magvar", "geoidheight" enz.) |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op Z-coördinaat<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GpxOptions() {#GpxOptions__1}


```
 GpxOptions() 
```

Maak een nieuw exemplaar.

