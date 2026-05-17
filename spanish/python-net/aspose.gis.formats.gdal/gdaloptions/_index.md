---
title: "Clase GdalOptions"
type: docs
weight: 20
url: /es/python-net/aspose.gis.formats.gdal/gdaloptions/
---

**Summary:** Driver-specific options for GDAL format.

**Module:** [aspose.gis.formats.gdal](/psd/python-net/aspose.gis.formats.gdal/)

**Full Name:** aspose.gis.formats.gdal.GdalOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GdalOptions(temp_directory)](#GdalOptions_temp_directory_1) | Crea una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Determina si cerrar un [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) sin cerrar en cada geometría. Por defecto es <see langword="false" />. |
| create_midpoints | bool | r/w | Determina si agregar un nuevo punto en el medio a cada segmento de la geometría. Por defecto es <see langword="false" />. |
| delete_near_points | bool | r/w | Determina si eliminar puntos cercanos en cada geometría. Por defecto es <see langword="false" />. |
| delete_near_points_distance | double | r/w | Determina la distancia para [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). El valor predeterminado es <see langword="0" />. |
| file_name | string | r/w | Nombre de la aplicación a iniciar |
| linearization_tolerance | double | r/w | Una tolerancia para linealizar geometrías curvas. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a la coordenada M<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| path_to_temp_file | string | r | Ruta a archivos temporales. |
| simplify_segments | bool | r/w | Determina si eliminar puntos que se encuentran en el mismo segmento en cada geometría. El valor predeterminado es <see langword="false" />. |
| simplify_segments_distance | double | r/w | Determina la distancia para [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). El valor predeterminado es <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Determina si las geometrías deben validarse cuando se añaden a la capa.<br/>            Si se establece en <see langword="true" />, se llama a [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) para cada<br/>            geometría cuando se añade a la capa, y si la validación falla ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) es <see langword="false" />), se lanza [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Determina si se permite la transformación de polígono o multipolígono a linestring. El valor predeterminado es <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a las coordenadas X e Y<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a la coordenada Z<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GdalOptions(temp_directory) {#GdalOptions_temp_directory_1}


```
 GdalOptions(temp_directory) 
```

Crea una nueva instancia.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| temp_directory | string | Ruta a archivos temporales. Carpeta temporal del usuario por defecto. |

