---
title: "Clase CsvOptions"
type: docs
weight: 20
url: /es/python-net/aspose.gis.formats.csv/csvoptions/
---

**Summary:** Driver-specific options for CSV format.

**Module:** [aspose.gis.formats.csv](/psd/python-net/aspose.gis.formats.csv/)

**Full Name:** aspose.gis.formats.csv.CsvOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [CsvOptions()](#CsvOptions__1) | Crear una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Determina si cerrar un [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) sin cerrar en cada geometría. Por defecto es <see langword="false" />. |
| column_m | string | r/w | Obtiene o establece el nombre de la columna que contiene el valor de la coordenada M.<br/>            El valor predeterminado es <see langword=\"null\" />. |
| column_wkt | string | r/w | Obtiene o establece el nombre de la columna que contiene Well-Known Text para representar la geometría.<br/>            El valor predeterminado es <see langword=\"null\" />. |
| column_x | string | r/w | Obtiene o establece el nombre de la columna que contiene el valor de la coordenada X.<br/>            El valor predeterminado es <see langword=\"null\" />. |
| column_y | string | r/w | Obtiene o establece el nombre de la columna que contiene el valor de la coordenada Y.<br/>            El valor predeterminado es <see langword=\"null\" />. |
| column_z | string | r/w | Obtiene o establece el nombre de la columna que contiene el valor de la coordenada Z.<br/>            El valor predeterminado es <see langword=\"null\" />. |
| create_midpoints | bool | r/w | Determina si agregar un nuevo punto en el medio a cada segmento de la geometría. Por defecto es <see langword="false" />. |
| delete_near_points | bool | r/w | Determina si eliminar puntos cercanos en cada geometría. Por defecto es <see langword="false" />. |
| delete_near_points_distance | double | r/w | Determina la distancia para [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). El valor predeterminado es <see langword="0" />. |
| delimitador | char | r/w | Obtiene o establece un carácter que se usa como delimitador para separar valores.<br/>            El valor predeterminado es ','. |
| double_quote_escape | char | r/w | Obtiene o establece un carácter que se usa como carácter de escape para comillas dobles.<br/>            El valor predeterminado es '\"'. |
| has_attribute_names | bool | r/w | Determina si existe una fila de encabezado con nombres de atributos.<br/>            El valor predeterminado es <see langword=\"true\" />. |
| linearization_tolerance | double | r/w | Una tolerancia para linealizar geometrías curvas. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a la coordenada M<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| simplify_segments | bool | r/w | Determina si eliminar puntos que se encuentran en el mismo segmento en cada geometría. El valor predeterminado es <see langword="false" />. |
| simplify_segments_distance | double | r/w | Determina la distancia para [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). El valor predeterminado es <see langword="0" />. |
| start_line_number | int | r/w | Obtiene o establece un número de línea basado en cero que será el primero al leer los datos.<br/>            El valor predeterminado es 0. |
| validate_geometries_on_write | bool | r/w | Determina si las geometrías deben validarse cuando se añaden a la capa.<br/>            Si se establece en <see langword="true" />, se llama a [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) para cada<br/>            geometría cuando se añade a la capa, y si la validación falla ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) es <see langword="false" />), se lanza [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Determina si se permite la transformación de polígono o multipolígono a linestring. El valor predeterminado es <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a las coordenadas X e Y<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a la coordenada Z<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: CsvOptions() {#CsvOptions__1}


```
 CsvOptions() 
```

Crear una nueva instancia.

