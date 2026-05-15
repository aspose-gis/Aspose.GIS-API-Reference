---
title: "NumericFormat Classe"
type: docs
weight: 2870
url: /fr/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Convertit et tente de garantir qu'une valeur numérique convertie en<br/>            une chaîne soit à nouveau analysée en la même valeur numérique. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Convertit un nombre en texte à point fixe sans notation scientifique. |
| [general(precision)](#general_precision_2) | Convertit un nombre dans la forme la plus compacte, soit en notation à point fixe, soit en notation scientifique,<br/>            selon le type du nombre et la présence d'un spécificateur de précision. Recommandé à l'utilisation. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Convertit un nombre en texte à point fixe sans notation scientifique.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| significant_digits | int | Nombre de chiffres significatifs. La précision maximale disponible est "308" |

**Returns**

| Type | Description |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Le spécificateur de précision d'arrondi. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Convertit un nombre dans la forme la plus compacte, soit en notation à point fixe, soit en notation scientifique,<br/>            selon le type du nombre et la présence d'un spécificateur de précision. Recommandé à l'utilisation.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| precision | int | La précision définit le nombre maximal de chiffres significatifs pouvant apparaître dans la chaîne de résultat.<br/>            Si la précision est zéro, la valeur "15" est utilisée. La précision maximale disponible est "17". |

**Returns**

| Type | Description |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Le spécificateur de format général. |


