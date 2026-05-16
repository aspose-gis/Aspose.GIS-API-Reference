---
title: "ProjectedSpatialReferenceSystemParameters क्लास"
type: docs
weight: 160
url: /hi/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/
---

**Summary:** Parameters to create projected SRS. Some of parameters have defaults.<br/>            Some parameters have reasonable defaults, so you don't have to assign only them.<br/>            If you assign <see langword="null" /> to those parameters, a default value will be used.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) and [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) don't have defaults -<br/>            you have to assign some non <see langword="null" /> value to this properties.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.ProjectedSpatialReferenceSystemParameters

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [ProjectedSpatialReferenceSystemParameters()](#ProjectedSpatialReferenceSystemParameters__1) | नया इंस्टेंस बनाता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| axises_order | [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder) | r/w | अक्षों का क्रम। डिफ़ॉल्ट रूप से [ProjectedAxisesOrder.XY](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) होता है। |
| base | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r/w | बेस जियोग्राफिक SRS (SRS जिस पर प्रोजेक्शन लागू किया जाता है)।<br/>            आपको इस प्रॉपर्टी को <see langword="null" /> नहीं मान सेट करना अनिवार्य है ताकि वैध SRS बनाया जा सके,<br/>            इस प्रॉपर्टी का कोई डिफ़ॉल्ट मान नहीं है। |
| linear_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r/w | इस SRS में उपयोग की जाने वाली इकाइयाँ। डिफ़ॉल्ट [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) है। |
| नाम | string | r/w | प्रोजेक्टेड SRS का नाम। डिफ़ॉल्ट "Unnamed" है। |
| projection_method_identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r/w | प्रोजेक्शन विधि का पहचानकर्ता। कोई डिफ़ॉल्ट मान नहीं है, आप इस पैरामीटर को <see langword="null" /> नहीं मान पर सेट कर सकते हैं,<br/>            यदि आप प्रोजेक्शन से पहचानकर्ता संलग्न करना चाहते हैं। यदि आप ऐसा करते हैं - यह आपका दायित्व है कि पहचानकर्ता लगातार प्रोजेक्शन विधि में संगत रहे<br/>            नाम (प्रोजेक्शन विधि का नाम इस प्रॉपर्टी को सेट करने पर नहीं बदलेगा)। |
| projection_method_name | string | r/w | प्रोजेक्शन विधि का नाम। कोई डिफ़ॉल्ट नहीं है और आपको इस पैरामीटर को <see langword=\"null\" /> मान नहीं रखने के लिए सेट करना अनिवार्य है, क्योंकि<br/>            बिना प्रोजेक्शन नाम के प्रोजेक्टेड SRS बेकार है। |
| x_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | X (क्षैतिज) आयाम का वर्णन करने वाली धुरी। डिफ़ॉल्ट रूप से पूर्व दिशा वाली धुरी। |
| y_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | r/w | Y (ऊर्ध्वाधर) आयाम का वर्णन करने वाली धुरी। डिफ़ॉल्ट रूप से उत्तर दिशा वाली धुरी। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add_projection_parameter(parameter_name, value)](#add_projection_parameter_parameter_name_value_1) | इस SRS में प्रोजेक्शन पैरामीटर जोड़ता है। यदि इस नाम का पैरामीटर पहले ही जोड़ा गया है - तो इसे अपडेट करें। |
| [get_projection_parameter(parameter_name)](#get_projection_parameter_parameter_name_2) | निर्दिष्ट नाम वाले प्रोजेक्शन पैरामीटर को प्राप्त करता है। |


### Constructor: ProjectedSpatialReferenceSystemParameters() {#ProjectedSpatialReferenceSystemParameters__1}


```
 ProjectedSpatialReferenceSystemParameters() 
```

नया इंस्टेंस बनाता है।

### Method: add_projection_parameter(parameter_name, value) {#add_projection_parameter_parameter_name_value_1}


```
 add_projection_parameter(parameter_name, value) 
```

इस SRS में प्रोजेक्शन पैरामीटर जोड़ता है। यदि इस नाम का पैरामीटर पहले ही जोड़ा गया है - तो इसे अपडेट करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| parameter_name | string | प्रोजेक्शन पैरामीटर का नाम। |
| value | double | पैरामीटर का मान। मान की इकाई [ProjectedSpatialReferenceSystemParameters.linear_unit](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) में होनी चाहिए<br/>            या [GeographicSpatialReferenceSystem.angular_unit](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) की, जो [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) का है। |

### Method: get_projection_parameter(parameter_name) {#get_projection_parameter_parameter_name_2}


```
 get_projection_parameter(parameter_name) 
```

निर्दिष्ट नाम वाले प्रोजेक्शन पैरामीटर को प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| parameter_name | string | पैरामीटर का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double | प्रोजेक्शन पैरामीटर का मान। |


