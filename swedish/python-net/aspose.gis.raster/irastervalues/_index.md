---
title: "IRasterValues-klass"
type: docs
weight: 30
url: /sv/python-net/aspose.gis.raster/irastervalues/
---

**Summary:** Provides access to the values of raster bands.

**Module:** [aspose.gis.raster](/psd/python-net/aspose.gis.raster/)

**Full Name:** aspose.gis.raster.IRasterValues

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [as_boolean(band_index)](#as_boolean_band_index_1) | Konverterar den angivna banddata till ett <see langword=\"bool\" /> värde. |
| [as_byte(band_index)](#as_byte_band_index_2) | Konverterar den angivna banddata till ett <see langword=\"byte\" /> värde. |
| [as_double(band_index)](#as_double_band_index_3) | Konverterar den angivna banddata till ett <see langword=\"double\" /> värde. |
| [as_float(band_index)](#as_float_band_index_4) | Konverterar den angivna banddata till ett <see langword=\"float\" /> värde. |
| [as_integer(band_index)](#as_integer_band_index_5) | Konverterar den angivna banddata till ett <see langword=\"int\" /> värde. |
| [as_long(band_index)](#as_long_band_index_6) | Konverterar den angivna banddata till ett <see langword=\"long\" /> värde. |
| [as_short(band_index)](#as_short_band_index_7) | Konverterar den angivna banddata till ett <see langword=\"short\" /> värde. |
| [equals_no_data(band_index)](#equals_no_data_band_index_8) | Kontrollerar om värdet representerar bakgrund eller 'no data' i det angivna bandet. |
| [get_data_type(band_index)](#get_data_type_band_index_9) | Hämtar typ av värden. |
| [is_null(band_index)](#is_null_band_index_10) | Kontrollerar om rastervärdet är satt i det angivna bandet. |


### Method: as_boolean(band_index) {#as_boolean_band_index_1}


```
 as_boolean(band_index) 
```

Konverterar den angivna banddata till ett <see langword=\"bool\" /> värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Det konverterade värdet. |


### Method: as_byte(band_index) {#as_byte_band_index_2}


```
 as_byte(band_index) 
```

Konverterar den angivna banddata till ett <see langword=\"byte\" /> värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| byte | Det konverterade värdet. |


### Method: as_double(band_index) {#as_double_band_index_3}


```
 as_double(band_index) 
```

Konverterar den angivna banddata till ett <see langword=\"double\" /> värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| double | Det konverterade värdet. |


### Method: as_float(band_index) {#as_float_band_index_4}


```
 as_float(band_index) 
```

Konverterar den angivna banddata till ett <see langword=\"float\" /> värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| flyttal | Det konverterade värdet. |


### Method: as_integer(band_index) {#as_integer_band_index_5}


```
 as_integer(band_index) 
```

Konverterar den angivna banddata till ett <see langword=\"int\" /> värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| int | Det konverterade värdet. |


### Method: as_long(band_index) {#as_long_band_index_6}


```
 as_long(band_index) 
```

Konverterar den angivna banddata till ett <see langword=\"long\" /> värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| long | Det konverterade värdet. |


### Method: as_short(band_index) {#as_short_band_index_7}


```
 as_short(band_index) 
```

Konverterar den angivna banddata till ett <see langword=\"short\" /> värde.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| short | Det konverterade värdet. |


### Method: equals_no_data(band_index) {#equals_no_data_band_index_8}


```
 equals_no_data(band_index) 
```

Kontrollerar om värdet representerar bakgrund eller 'no data' i det angivna bandet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar 'true' om det representerar bakgrund eller 'no data'. |


### Method: get_data_type(band_index) {#get_data_type_band_index_9}


```
 get_data_type(band_index) 
```

Hämtar typ av värden.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [BandTypes](/psd/python-net/aspose.gis.raster/bandtypes) | Typen av värden. |


### Method: is_null(band_index) {#is_null_band_index_10}


```
 is_null(band_index) 
```

Kontrollerar om rastervärdet är satt i det angivna bandet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| band_index | int | Indexet för bandet. Numreringen börjar från 0. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| bool | Returnerar 'false' om det inte finns. |


