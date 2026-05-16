---
title: "NumericFormat Klasse"
type: docs
weight: 2870
url: /nl/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Converteert en probeert te waarborgen dat een numerieke waarde die wordt geconverteerd naar<br/>            een tekenreeks, wordt teruggeparseerd naar dezelfde numerieke waarde. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Converteert een getal naar een vaste-komma tekst zonder wetenschappelijke notatie. |
| [general(precision)](#general_precision_2) | Converteert een getal naar de compactere van vaste-komma of wetenschappelijke notatie,<br/>            afhankelijk van het type getal en of er een precisiespecificatie aanwezig is. Aanbevolen om te gebruiken. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Converteert een getal naar een vaste-komma tekst zonder wetenschappelijke notatie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| significant_digits | int | Aantal significante cijfers. De maximale beschikbare precisie is "308" |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | De afrondingsprecisie-specificatie. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Converteert een getal naar de compactere van vaste-komma of wetenschappelijke notatie,<br/>            afhankelijk van het type getal en of er een precisiespecificatie aanwezig is. Aanbevolen om te gebruiken.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| precision | int | De precisie definieert het maximale aantal significante cijfers dat kan verschijnen in de resulterende tekenreeks.<br/>            Als de precisie nul is, wordt de waarde "15" gebruikt. De maximale beschikbare precisie is "17". |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | De algemene opmaak-specificatie. |


