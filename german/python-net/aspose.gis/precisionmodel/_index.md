---
title: "PrecisionModel Klasse"
type: docs
weight: 3200
url: /de/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Gibt ein exaktes Präzisionsmodell zurück.<br/>            Laut exaktem Präzisionsmodell sind alle Ziffern eines double‑Werts signifikant. |
| is_exact | bool | r | Ermittelt einen Wert, der angibt, ob dieses Präzisionsmodell exakt ist. |
| is_rounding | bool | r | Ermittelt einen Wert, der angibt, ob dieses Präzisionsmodell rundet. |
| significant_digits | int | r | Ermittelt die Anzahl signifikanter Stellen in einem Präzisionsmodell, wenn es rundet. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Gibt ein Rundungs‑Präzisionsmodell zurück.<br/>            Laut Rundungs‑Präzisionsmodell sind nur eine begrenzte Anzahl von Ziffern signifikant. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Gibt ein Rundungs‑Präzisionsmodell zurück.<br/>            Laut Rundungs‑Präzisionsmodell sind nur eine begrenzte Anzahl von Ziffern signifikant.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| significant_digits | int | Anzahl signifikanter Stellen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Rundungs‑Präzisionsmodell. |


