---
title: "NumericFormat Klasse"
type: docs
weight: 2870
url: /de/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Konvertiert und versucht sicherzustellen, dass ein numerischer Wert, der in eine<br/>            Zeichenkette konvertiert wird, wieder in denselben numerischen Wert geparst wird. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Konvertiert eine Zahl in einen Festkomma-Text ohne wissenschaftliche Notation. |
| [general(precision)](#general_precision_2) | Konvertiert eine Zahl in die kompaktere Darstellung, entweder Festkomma- oder wissenschaftliche Notation,<br/>            abhängig vom Typ der Zahl und davon, ob ein Präzisionsangabe vorhanden ist. Empfohlen zu verwenden. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Konvertiert eine Zahl in einen Festkomma-Text ohne wissenschaftliche Notation.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| significant_digits | int | Anzahl signifikanter Stellen. Die maximal verfügbare Präzision beträgt "308" |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Der Rundungspräzisions‑Spezifizierer. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Konvertiert eine Zahl in die kompaktere Darstellung, entweder Festkomma- oder wissenschaftliche Notation,<br/>            abhängig vom Typ der Zahl und davon, ob ein Präzisionsangabe vorhanden ist. Empfohlen zu verwenden.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| precision | int | Die Präzision definiert die maximale Anzahl signifikanter Stellen, die im Ergebnis‑String erscheinen können.<br/>            Wenn die Präzision null ist, wird der Wert "15" verwendet. Die maximal verfügbare Präzision beträgt "17". |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Der allgemeine Format‑Spezifizierer. |


