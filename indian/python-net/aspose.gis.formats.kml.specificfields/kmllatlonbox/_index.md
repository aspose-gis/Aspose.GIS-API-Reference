---
title: "KmlLatLonBox क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.gis.formats.kml.specificfields/kmllatlonbox/
---

**Summary:** Specifies object from Kml 'LatLonBox' node

**Module:** [aspose.gis.formats.kml.specificfields](/psd/python-net/aspose.gis.formats.kml.specificfields/)

**Full Name:** aspose.gis.formats.kml.specificfields.KmlLatLonBox

**Inheritance:** XmlNodeLink

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| children | [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | r | बच्चों को प्राप्त करता है। |
| पूर्व | double | r/w | 'LatLonBox' नोड का पूर्व। |
| max_altitude | Nullable<double> | r/w | 'LatLonBox' नोड का MaxAltitude। |
| min_altitude | Nullable<double> | r/w | 'LatLonBox' नोड का MinAltitude। |
| name_without_prefix | string | r | प्रिफिक्स के बिना नाम प्राप्त करता है। |
| node_name | string | r/w | नाम को प्राप्त करता है या सेट करता है। |
| node_value | string | r/w | मान को प्राप्त करता है या सेट करता है। |
| उत्तर | double | r/w | 'LatLonBox' नोड का उत्तर। |
| उपसर्ग | string | r | उपसर्ग प्राप्त करता है। |
| रोटेशन | Nullable<double> | r/w | 'LatLonBox' नोड का Rotation। |
| दक्षिण | double | r/w | 'LatLonBox' नोड का दक्षिण। |
| पश्चिम | double | r/w | 'LatLonBox' नोड का पश्चिम। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add_child(child)](#add_child_child_1) | बच्चे को जोड़ता है। |
| [as_bool()](#as_bool__2) | मान को बूल में कास्ट करके लौटाता है |
| [as_double()](#as_double__3) | मान को डबल में कास्ट करके लौटाता है। |
| [as_int()](#as_int__4) | इंट में कास्ट किया गया मान लौटाता है। |
| [find_nodes_by_name(name)](#find_nodes_by_name_name_5) | नाम द्वारा XML नोड्स खोजता है। |
| [get_node_by_name(name)](#get_node_by_name_name_6) | नाम से नोड प्राप्त करता है। कृपया ध्यान दें, यह मेथड पहला पाया गया Node लौटाएगा।<br/>            स्तर कोई भी हो, यह पाया जाएगा |
| [get_node_content()](#get_node_content__7) | नोड की सामग्री प्राप्त करता है। |
| [get_nodes_by_name(names)](#get_nodes_by_name_names_8) | निर्दिष्ट नाम वाले सभी नोड्स प्राप्त करता है। <br/>            स्तर कोई भी हो, यह पाया जाएगा |


### Method: add_child(child) {#add_child_child_1}


```
 add_child(child) 
```

बच्चे को जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| child | [NodeLink](/psd/python-net/aspose.gis/nodelink) | संतान। |

### Method: as_bool() {#as_bool__2}


```
 as_bool() 
```

मान को बूल में कास्ट करके लौटाता है

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | नोड का बूल मान |


### Method: as_double() {#as_double__3}


```
 as_double() 
```

मान को डबल में कास्ट करके लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double | नोड का डबल मान |


### Method: as_int() {#as_int__4}


```
 as_int() 
```

इंट में कास्ट किया गया मान लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| इंट | नोड का इंट मान |


### Method: find_nodes_by_name(name) {#find_nodes_by_name_name_5}


```
 find_nodes_by_name(name) 
```

नाम द्वारा XML नोड्स खोजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | नोड का नाम |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | नाम द्वारा XML नोड्स की सरणी। |


### Method: get_node_by_name(name) {#get_node_by_name_name_6}


```
 get_node_by_name(name) 
```

नाम से नोड प्राप्त करता है। कृपया ध्यान दें, यह मेथड पहला पाया गया Node लौटाएगा।<br/>            स्तर कोई भी हो, यह पाया जाएगा

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | आपके द्वारा खोजे जाने वाले नोड का नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | NodeLink API के साथ पाया गया नोड |


### Method: get_node_content() {#get_node_content__7}


```
 get_node_content() 
```

नोड की सामग्री प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | नोड की सामग्री |


### Method: get_nodes_by_name(names) {#get_nodes_by_name_names_8}


```
 get_nodes_by_name(names) 
```

निर्दिष्ट नाम वाले सभी नोड्स प्राप्त करता है। <br/>            स्तर कोई भी हो, यह पाया जाएगा

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | नाम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [NodeLink[]](/psd/python-net/aspose.gis/nodelink) | पाए गए नोड्स की एरे। |


