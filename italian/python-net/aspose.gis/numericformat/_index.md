---
title: "Classe NumericFormat"
type: docs
weight: 2870
url: /it/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Converte e tenta di garantire che un valore numerico convertito in<br/>            una stringa venga analizzato nuovamente nello stesso valore numerico. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Converte un numero in un testo a virgola fissa senza notazione scientifica. |
| [general(precision)](#general_precision_2) | Converte un numero nella forma più compatta, sia a virgola fissa che in notazione scientifica,<br/>            a seconda del tipo di numero e se è presente uno specificatore di precisione. Consigliato da utilizzare. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Converte un numero in un testo a virgola fissa senza notazione scientifica.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| significant_digits | int | Numero di cifre significative. La precisione massima disponibile è "308" |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Specificatore di precisione di arrotondamento. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Converte un numero nella forma più compatta, sia a virgola fissa che in notazione scientifica,<br/>            a seconda del tipo di numero e se è presente uno specificatore di precisione. Consigliato da utilizzare.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| precision | int | La precisione definisce il numero massimo di cifre significative che possono apparire nella stringa risultato.<br/>            Se la precisione è zero, viene usato il valore "15". La precisione massima disponibile è "17". |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Specificatore di formato generale. |


