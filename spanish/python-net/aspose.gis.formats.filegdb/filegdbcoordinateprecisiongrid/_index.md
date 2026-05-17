---
title: "Clase FileGdbCoordinatePrecisionGrid"
type: docs
weight: 10
url: /es/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Descripción** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | Inicializa una nueva instancia de la clase FileGdbCoordinatePrecisionGrid |
## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | Obtiene o establece el origen de la coordenada M. Si se establece en <see langword=\"null\" /> se usa el valor predeterminado. |
| m_scale | Nullable<double> | r/w | Obtiene o establece la escala de la coordenada M. Si se establece en <see langword=\"null\" /> se usa el valor predeterminado. |
| x_origin | Nullable<double> | r/w | Obtiene o establece el origen de la coordenada X. Si se establece en <see langword=\"null\" /> se usa el valor predeterminado. |
| xy_scale | Nullable<double> | r/w | Obtiene o establece la escala de las coordenadas X y Y. Si se establece en <see langword=\"null\" /> se usa el valor predeterminado. |
| y_origin | Nullable<double> | r/w | Obtiene o establece el origen de la coordenada Y. Si se establece en <see langword=\"null\" /> se usa el valor predeterminado. |
| z_origin | Nullable<double> | r/w | Obtiene o establece el origen de la coordenada Z. Si se establece en <see langword=\"null\" /> se usa el valor predeterminado. |
| z_scale | Nullable<double> | r/w | Obtiene o establece la escala de la coordenada Z. Si se establece en <see langword=\"null\" /> se usa el valor predeterminado. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Crea un nuevo <c>FileGdbCoordinatePrecisionGrid</c> de modo que todos los valores dentro de un rectángulo sean representables. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

Inicializa una nueva instancia de la clase FileGdbCoordinatePrecisionGrid

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Crea un nuevo <c>FileGdbCoordinatePrecisionGrid</c> de modo que todos los valores dentro de un rectángulo sean representables.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Una esquina del rectángulo. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Esquina opuesta del rectángulo. Debe tener las mismas dimensiones que <paramref name=\"p1\" />. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | El <c>FileGdbCoordinatePrecisionGrid</c> de modo que todos los valores dentro de un rectángulo sean representables.<br/>            Los valores fuera del rectángulo no son representables, por lo que todas las coordenadas que se escribirán en la capa FileGDB<br/>            deben estar dentro del rectángulo. |


