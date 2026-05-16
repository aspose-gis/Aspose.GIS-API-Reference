---
title: "Classe PrecisionModel"
type: docs
weight: 3200
url: /it/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Restituisce un modello di precisione esatto.<br/>            Secondo il modello di precisione esatto, tutte le cifre di un valore double sono significative. |
| is_exact | bool | r | Ottiene un valore che indica se questo modello di precisione è esatto. |
| is_rounding | bool | r | Ottiene un valore che indica se questo modello di precisione è arrotondato. |
| significant_digits | int | r | Ottiene il numero di cifre significative in un modello di precisione se è arrotondato. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Restituisce un modello di precisione arrotondato.<br/>            Secondo il modello di precisione arrotondato, solo un numero limitato di cifre è significativo. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Restituisce un modello di precisione arrotondato.<br/>            Secondo il modello di precisione arrotondato, solo un numero limitato di cifre è significativo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| significant_digits | int | Numero di cifre significative. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Modello di precisione arrotondato. |


