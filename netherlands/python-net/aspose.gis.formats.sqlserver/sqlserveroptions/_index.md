---
title: "SqlServerOptions Klasse"
type: docs
weight: 20
url: /nl/python-net/aspose.gis.formats.sqlserver/sqlserveroptions/
---

**Summary:** Driver-specific options for SqlServer format.<br/>            At the moment, the driver provides no customizable options.

**Module:** [aspose.gis.formats.sqlserver](/psd/python-net/aspose.gis.formats.sqlserver/)

**Full Name:** aspose.gis.formats.sqlserver.SqlServerOptions

**Inheritance:** DatabaseDriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [SqlServerOptions()](#SqlServerOptions__1) | Maak een nieuw exemplaar. |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Bepaalt of een niet-gesloten [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) in elke geometrie moet worden gesloten. Standaard <see langword="false" />. |
| create_midpoints | bool | r/w | Bepaalt of een nieuw punt in het midden van elk segment van de geometrie moet worden toegevoegd. Standaard <see langword="false" />. |
| delete_near_points | bool | r/w | Bepaalt of naburige punten in elke geometrie moeten worden verwijderd. Standaard <see langword="false" />. |
| delete_near_points_distance | double | r/w | Bepaalt de afstand voor [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Standaard is <see langword="0" />. |
| linearization_tolerance | double | r/w | Een tolerantie die gebruikt wordt om kromme geometrieën te lineariseren. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op de M-coördinaat<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | r/w | Bepaalt of punten die op hetzelfde segment liggen in elke geometrie worden verwijderd. Standaard is <see langword="false" />. |
| simplify_segments_distance | double | r/w | Bepaalt de afstand voor [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Standaard is <see langword="0" />. |
| spatial_reference_system_mode | [SpatialReferenceSystemMode](/psd/python-net/aspose.gis/spatialreferencesystemmode) | r/w | Bepaalt hoe de SRS van onbekende geometrieën voor de database moet worden afgehandeld wanneer ze aan de laag worden toegevoegd.<br/>            De standaardwaarde is [SpatialReferenceSystemMode.THROW_EXCEPTION](/psd/python-net/aspose.gis/spatialreferencesystemmode/). |
| validate_geometries_on_write | bool | r/w | Bepaalt of geometrieën gevalideerd moeten worden wanneer ze aan de laag worden toegevoegd.<br/>            Als ingesteld op <see langword="true" />, wordt [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) voor elke<br/>            geometrie aangeroepen wanneer deze aan de laag wordt toegevoegd, en als validatie faalt ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) is <see langword="false" />), wordt [GisException](/psd/python-net/aspose.gis/gisexception/) gegooid. |
| write_polygons_as_lines | bool | r/w | Bepaalt of transformatie van polygon of multipolygon naar linestring is toegestaan. Standaard is <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op X- en Y-coördinaten<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Een [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) die wordt toegepast op Z-coördinaat<br/>            wanneer geometrieën worden toegevoegd aan de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) of wanneer ze worden gelezen uit de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            De standaardwaarde is [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: SqlServerOptions() {#SqlServerOptions__1}


```
 SqlServerOptions() 
```

Maak een nieuw exemplaar.

