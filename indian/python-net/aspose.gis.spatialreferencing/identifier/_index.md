---
title: "Identifier क्लास"
type: docs
weight: 110
url: /hi/python-net/aspose.gis.spatialreferencing/identifier/
---

**Summary:** Represents an identifier - a reference to external description of an object.<br/>            If you create a SRS from WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponds to "AUTHORITY" keyword.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Identifier

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [Identifier(authority_name, authority_unique_identifier)](#Identifier_authority_name_authority_unique_identifier_1) | नया उदाहरण बनाएं। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| authority_name | string | r | एक प्राधिकरण का नाम, जिसने एक [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) प्रदान किया। |
| authority_unique_identifier | string | r | एक अनूठा तरीका जिससे एक वस्तु को [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) के भीतर दर्शाया जा सकता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [epsg(epsg_code)](#epsg_epsg_code_1) | एक नया Identifier बनाता है जो कोड <paramref name="epsgCode" /> के साथ EPSG पहचानकर्ता को दर्शाता है। |
| [get_epsg_code()](#get_epsg_code__2) | यदि यह वस्तु एक मान्य EPSG पहचानकर्ता को दर्शाती है (उदा. - प्राधिकरण नाम "EPSG" है और प्राधिकरण का अद्वितीय पहचानकर्ता पूर्णांक है) -<br/>            इसे लौटाएँ। अन्यथा - -1 लौटाएँ। |


### Constructor: Identifier(authority_name, authority_unique_identifier) {#Identifier_authority_name_authority_unique_identifier_1}


```
 Identifier(authority_name, authority_unique_identifier) 
```

नया उदाहरण बनाएं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| authority_name | string | [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |
| authority_unique_identifier | string | [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/). |

### Method: epsg(epsg_code)  [static] {#epsg_epsg_code_1}


```
 epsg(epsg_code) 
```

एक नया Identifier बनाता है जो कोड <paramref name="epsgCode" /> के साथ EPSG पहचानकर्ता को दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| epsg_code | इंट | Epsg कोड। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | नया पहचानकर्ता [Identifier.authority_name](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "EPSG" और [Identifier.authority_unique_identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) <paramref name=\"epsgCode\" /> के साथ।<br/> यदि <paramref name=\"epsgCode\" /> 0 से कम है - <see langword=\"null\" /> लौटाएँ; |


### Method: get_epsg_code() {#get_epsg_code__2}


```
 get_epsg_code() 
```

यदि यह वस्तु एक मान्य EPSG पहचानकर्ता को दर्शाती है (उदा. - प्राधिकरण नाम "EPSG" है और प्राधिकरण का अद्वितीय पहचानकर्ता पूर्णांक है) -<br/>            इसे लौटाएँ। अन्यथा - -1 लौटाएँ।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| इंट | इस वस्तु द्वारा दर्शाया गया EPSG पहचानकर्ता। यदि यह वस्तु EPSG पहचानकर्ता का प्रतिनिधित्व नहीं करती - -1 लौटाएँ। |


