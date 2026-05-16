---
title: "PrecisionModel Class"
type: docs
weight: 3200
url: /nl/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Retourneert een exact precisiemodel.<br/>            Volgens het exacte precisiemodel zijn alle cijfers in een double-waarde significant. |
| is_exact | bool | r | Haalt een waarde op die aangeeft of dit precisiemodel exact is. |
| is_rounding | bool | r | Haalt een waarde op die aangeeft of dit precisiemodel afrondt. |
| significant_digits | int | r | Haalt het aantal significante cijfers op in een precisiemodel wanneer het afrondt. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Retourneert een afrondingsprecisiemodel.<br/>            Volgens het afrondingsprecisiemodel zijn slechts een beperkt aantal cijfers significant. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Retourneert een afrondingsprecisiemodel.<br/>            Volgens het afrondingsprecisiemodel zijn slechts een beperkt aantal cijfers significant.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| significant_digits | int | Aantal significante cijfers. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Afrondingsprecisiemodel. |


