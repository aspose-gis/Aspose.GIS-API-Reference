---
title: "IRasterValues Klasse"
type: docs
weight: 30
url: /nl/python-net/aspose.gis.raster/irastervalues/
---

**Summary:** Provides access to the values of raster bands.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.IRasterValues

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [as_boolean(band_index)](#as_boolean_band_index_1) | Converteert de opgegeven bandgegevens naar een <see langword="bool" /> waarde. |
| [as_byte(band_index)](#as_byte_band_index_2) | Converteert de opgegeven bandgegevens naar een <see langword="byte" /> waarde. |
| [as_double(band_index)](#as_double_band_index_3) | Converteert de opgegeven bandgegevens naar een <see langword="double" /> waarde. |
| [as_float(band_index)](#as_float_band_index_4) | Converteert de opgegeven bandgegevens naar een <see langword="float" /> waarde. |
| [as_integer(band_index)](#as_integer_band_index_5) | Converteert de opgegeven bandgegevens naar een <see langword="int" /> waarde. |
| [as_long(band_index)](#as_long_band_index_6) | Converteert de opgegeven bandgegevens naar een <see langword="long" /> waarde. |
| [as_short(band_index)](#as_short_band_index_7) | Converteert de opgegeven bandgegevens naar een <see langword="short" /> waarde. |
| [equals_no_data(band_index)](#equals_no_data_band_index_8) | Controleert of de waarde achtergrond of 'geen gegevens' vertegenwoordigt in de opgegeven band. |
| [get_data_type(band_index)](#get_data_type_band_index_9) | Haalt het type van waarden op. |
| [is_null(band_index)](#is_null_band_index_10) | Controleert of de rasterwaarde is ingesteld in de opgegeven band. |


### Method: as_boolean(band_index) {#as_boolean_band_index_1}


```
 as_boolean(band_index) 
```

Converteert de opgegeven bandgegevens naar een <see langword="bool" /> waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | De geconverteerde waarde. |


### Method: as_byte(band_index) {#as_byte_band_index_2}


```
 as_byte(band_index) 
```

Converteert de opgegeven bandgegevens naar een <see langword="byte" /> waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| byte | De geconverteerde waarde. |


### Method: as_double(band_index) {#as_double_band_index_3}


```
 as_double(band_index) 
```

Converteert de opgegeven bandgegevens naar een <see langword="double" /> waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| double | De geconverteerde waarde. |


### Method: as_float(band_index) {#as_float_band_index_4}


```
 as_float(band_index) 
```

Converteert de opgegeven bandgegevens naar een <see langword="float" /> waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| float | De geconverteerde waarde. |


### Method: as_integer(band_index) {#as_integer_band_index_5}


```
 as_integer(band_index) 
```

Converteert de opgegeven bandgegevens naar een <see langword="int" /> waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int | De geconverteerde waarde. |


### Method: as_long(band_index) {#as_long_band_index_6}


```
 as_long(band_index) 
```

Converteert de opgegeven bandgegevens naar een <see langword="long" /> waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| long | De geconverteerde waarde. |


### Method: as_short(band_index) {#as_short_band_index_7}


```
 as_short(band_index) 
```

Converteert de opgegeven bandgegevens naar een <see langword="short" /> waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| short | De geconverteerde waarde. |


### Method: equals_no_data(band_index) {#equals_no_data_band_index_8}


```
 equals_no_data(band_index) 
```

Controleert of de waarde achtergrond of 'geen gegevens' vertegenwoordigt in de opgegeven band.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Retourneert 'true' als het achtergrond of 'geen gegevens' vertegenwoordigt. |


### Method: get_data_type(band_index) {#get_data_type_band_index_9}


```
 get_data_type(band_index) 
```

Haalt het type van waarden op.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [BandTypes](/psd/python-net/aspose.gis.raster/bandtypes) | Het type van waarden. |


### Method: is_null(band_index) {#is_null_band_index_10}


```
 is_null(band_index) 
```

Controleert of de rasterwaarde is ingesteld in de opgegeven band.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| band_index | int | De index van de band. Nummering begint bij 0. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| bool | Retourneert 'false' als het niet bestaat. |


