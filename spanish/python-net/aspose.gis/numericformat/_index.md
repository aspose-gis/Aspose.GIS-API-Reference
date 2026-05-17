---
title: "Clase NumericFormat"
type: docs
weight: 2870
url: /es/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descripción** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Convierte e intenta asegurar que un valor numérico que se convierte a<br/>            una cadena se analice de nuevo al mismo valor numérico. |
## **Methods**
| **Name** | **Descripción** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Convierte un número a texto de punto fijo sin notación científica. |
| [general(precision)](#general_precision_2) | Convierte un número al formato más compacto, ya sea de punto fijo o notación científica,<br/>            dependiendo del tipo del número y de si hay un especificador de precisión presente. Se recomienda su uso. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Convierte un número a texto de punto fijo sin notación científica.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| significant_digits | int | Número de dígitos significativos. La precisión máxima disponible es "308" |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | El especificador de precisión de redondeo. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Convierte un número al formato más compacto, ya sea de punto fijo o notación científica,<br/>            dependiendo del tipo del número y de si hay un especificador de precisión presente. Se recomienda su uso.

**Parameters:**

| Parámetro | Tipo | Descripción |
| :- | :- | :- |
| precision | int | La precisión define el número máximo de dígitos significativos que pueden aparecer en la cadena de resultado.<br/>            Si la precisión es cero, se utiliza el valor "15". La precisión máxima disponible es "17". |

**Returns**

| Tipo | Descripción |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | El especificador de formato general. |


