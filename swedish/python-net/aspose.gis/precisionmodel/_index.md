---
title: "PrecisionModel-klass"
type: docs
weight: 3200
url: /sv/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Returnerar en exakt precisionsmodell.<br/>            Enligt exakt precisionsmodell är alla siffror i ett dubbelvärde signifikanta. |
| is_exact | bool | r | Hämtar ett värde som indikerar om denna precisionsmodell är exakt. |
| is_rounding | bool | r | Hämtar ett värde som indikerar om denna precisionsmodell avrundar. |
| significant_digits | int | r | Hämtar antalet signifikanta siffror i en precisionsmodell om den avrundar. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Returnerar en avrundningsprecisionsmodell.<br/>            Enligt avrundningsprecisionsmodellen är endast ett begränsat antal siffror signifikanta. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Returnerar en avrundningsprecisionsmodell.<br/>            Enligt avrundningsprecisionsmodellen är endast ett begränsat antal siffror signifikanta.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| significant_digits | int | Antal signifikanta siffror. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Avrundningsprecisionsmodell. |


