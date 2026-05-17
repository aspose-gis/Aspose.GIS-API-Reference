---
title: "Clase GmlOptions"
type: docs
weight: 20
url: /es/python-net/aspose.gis.formats.gml/gmloptions/
---

**Summary:** Driver-specific options for GML format.

**Module:** [aspose.gis.formats.gml](/psd/python-net/aspose.gis.formats.gml/)

**Full Name:** aspose.gis.formats.gml.GmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [GmlOptions()](#GmlOptions__1) | Crear una nueva instancia. |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| application_namespace | string | r/w | Esto especifica un espacio de nombres personalizado que se usará como el espacio de nombres de la aplicación para generar el documento gml. |
| close_linear_ring | bool | r/w | Determina si cerrar un [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) sin cerrar en cada geometría. Por defecto es <see langword="false" />. |
| create_midpoints | bool | r/w | Determina si agregar un nuevo punto en el medio a cada segmento de la geometría. Por defecto es <see langword="false" />. |
| delete_near_points | bool | r/w | Determina si eliminar puntos cercanos en cada geometría. Por defecto es <see langword="false" />. |
| delete_near_points_distance | double | r/w | Determina la distancia para [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). El valor predeterminado es <see langword="0" />. |
| linearization_tolerance | double | r/w | Una tolerancia para linealizar geometrías curvas. |
| load_schemas_from_internet | bool | r/w | Determina si Aspose.GIS tiene permiso para cargar esquemas XML desde Internet.<br/>            Si se establece en <see langword="false" />, los esquemas con URIs absolutas que no comiencen con 'file://' no se cargarán.<br/>            El valor predeterminado es <see langword="false" />. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a la coordenada M<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | r/w | Obtiene o establece una cadena que se usa para separar los componentes de atributos anidados.<br/>            El valor predeterminado es "_". |
| restore_schema | bool | r/w | Determina si Aspose.GIS tiene permiso para analizar atributos en un archivo Gml en el que falta un esquema XML o no se puede cargar.<br/>            Si se establece en <see langword="true" />, el lector de Aspose.GIS no requiere la presencia de un esquema XML.<br/>            El valor predeterminado es <see langword="false" />. |
| schema_location | string | r/w | Lista de pares de URI separados por espacios. El primer URI de cada par es un URI del espacio de nombres, el segundo URI es una ruta al esquema XML del espacio de nombres.<br/>            Si se establece en <see langword="null" />, [GmlDriver](/psd/python-net/aspose.gis.formats.gml/gmldriver/) intentará leer schemaLocation del elemento raíz del documento.<br/>            El valor predeterminado es <see langword="null" />. |
| simplify_segments | bool | r/w | Determina si eliminar puntos que se encuentran en el mismo segmento en cada geometría. El valor predeterminado es <see langword="false" />. |
| simplify_segments_distance | double | r/w | Determina la distancia para [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). El valor predeterminado es <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Determina si las geometrías deben validarse cuando se añaden a la capa.<br/>            Si se establece en <see langword="true" />, se llama a [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) para cada<br/>            geometría cuando se añade a la capa, y si la validación falla ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) es <see langword="false" />), se lanza [GisException](/psd/python-net/aspose.gis/gisexception/). |
| write_polygons_as_lines | bool | r/w | Determina si se permite la transformación de polígono o multipolígono a linestring. El valor predeterminado es <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a las coordenadas X e Y<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) que se aplicará a la coordenada Z<br/>            cuando se añadan geometrías al [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) o cuando se lean del [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            El valor predeterminado es [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GmlOptions() {#GmlOptions__1}


```
 GmlOptions() 
```

Crear una nueva instancia.

