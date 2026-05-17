---
title: "Clase DynamicFeature"
type: docs
weight: 650
url: /es/python-net/aspose.gis/dynamicfeature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.DynamicFeature

**Inheritance:** Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Obtiene o establece la geometría del feature.<br/>            No puede ser <see langword="null" />, use [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) para indicar geometría faltante. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Copia los valores de los atributos de otro feature. |
| [get_as_node()](#get_as_node__2) | Obtiene la característica como nodo. Esto puede ser útil para los datos personalizados |
| [get_value(attribute_name)](#get_value_attribute_name_3) | Obtiene el valor de un atributo. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_4) | Obtiene el valor de un atributo, o [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) si el valor no está establecido o <c>null</c>. |
| [get_values(values, default_value)](#get_values_values_default_value_5) | Devuelve los valores de todos los atributos en una matriz. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_6) | Devuelve los valores de todos los atributos en una matriz. |
| [get_values_dump(default_value)](#get_values_dump_default_value_7) | Devuelve los valores de todos los atributos en una matriz.<br/>            Considere usar el método Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) para evitar asignaciones de memoria adicionales. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_8) | Obtiene los valores de una secuencia de atributos como una lista. |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_9) | Determina si el atributo especificado ha sido establecido explícitamente al valor <c>null</c>. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_10) | Comprueba si el valor del atributo está establecido en esta característica. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_11) | Establece un nuevo valor de un atributo. |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_12) | Establece el valor del atributo a <c>null</c>. |
| [set_values(values)](#set_values_values_13) | Establece nuevos valores para todos los atributos.<br/>            También considere usar el método [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) para simplificar la asignación de valores en una sola llamada. |
| [unset_value(attribute_name)](#unset_value_attribute_name_14) | Elimina el valor del atributo de esta característica. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Copia los valores de los atributos de otro feature.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | La característica de la cual copiar los valores. |

### Method: get_as_node() {#get_as_node__2}


```
 get_as_node() 
```

Obtiene la característica como nodo. Esto puede ser útil para los datos personalizados

**Returns**

| Tipo | Descripción |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | El NodeLink a la característica |


### Method: get_value(attribute_name) {#get_value_attribute_name_3}


```
 get_value(attribute_name) 
```

Obtiene el valor de un atributo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Nombre del atributo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| object | Valor del atributo. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_4}


```
 get_value_or_default(attribute_name, default_value) 
```

Obtiene el valor de un atributo, o [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) si el valor no está establecido o <c>null</c>.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Nombre del atributo. |
| default_value | object | El valor a devolver si el valor del atributo falta. El valor predeterminado es <see langword=\"null\" />. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| object | Valor del atributo. |


### Method: get_values(values, default_value) {#get_values_values_default_value_5}


```
 get_values(values, default_value) 
```

Devuelve los valores de todos los atributos en una matriz.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valores | object | La matriz en la que copiar los valores de los atributos. |
| default_value | object | El valor a devolver si el valor del atributo falta (no establecido). El valor predeterminado es <see langword=\"null\" />.<br/>            Considere usar '.Value' para separar los valores 'no establecido' y '<see langword=\"null\" />'. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | Una cantidad de atributos copiados. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_6}


```
 get_values(values_count, default_value) 
```

Devuelve los valores de todos los atributos en una matriz.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| values_count | int | El recuento de valores. |
| default_value | object | El valor a devolver si el valor del atributo falta (no establecido). El valor predeterminado es <see langword=\"null\" />.<br/>            Considere usar '.Value' para separar los valores 'no establecido' y '<see langword=\"null\" />'. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| object | Una cantidad de atributos copiados. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_7}


```
 get_values_dump(default_value) 
```

Devuelve los valores de todos los atributos en una matriz.<br/>            Considere usar el método Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) para evitar asignaciones de memoria adicionales.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| default_value | object | El valor a devolver si el valor del atributo falta (no establecido). El valor predeterminado es <see langword=\"null\" />.<br/>            Considere usar '.Value' para separar los valores 'no establecido' y '<see langword=\"null\" />'. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| object | Una nueva matriz en la que copiar los valores de los atributos. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_8}


```
 get_values_list(attribute_name, separator, count) 
```

Obtiene los valores de una secuencia de atributos como una lista.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Nombre del atributo. |
| separator | string | Una cadena que se usa para separar el nombre del atributo y el valor de índice de la secuencia. |
| conteo | int | Cantidad de valores a devolver (los valores faltantes se rellenan como null) |

**Returns**

| Tipo | Descripción |
| :- | :- |
| object | Lista de valores de los atributos cuyos nombres difieren por el valor de índice de la secuencia. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_9}


```
 is_value_null(attribute_name) 
```

Determina si el atributo especificado ha sido establecido explícitamente al valor <c>null</c>.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Nombre del atributo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si el valor del atributo es <c>null</c>; de lo contrario, <see langword=\"false\" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_10}


```
 is_value_set(attribute_name) 
```

Comprueba si el valor del atributo está establecido en esta característica.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Nombre del atributo. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | <see langword=\"true\" /> si el valor para el atributo especificado está establecido; de lo contrario, <see langword=\"false\" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_11}


```
 set_value(attribute_name, value) 
```

Establece un nuevo valor de un atributo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | El nombre del atributo. |
| value | object | El valor del atributo. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_12}


```
 set_value_null(attribute_name) 
```

Establece el valor del atributo a <c>null</c>.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | El nombre del atributo. |

### Method: set_values(values) {#set_values_values_13}


```
 set_values(values) 
```

Establece nuevos valores para todos los atributos.<br/>            También considere usar el método [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) para simplificar la asignación de valores en una sola llamada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| valores | object | La matriz de nuevos valores. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El número de valores de atributo establecidos. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_14}


```
 unset_value(attribute_name) 
```

Elimina el valor del atributo de esta característica.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| attribute_name | string | Nombre del atributo. |

