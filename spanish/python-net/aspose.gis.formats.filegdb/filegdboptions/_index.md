---
title: "Clase FileGdbOptions"
type: docs
weight: 30
url: /es/python-net/aspose.gis.formats.filegdb/filegdboptions/
---

**Summary:** Driver-specific options for FileGDB format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [FileGdbOptions()](#FileGdbOptions__1) | Crear una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Determina si cerrar un [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) sin cerrar en cada geometría. Por defecto es <see langword="false" />. |
| coordinate_precision_grid | [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | r/w | Una cuadrícula de precisión de coordenadas para usar en una capa nueva. |
| create_midpoints | bool | r/w | Determina si agregar un nuevo punto en el medio a cada segmento de la geometría. Por defecto es <see langword="false" />. |
| delete_near_points | bool | r/w | Determina si eliminar puntos cercanos en cada geometría. Por defecto es <see langword="false" />. |
| delete_near_points_distance | double | r/w | Determina la distancia para [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). El valor predeterminado es <see langword="0" />. |
| ensure_valid_coordinates_range | bool | r/w | Indica si las coordenadas deben estar en un rango válido. |
| expected_geometry_type | Nullable<Aspose.Gis.Geometries.GeometryType> | r/w | Tipo de geometría esperado para la capa. Si se establece esta opción, solo se permite agregar geometrías de este tipo |
| geometry_field_name | string | r/w | Nombre del campo de geometría. |
| has_m | bool | r/w | ¿Pueden las geometrías de la capa tener coordenada 'm'? Por defecto es verdadero |
| has_z | bool | r/w | ¿Pueden las geometrías de la capa tener coordenada 'z'? Por defecto es verdadero |
| linearization_tolerance | double | r/w | Una tolerancia para linealizar geometrías curvas. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a la coordenada M<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| m_tolerance | Nullable<double> | r/w | Tolerancia de ajuste M. |
| object_id_field_name | string | r/w | Nombre del campo de ID del objeto. |
| simplify_segments | bool | r/w | Determina si eliminar puntos que se encuentran en el mismo segmento en cada geometría. El valor predeterminado es <see langword="false" />. |
| simplify_segments_distance | double | r/w | Determina la distancia para [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). El valor predeterminado es <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Determina si las geometrías deben validarse cuando se añaden a la capa.<br/>            Si se establece en <see langword="true" />, se llama a [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) para cada<br/>            geometría cuando se añade a la capa, y si la validación falla ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) es <see langword="false" />), se lanza [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Determina si se permite la transformación de polígono o multipolígono a linestring. El valor predeterminado es <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a las coordenadas X e Y<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| xy_tolerance | Nullable<double> | r/w | Tolerancia de ajuste X y Y. |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a la coordenada Z<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_tolerance | Nullable<double> | r/w | Tolerancia de ajuste Z. |


### Constructor: FileGdbOptions() {#FileGdbOptions__1}


```
 FileGdbOptions() 
```

Crear una nueva instancia.

