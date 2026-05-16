---
title: "FileGdbOptions Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.gis.formats.filegdb/filegdboptions/
---

**Summary:** Driver-specific options for FileGDB format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [FileGdbOptions()](#FileGdbOptions__1) | Maak een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Bepaalt of een niet-gesloten [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) in elke geometrie moet worden gesloten. Standaard <see langword="false" />. |
| coordinate_precision_grid | [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | r/w | Een coördinatenprecisie‑raster om te gebruiken in een nieuwe laag. |
| create_midpoints | bool | r/w | Bepaalt of een nieuw punt in het midden van elk segment van de geometrie moet worden toegevoegd. Standaard <see langword="false" />. |
| delete_near_points | bool | r/w | Bepaalt of naburige punten in elke geometrie moeten worden verwijderd. Standaard <see langword="false" />. |
| delete_near_points_distance | double | r/w | Bepaalt de afstand voor [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Standaard is <see langword="0" />. |
| ensure_valid_coordinates_range | bool | r/w | Of coördinaten binnen een geldig bereik moeten liggen. |
| expected_geometry_type | Nullable<Aspose.Gis.Geometries.GeometryType> | r/w | Verwacht geometrie‑type voor de laag. Als deze optie is ingesteld, staan we alleen het toevoegen van geometrieën toe met dit type |
| geometry_field_name | string | r/w | Naam van het geometrie‑veld. |
| has_m | bool | r/w | Kunnen geometrieën van de laag een 'm'-coördinaat hebben. Standaard is true |
| has_z | bool | r/w | Kunnen geometrieën van de laag een 'z'-coördinaat hebben. Standaard is true |
| linearization_tolerance | double | r/w | Een tolerantie die gebruikt wordt om kromme geometrieën te lineariseren. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op de M-coördinaat<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| m_tolerance | Nullable<double> | r/w | M snap-tolerantie. |
| object_id_field_name | string | r/w | Naam van het object-ID-veld. |
| simplify_segments | bool | r/w | Bepaalt of punten die op hetzelfde segment liggen in elke geometrie worden verwijderd. Standaard is <see langword="false" />. |
| simplify_segments_distance | double | r/w | Bepaalt de afstand voor [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Standaard is <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Bepaalt of geometrieën gevalideerd moeten worden wanneer ze aan de laag worden toegevoegd.<br/>            Als ingesteld op <see langword="true" />, wordt [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) voor elke<br/>            geometrie aangeroepen wanneer deze aan de laag wordt toegevoegd, en als validatie faalt ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) is <see langword="false" />), wordt [GisException](/psd/python-net/aspose.gis/gisexception/) gegooid. |
| write_polygons_as_lines | bool | r/w | Bepaalt of transformatie van polygon of multipolygon naar linestring is toegestaan. Standaard is <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op X- en Y-coördinaten<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| xy_tolerance | Nullable<double> | r/w | X- en Y-snap-tolerantie. |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op Z-coördinaat<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_tolerance | Nullable<double> | r/w | Z snap-tolerantie. |


### Constructor: FileGdbOptions() {#FileGdbOptions__1}


```
 FileGdbOptions() 
```

Maak een nieuw exemplaar.

