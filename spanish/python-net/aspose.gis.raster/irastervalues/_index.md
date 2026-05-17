---
title: "Clase IRasterValues"
type: docs
weight: 30
url: /es/python-net/aspose.gis.raster/irastervalues/
---

**Summary:** Provides access to the values of raster bands.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.IRasterValues

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [as_boolean(band_index)](#as_boolean_band_index_1) | Convierte los datos de banda especificados a un valor <see langword="bool" />. |
| [as_byte(band_index)](#as_byte_band_index_2) | Convierte los datos de banda especificados a un valor <see langword="byte" />. |
| [as_double(band_index)](#as_double_band_index_3) | Convierte los datos de banda especificados a un valor <see langword="double" />. |
| [as_float(band_index)](#as_float_band_index_4) | Convierte los datos de banda especificados a un valor <see langword="float" />. |
| [as_integer(band_index)](#as_integer_band_index_5) | Convierte los datos de banda especificados a un valor <see langword="int" />. |
| [as_long(band_index)](#as_long_band_index_6) | Convierte los datos de banda especificados a un valor <see langword="long" />. |
| [as_short(band_index)](#as_short_band_index_7) | Convierte los datos de banda especificados a un valor <see langword="short" />. |
| [equals_no_data(band_index)](#equals_no_data_band_index_8) | Comprueba si el valor representa fondo o 'no data' en la banda especificada. |
| [get_data_type(band_index)](#get_data_type_band_index_9) | Obtiene el tipo de valores. |
| [is_null(band_index)](#is_null_band_index_10) | Comprueba si el valor raster está establecido en la banda especificada. |


### Method: as_boolean(band_index) {#as_boolean_band_index_1}


```
 as_boolean(band_index) 
```

Convierte los datos de banda especificados a un valor <see langword="bool" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | El valor convertido. |


### Method: as_byte(band_index) {#as_byte_band_index_2}


```
 as_byte(band_index) 
```

Convierte los datos de banda especificados a un valor <see langword="byte" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| byte | El valor convertido. |


### Method: as_double(band_index) {#as_double_band_index_3}


```
 as_double(band_index) 
```

Convierte los datos de banda especificados a un valor <see langword="double" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| double | El valor convertido. |


### Method: as_float(band_index) {#as_float_band_index_4}


```
 as_float(band_index) 
```

Convierte los datos de banda especificados a un valor <see langword="float" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| float | El valor convertido. |


### Method: as_integer(band_index) {#as_integer_band_index_5}


```
 as_integer(band_index) 
```

Convierte los datos de banda especificados a un valor <see langword="int" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| int | El valor convertido. |


### Method: as_long(band_index) {#as_long_band_index_6}


```
 as_long(band_index) 
```

Convierte los datos de banda especificados a un valor <see langword="long" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| long | El valor convertido. |


### Method: as_short(band_index) {#as_short_band_index_7}


```
 as_short(band_index) 
```

Convierte los datos de banda especificados a un valor <see langword="short" />.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| short | El valor convertido. |


### Method: equals_no_data(band_index) {#equals_no_data_band_index_8}


```
 equals_no_data(band_index) 
```

Comprueba si el valor representa fondo o 'no data' en la banda especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Devuelve 'true' si representa fondo o 'no data'. |


### Method: get_data_type(band_index) {#get_data_type_band_index_9}


```
 get_data_type(band_index) 
```

Obtiene el tipo de valores.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [BandTypes](/psd/python-net/aspose.gis.raster/bandtypes) | El tipo de valores. |


### Method: is_null(band_index) {#is_null_band_index_10}


```
 is_null(band_index) 
```

Comprueba si el valor raster está establecido en la banda especificada.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| band_index | int | El índice de la banda. La numeración comienza en 0. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| bool | Devuelve 'false' si no existe. |


