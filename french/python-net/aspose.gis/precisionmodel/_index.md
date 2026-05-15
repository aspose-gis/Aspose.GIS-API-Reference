---
title: "PrecisionModel Classe"
type: docs
weight: 3200
url: /fr/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Renvoie un modèle de précision exact.<br/>            Selon le modèle de précision exact, tous les chiffres d'une valeur double sont significatifs. |
| is_exact | bool | r | Obtient une valeur indiquant si ce modèle de précision est exact. |
| is_rounding | bool | r | Obtient une valeur indiquant si ce modèle de précision effectue un arrondi. |
| significant_digits | int | r | Obtient le nombre de chiffres significatifs dans un modèle de précision s'il effectue un arrondi. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Renvoie un modèle de précision avec arrondi.<br/>            Selon le modèle de précision avec arrondi, seul un nombre limité de chiffres est significatif. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Renvoie un modèle de précision avec arrondi.<br/>            Selon le modèle de précision avec arrondi, seul un nombre limité de chiffres est significatif.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| significant_digits | int | Nombre de chiffres significatifs. |

**Returns**

| Type | Description |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Modèle de précision avec arrondi. |


