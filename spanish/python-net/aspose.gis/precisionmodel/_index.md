---
title: "Clase PrecisionModel"
type: docs
weight: 3200
url: /es/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Devuelve un modelo de precisión exacta.<br/>            Según el modelo de precisión exacta, todos los dígitos en un valor double son significativos. |
| is_exact | bool | r | Obtiene un valor que indica si este modelo de precisión es exacto. |
| is_rounding | bool | r | Obtiene un valor que indica si este modelo de precisión está redondeando. |
| significant_digits | int | r | Obtiene el número de dígitos significativos en un modelo de precisión si está redondeando. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Devuelve un modelo de precisión con redondeo.<br/>            Según el modelo de precisión con redondeo, solo un número limitado de dígitos es significativo. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Devuelve un modelo de precisión con redondeo.<br/>            Según el modelo de precisión con redondeo, solo un número limitado de dígitos es significativo.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| significant_digits | int | Número de dígitos significativos. |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Modelo de precisión con redondeo. |


