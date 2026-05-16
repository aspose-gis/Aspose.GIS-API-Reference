---
title: "Classe DynamicFeature"
type: docs
weight: 650
url: /it/python-net/aspose.gis/dynamicfeature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.DynamicFeature

**Inheritance:** Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Ottiene o imposta la geometria della feature.<br/>            Non può essere <see langword="null" />, usa [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) per indicare una geometria mancante. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Copia i valori degli attributi da un'altra feature. |
| [get_as_node()](#get_as_node__2) | Ottiene la funzionalità come nodo. Questo può essere utile per i dati personalizzati |
| [get_value(attribute_name)](#get_value_attribute_name_3) | Ottiene il valore di un attributo. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_4) | Ottiene il valore di un attributo, o [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) se il valore non è impostato o <c>null</c>. |
| [get_values(values, default_value)](#get_values_values_default_value_5) | Restituisce i valori di tutti gli attributi in un array. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_6) | Restituisce i valori di tutti gli attributi in un array. |
| [get_values_dump(default_value)](#get_values_dump_default_value_7) | Restituisce i valori di tutti gli attributi in un array.<br/>            Considera di utilizzare il metodo Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) per evitare ulteriori allocazioni di memoria. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_8) | Ottiene i valori di una sequenza di attributi come elenco. |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_9) | Determina se l'attributo specificato è stato impostato esplicitamente al valore <c>null</c>. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_10) | Verifica se il valore dell'attributo è impostato in questa feature. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_11) | Imposta un nuovo valore per un attributo. |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_12) | Imposta il valore dell'attributo a <c>null</c>. |
| [set_values(values)](#set_values_values_13) | Imposta nuovi valori per tutti gli attributi.<br/>            Considera anche di utilizzare il metodo [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) per semplificare l'impostazione dei valori in una sola chiamata. |
| [unset_value(attribute_name)](#unset_value_attribute_name_14) | Rimuove il valore dell'attributo da questa feature. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Copia i valori degli attributi da un'altra feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | La feature da cui copiare i valori. |

### Method: get_as_node() {#get_as_node__2}


```
 get_as_node() 
```

Ottiene la funzionalità come nodo. Questo può essere utile per i dati personalizzati

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Il NodeLink alla funzionalità |


### Method: get_value(attribute_name) {#get_value_attribute_name_3}


```
 get_value(attribute_name) 
```

Ottiene il valore di un attributo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Nome dell'attributo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| object | Valore dell'attributo. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_4}


```
 get_value_or_default(attribute_name, default_value) 
```

Ottiene il valore di un attributo, o [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) se il valore non è impostato o <c>null</c>.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Nome dell'attributo. |
| default_value | object | Il valore da restituire se il valore dell'attributo è mancante. Il valore predefinito è <see langword=\"null\" />. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| object | Valore dell'attributo. |


### Method: get_values(values, default_value) {#get_values_values_default_value_5}


```
 get_values(values, default_value) 
```

Restituisce i valori di tutti gli attributi in un array.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valori | object | L'array in cui copiare i valori degli attributi. |
| default_value | object | Il valore da restituire se il valore dell'attributo è mancante (non impostato). Il valore predefinito è <see langword=\"null\" />.<br/>            Considera di usare '.Value' per distinguere i valori 'non impostato' e '<see langword=\"null\" />'. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Un numero di attributi copiati. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_6}


```
 get_values(values_count, default_value) 
```

Restituisce i valori di tutti gli attributi in un array.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| values_count | int | Il conteggio dei valori. |
| default_value | object | Il valore da restituire se il valore dell'attributo è mancante (non impostato). Il valore predefinito è <see langword=\"null\" />.<br/>            Considera di usare '.Value' per distinguere i valori 'non impostato' e '<see langword=\"null\" />'. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| object | Un numero di attributi copiati. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_7}


```
 get_values_dump(default_value) 
```

Restituisce i valori di tutti gli attributi in un array.<br/>            Considera di utilizzare il metodo Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) per evitare ulteriori allocazioni di memoria.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| default_value | object | Il valore da restituire se il valore dell'attributo è mancante (non impostato). Il valore predefinito è <see langword=\"null\" />.<br/>            Considera di usare '.Value' per distinguere i valori 'non impostato' e '<see langword=\"null\" />'. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| object | Un nuovo array in cui copiare i valori degli attributi. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_8}


```
 get_values_list(attribute_name, separator, count) 
```

Ottiene i valori di una sequenza di attributi come elenco.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Nome dell'attributo. |
| separator | string | Una stringa utilizzata per separare il nome dell'attributo e il valore indice della sequenza. |
| conteggio | int | Conteggio dei valori da restituire (i valori mancanti vengono riempiti con null) |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| object | Elenco dei valori degli attributi i cui nomi differiscono per valore indice di sequenza. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_9}


```
 is_value_null(attribute_name) 
```

Determina se l'attributo specificato è stato impostato esplicitamente al valore <c>null</c>.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Nome dell'attributo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword=\"true\" /> se il valore dell'attributo è <c>null</c>; altrimenti, <see langword=\"false\" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_10}


```
 is_value_set(attribute_name) 
```

Verifica se il valore dell'attributo è impostato in questa feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Nome dell'attributo. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | <see langword=\"true\" /> se il valore per l'attributo specificato è impostato; altrimenti, <see langword=\"false\" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_11}


```
 set_value(attribute_name, value) 
```

Imposta un nuovo valore per un attributo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Il nome dell'attributo. |
| valore | object | Il valore dell'attributo. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_12}


```
 set_value_null(attribute_name) 
```

Imposta il valore dell'attributo a <c>null</c>.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Il nome dell'attributo. |

### Method: set_values(values) {#set_values_values_13}


```
 set_values(values) 
```

Imposta nuovi valori per tutti gli attributi.<br/>            Considera anche di utilizzare il metodo [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) per semplificare l'impostazione dei valori in una sola chiamata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| valori | object | L'array dei nuovi valori. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il numero di valori di attributo impostati. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_14}


```
 unset_value(attribute_name) 
```

Rimuove il valore dell'attributo da questa feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Nome dell'attributo. |

