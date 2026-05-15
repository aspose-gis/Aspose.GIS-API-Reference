---
title: "Classe IRasterValues"
type: docs
weight: 30
url: /fr/python-net/aspose.gis.raster/irastervalues/
---

**Summary:** Provides access to the values of raster bands.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.IRasterValues

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_boolean(band_index)](#as_boolean_band_index_1) | Convertit les données de bande spécifiées en une valeur <see langword="bool" />. |
| [as_byte(band_index)](#as_byte_band_index_2) | Convertit les données de bande spécifiées en une valeur <see langword="byte" />. |
| [as_double(band_index)](#as_double_band_index_3) | Convertit les données de bande spécifiées en une valeur <see langword="double" />. |
| [as_float(band_index)](#as_float_band_index_4) | Convertit les données de bande spécifiées en une valeur <see langword="float" />. |
| [as_integer(band_index)](#as_integer_band_index_5) | Convertit les données de bande spécifiées en une valeur <see langword="int" />. |
| [as_long(band_index)](#as_long_band_index_6) | Convertit les données de bande spécifiées en une valeur <see langword="long" />. |
| [as_short(band_index)](#as_short_band_index_7) | Convertit les données de bande spécifiées en une valeur <see langword="short" />. |
| [equals_no_data(band_index)](#equals_no_data_band_index_8) | Vérifie si la valeur représente le fond ou 'no data' dans la bande spécifiée. |
| [get_data_type(band_index)](#get_data_type_band_index_9) | Obtient le type des valeurs. |
| [is_null(band_index)](#is_null_band_index_10) | Vérifie si la valeur raster est définie dans la bande spécifiée. |


### Method: as_boolean(band_index) {#as_boolean_band_index_1}


```
 as_boolean(band_index) 
```

Convertit les données de bande spécifiées en une valeur <see langword="bool" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| bool | La valeur convertie. |


### Method: as_byte(band_index) {#as_byte_band_index_2}


```
 as_byte(band_index) 
```

Convertit les données de bande spécifiées en une valeur <see langword="byte" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| byte | La valeur convertie. |


### Method: as_double(band_index) {#as_double_band_index_3}


```
 as_double(band_index) 
```

Convertit les données de bande spécifiées en une valeur <see langword="double" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| double | La valeur convertie. |


### Method: as_float(band_index) {#as_float_band_index_4}


```
 as_float(band_index) 
```

Convertit les données de bande spécifiées en une valeur <see langword="float" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| float | La valeur convertie. |


### Method: as_integer(band_index) {#as_integer_band_index_5}


```
 as_integer(band_index) 
```

Convertit les données de bande spécifiées en une valeur <see langword="int" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| int | La valeur convertie. |


### Method: as_long(band_index) {#as_long_band_index_6}


```
 as_long(band_index) 
```

Convertit les données de bande spécifiées en une valeur <see langword="long" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| long | La valeur convertie. |


### Method: as_short(band_index) {#as_short_band_index_7}


```
 as_short(band_index) 
```

Convertit les données de bande spécifiées en une valeur <see langword="short" />.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| short | La valeur convertie. |


### Method: equals_no_data(band_index) {#equals_no_data_band_index_8}


```
 equals_no_data(band_index) 
```

Vérifie si la valeur représente le fond ou 'no data' dans la bande spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Renvoie 'true' si elle représente le fond ou 'no data'. |


### Method: get_data_type(band_index) {#get_data_type_band_index_9}


```
 get_data_type(band_index) 
```

Obtient le type des valeurs.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| [BandTypes](/psd/python-net/aspose.gis.raster/bandtypes) | Le type des valeurs. |


### Method: is_null(band_index) {#is_null_band_index_10}


```
 is_null(band_index) 
```

Vérifie si la valeur raster est définie dans la bande spécifiée.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| band_index | int | L'index de la bande. Le comptage commence à 0. |

**Returns**

| Type | Description |
| :- | :- |
| bool | Renvoie 'false' si elle n'existe pas. |


