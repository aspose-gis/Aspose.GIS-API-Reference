---
title: "SqlServerOptions-klass"
type: docs
weight: 20
url: /sv/python-net/aspose.gis.formats.sqlserver/sqlserveroptions/
---

**Summary:** Driver-specific options for SqlServer format.<br/>            At the moment, the driver provides no customizable options.

**Module:** [aspose.gis.formats.sqlserver](/psd/python-net/aspose.gis.formats.sqlserver/)

**Full Name:** aspose.gis.formats.sqlserver.SqlServerOptions

**Inheritance:** DatabaseDriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [SqlServerOptions()](#SqlServerOptions__1) | Skapa ny instans. |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Avgör om en oöppnad [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) ska stängas i varje geometri. Standardvärdet är <see langword="false" />. |
| create_midpoints | bool | läs/skriv | Avgör om en ny punkt ska läggas till i mitten av varje segment i geometrin. Standardvärdet är <see langword="false" />. |
| delete_near_points | bool | läs/skriv | Avgör om närliggande punkter ska tas bort i varje geometri. Standardvärdet är <see langword="false" />. |
| delete_near_points_distance | double | r/w | Bestämmer avstånd för [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Standardvärdet är <see langword=\"0\" />. |
| linearization_tolerance | double | läs/skriv | En tolerans att använda för att linjärisera kurvgeometrier. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | En [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) som kommer att tillämpas på M-koordinaten<br/>            när geometrier läggs till i [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eller när de läses från [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Standardvärdet är [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | läs/skriv | Bestämmer om punkter som ligger på samma segment i varje geometri ska tas bort. Standardvärdet är <see langword=\"false\" />. |
| simplify_segments_distance | double | r/w | Bestämmer avstånd för [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Standardvärdet är <see langword=\"0\" />. |
| spatial_reference_system_mode | [SpatialReferenceSystemMode](/psd/python-net/aspose.gis/spatialreferencesystemmode) | r/w | Bestämmer hur den okända geometriens SRS för databasen ska hanteras när de läggs till i lagret.<br/>            Standardvärdet är [SpatialReferenceSystemMode.THROW_EXCEPTION](/psd/python-net/aspose.gis/spatialreferencesystemmode/). |
| validate_geometries_on_write | bool | r/w | Bestämmer om geometrier ska valideras när de läggs till i lagret.<br/>            Om den är satt till <see langword=\"true\" />, anropas [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) för varje<br/>            geometri när den läggs till i lagret, och om valideringen misslyckas ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) är <see langword=\"false\" />), kastas [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | läs/skriv | Bestämmer om omvandling av polygon eller multipolygon till linjesträng är tillåten. Standardvärdet är <see langword=\"false\" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | En [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) som kommer att tillämpas på X- och Y-koordinaterna<br/>            när geometrier läggs till i [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eller när de läses från [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Standardvärdet är [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | En [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) som kommer att tillämpas på Z-koordinaten<br/>            när geometrier läggs till i [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) eller när de läses från [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            Standardvärdet är [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: SqlServerOptions() {#SqlServerOptions__1}


```
 SqlServerOptions() 
```

Skapa ny instans.

