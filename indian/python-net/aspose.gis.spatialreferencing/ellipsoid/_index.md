---
title: "एलिप्सॉइड वर्ग"
type: docs
weight: 40
url: /hi/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | नया एलिप्सॉइड बनाता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Airy एलिप्सॉइड। |
| epsg_code | इंट | r | यदि इस वस्तु का पहचानकर्ता EPSG पहचानकर्ता है - तो उसका कोड लौटाएँ। अन्यथा -1 लौटाएँ। |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | GRS 1980 एलिप्सॉइड। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | इस पहचाने जाने योग्य वस्तु का पहचानकर्ता। |
| inverse_flattening | double | r | एलिप्सॉइड का इनवर्स फ्लैटनिंग। यदि यह एक गोला है तो 0। |
| is_sphere | bool | r | पता लगाता है कि यह एलिप्सॉइड एक गोला है या नहीं। |
| is_valid | bool | r | पता लगाता है कि एलिप्सॉइड वैध है या नहीं: इसका अर्ध-प्रमुख अक्ष 0 से अधिक होना चाहिए और इनवर्स फ्लैटनिंग सकारात्मक या 0 के बराबर होना चाहिए। |
| नाम | string | r | इस वस्तु का नाम। |
| semi_major_axis | double | r | एलिप्सॉइड का अर्ध-प्रमुख अक्ष। |
| semi_minor_axis | double | r | एलिप्सॉइड का अर्ध-लघु अक्ष। यदि यह एक गोला है तो यह अर्ध-प्रमुख अक्ष के बराबर होता है। |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 72 एलिप्सॉइड। |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 84 एलिप्सॉइड। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | निर्धारित करता है कि दो एलिप्सॉइड समान हैं या नहीं.<br/>            यदि एलिप्सॉइड A, एलिप्सॉइड B के बराबर है, तो उनके पास समान अर्ध-प्रमुख अक्ष और इनवर्स फ्लैटनिंग होता है। |
| [is_equivalent(other)](#is_equivalent_other_2) | निर्धारित करता है कि दो एलिप्सॉइड समान हैं या नहीं.<br/>            यदि एलिप्सॉइड A, एलिप्सॉइड B के बराबर है, तो उनके पास समान अर्ध-प्रमुख अक्ष और इनवर्स फ्लैटनिंग होता है। |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

नया एलिप्सॉइड बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | एलिप्सॉइड का नाम। |
| semi_major_axis | double | एलिप्सॉइड का अर्ध-प्रमुख अक्ष। |
| inverse_flattening | double | एलिप्सॉइड का इनवर्स फ्लैटनिंग। स्फ़ेरॉइड बनाने के लिए यह 0 होना चाहिए। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | एलिप्सॉइड की पहचानकर्ता। |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

निर्धारित करता है कि दो एलिप्सॉइड समान हैं या नहीं.<br/>            यदि एलिप्सॉइड A, एलिप्सॉइड B के बराबर है, तो उनके पास समान अर्ध-प्रमुख अक्ष और इनवर्स फ्लैटनिंग होता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | पहला एलिप्सॉइड। |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | दूसरा एलिप्सॉइड। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | बूल मान, जो दर्शाता है कि दो एलिप्सॉइड समान हैं या नहीं। |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

निर्धारित करता है कि दो एलिप्सॉइड समान हैं या नहीं.<br/>            यदि एलिप्सॉइड A, एलिप्सॉइड B के बराबर है, तो उनके पास समान अर्ध-प्रमुख अक्ष और इनवर्स फ्लैटनिंग होता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | अन्य एलिप्सॉइड। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | बूल मान, जो दर्शाता है कि दो एलिप्सॉइड समान हैं या नहीं। |


