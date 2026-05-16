---
title: "Projection क्लास"
type: docs
weight: 170
url: /hi/python-net/aspose.gis.spatialreferencing/projection/
---

**Summary:** Represents a projection method with parameters, that transforms (longitude, latitude) to (x, y).

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Projection

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| angular_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | कोणीय पैरामीटरों के लिए उपयोग की जाने वाली इकाई। |
| epsg_code | इंट | r | यदि इस वस्तु का पहचानकर्ता EPSG पहचानकर्ता है - तो उसका कोड लौटाएँ। अन्यथा -1 लौटाएँ। |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | इस पहचाने जाने योग्य वस्तु का पहचानकर्ता। |
| linear_parameters_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | रेखीय पैरामीटरों के लिए उपयोग की जाने वाली इकाई। |
| नाम | string | r | इस वस्तु का नाम। |
| parameters_names | System.Collections.Generic.IList<string> | r | इस प्रोजेक्शन को दिए गए पैरामीटरों के नामों का एक क्रमबद्ध संग्रह प्राप्त करता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [get_parameter_value(name, type)](#get_parameter_value_name_type_1) | इस प्रोजेक्शन के निर्दिष्ट नाम वाले पैरामीटर को प्राप्त करता है। |
| [is_equivalent(other)](#is_equivalent_other_2) | निर्धारित करता है कि दो प्रोजेक्शन समान हैं या नहीं। समान प्रोजेक्शन (longitude, latitude) को (x, y) में <br/>            उसी तरह मानचित्रित करते हैं। |
| [try_get_parameter_value(name, type)](#try_get_parameter_value_name_type_3) | इस प्रोजेक्शन के निर्दिष्ट नाम वाले पैरामीटर को प्राप्त करता है। यदि ऐसा कोई पैरामीटर नहीं है - <see langword="null" /> लौटाता है। |


### Method: get_parameter_value(name, type) {#get_parameter_value_name_type_1}


```
 get_parameter_value(name, type) 
```

इस प्रोजेक्शन के निर्दिष्ट नाम वाले पैरामीटर को प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | पैरामीटर का नाम। |
