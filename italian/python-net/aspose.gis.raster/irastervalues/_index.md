---
title: "Classe IRasterValues"
type: docs
weight: 30
url: /it/python-net/aspose.gis.raster/irastervalues/
---

**Summary:** Provides access to the values of raster bands.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.IRasterValues

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [as_boolean(band_index)](#as_boolean_band_index_1) | Converte i dati della banda specificata in un valore <see langword="bool" />. |
| [as_byte(band_index)](#as_byte_band_index_2) | Converte i dati della banda specificata in un valore <see langword="byte" />. |
| [as_double(band_index)](#as_double_band_index_3) | Converte i dati della banda specificata in un valore <see langword="double" />. |
| [as_float(band_index)](#as_float_band_index_4) | Converte i dati della banda specificata in un valore <see langword="float" />. |
| [as_integer(band_index)](#as_integer_band_index_5) | Converte i dati della banda specificata in un valore <see langword="int" />. |
| [as_long(band_index)](#as_long_band_index_6) | Converte i dati della banda specificata in un valore <see langword="long" />. |
| [as_short(band_index)](#as_short_band_index_7) | Converte i dati della banda specificata in un valore <see langword="short" />. |
| [equals_no_data(band_index)](#equals_no_data_band_index_8) | Verifica se il valore rappresenta lo sfondo o 'no data' nella banda specificata. |
| [get_data_type(band_index)](#get_data_type_band_index_9) | Ottiene il tipo dei valori. |
| [is_null(band_index)](#is_null_band_index_10) | Verifica se il valore raster è impostato nella banda specificata. |


### Method: as_boolean(band_index) {#as_boolean_band_index_1}


```
 as_boolean(band_index) 
```

Converte i dati della banda specificata in un valore <see langword="bool" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Il valore convertito. |


### Method: as_byte(band_index) {#as_byte_band_index_2}


```
 as_byte(band_index) 
```

Converte i dati della banda specificata in un valore <see langword="byte" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| byte | Il valore convertito. |


### Method: as_double(band_index) {#as_double_band_index_3}


```
 as_double(band_index) 
```

Converte i dati della banda specificata in un valore <see langword="double" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| double | Il valore convertito. |


### Method: as_float(band_index) {#as_float_band_index_4}


```
 as_float(band_index) 
```

Converte i dati della banda specificata in un valore <see langword="float" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| float | Il valore convertito. |


### Method: as_integer(band_index) {#as_integer_band_index_5}


```
 as_integer(band_index) 
```

Converte i dati della banda specificata in un valore <see langword="int" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| int | Il valore convertito. |


### Method: as_long(band_index) {#as_long_band_index_6}


```
 as_long(band_index) 
```

Converte i dati della banda specificata in un valore <see langword="long" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| long | Il valore convertito. |


### Method: as_short(band_index) {#as_short_band_index_7}


```
 as_short(band_index) 
```

Converte i dati della banda specificata in un valore <see langword="short" />.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| short | Il valore convertito. |


### Method: equals_no_data(band_index) {#equals_no_data_band_index_8}


```
 equals_no_data(band_index) 
```

Verifica se il valore rappresenta lo sfondo o 'no data' nella banda specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Restituisce 'true' se rappresenta lo sfondo o 'no data'. |


### Method: get_data_type(band_index) {#get_data_type_band_index_9}


```
 get_data_type(band_index) 
```

Ottiene il tipo dei valori.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [BandTypes](/psd/python-net/aspose.gis.raster/bandtypes) | Il tipo dei valori. |


### Method: is_null(band_index) {#is_null_band_index_10}


```
 is_null(band_index) 
```

Verifica se il valore raster è impostato nella banda specificata.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| band_index | int | L'indice della banda. La numerazione inizia da 0. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| bool | Restituisce 'false' se non esiste. |


