---
title: "NumericFormat-klass"
type: docs
weight: 2870
url: /sv/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Konverterar och försöker säkerställa att ett numeriskt värde som konverteras till<br/>            en sträng parsas tillbaka till samma numeriska värde. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Konverterar ett tal till en fastpunktstext utan vetenskaplig notation. |
| [general(precision)](#general_precision_2) | Konverterar ett tal till den mest kompakta av antingen fastpunkt- eller vetenskaplig notation,<br/>            beroende på typ av tal och om en precision specificerare finns. Rekommenderas att använda. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Konverterar ett tal till en fastpunktstext utan vetenskaplig notation.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| significant_digits | int | Antal signifikanta siffror. Den maximalt tillgängliga precisionen är "308" |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Rundningsprecisionens specifikator. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Konverterar ett tal till den mest kompakta av antingen fastpunkt- eller vetenskaplig notation,<br/>            beroende på typ av tal och om en precision specificerare finns. Rekommenderas att använda.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| precision | int | Precisionen definierar det maximala antalet signifikanta siffror som kan förekomma i resultatsträngen.<br/>            Om precisionen är noll används värdet "15". Den maximalt tillgängliga precisionen är "17". |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Den allmänna formatets specifikator. |


