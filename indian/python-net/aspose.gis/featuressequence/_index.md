---
title: "FeaturesSequence क्लास"
type: docs
weight: 870
url: /hi/python-net/aspose.gis/featuressequence/
---

**Summary:** [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence/) represents a set of vector features.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | इस [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में फीचर्स के लिए कस्टम एट्रिब्यूट्स का संग्रह प्राप्त करता है। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | इस फीचर अनुक्रम की स्थानिक संदर्भ प्रणाली प्राप्त करता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [get_extent()](#get_extent__1) | इस लेयर का स्थानिक विस्तार प्राप्त करता है। |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_2) | फीचर अनुक्रम को लेयर में सहेजता है। |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_3) | फीचर अनुक्रम को लेयर में सहेजता है। |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_4) | फीचर अनुक्रम को लेयर में सहेजता है। |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_5) | फीचर अनुक्रम को लेयर में सहेजता है। |
| [split_to()](#split_to__6) | फीचर को ज्यामिति प्रकार के अनुसार विभाजित करता है। |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_7) | प्रदान किए गए मान के बराबर गुण मान वाले फीचर चुनता है। |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_8) | प्रदान किए गए मान से बड़े गुण मान वाले फीचर चुनता है। |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_9) | प्रदान किए गए मान से बड़े या बराबर गुण मान वाले फीचर चुनता है। |
| [where_intersects(extent)](#where_intersects_extent_10) | विस्तार के आधार पर फीचर फ़िल्टर करता है। |
| [where_intersects(geometry)](#where_intersects_geometry_11) | प्रदान की गई ज्यामिति के आधार पर फीचर फ़िल्टर करता है। |
| [where_intersects(sequence)](#where_intersects_sequence_12) | अन्य फीचर अनुक्रम में सभी ज्यामितियों के संघ के आधार पर फीचर फ़िल्टर करता है। |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_13) | ऐसे फीचर चुनता है जिनका गुण मान प्रदान किए गए मान के बराबर नहीं है। |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_14) | ऐसे फीचर चुनता है जिनका गुण null के बराबर नहीं है। |
| [where_null(attribute_name)](#where_null_attribute_name_15) | ऐसे फीचर चुनता है जिनका गुण null के बराबर है। |
| [where_set(attribute_name)](#where_set_attribute_name_16) | ऐसे फीचर चुनता है जिनमें गुण सेट है। |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_17) | ऐसे फीचर चुनता है जिनका गुण मान प्रदान किए गए मान से छोटा है। |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_18) | ऐसे फीचर चुनता है जिनका गुण मान प्रदान किए गए मान से छोटा या बराबर है। |
| [where_unset(attribute_name)](#where_unset_attribute_name_19) | ऐसे फीचर चुनता है जहाँ निर्दिष्ट गुण सेट नहीं है। |


### Method: get_extent() {#get_extent__1}


```
 get_extent() 
```

इस लेयर का स्थानिक विस्तार प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | इस लेयर का स्थानिक विस्तार। |


### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_2}


```
 save_to(destination_path, destination_driver) 
```

फीचर अनुक्रम को लेयर में सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| destination_path | string | आउटपुट परत का पथ। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | आउटपुट परत के लिए फ़ॉर्मेट ड्राइवर। |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_3}


```
 save_to(destination_path, destination_driver) 
```

फीचर अनुक्रम को लेयर में सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | आउटपुट परत का पथ। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | आउटपुट परत के लिए फ़ॉर्मेट ड्राइवर। |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_4}


```
 save_to(destination_path, destination_driver, options) 
```

फीचर अनुक्रम को लेयर में सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| destination_path | string | आउटपुट परत का पथ। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | आउटपुट परत के लिए फ़ॉर्मेट ड्राइवर। |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | सहेजने की प्रक्रिया के विकल्प। |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_5}


```
 save_to(destination_path, destination_driver, options) 
```

फीचर अनुक्रम को लेयर में सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | आउटपुट परत का पथ। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | आउटपुट परत के लिए फ़ॉर्मेट ड्राइवर। |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | सहेजने की प्रक्रिया के विकल्प। |

### Method: split_to() {#split_to__6}


```
 split_to() 
```

फीचर को ज्यामिति प्रकार के अनुसार विभाजित करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | एक ही प्रकार की ज्यामिति वाली परतें। |


### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_7}


```
 where_equal(attribute_name, value) 
```

प्रदान किए गए मान के बराबर गुण मान वाले फीचर चुनता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |
| मान | object | तुलना करने के लिए मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | फ़ीचर जिनका गुण मान प्रदान किए गए मान के बराबर है। |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_8}


```
 where_greater(attribute_name, value) 
```

प्रदान किए गए मान से बड़े गुण मान वाले फीचर चुनता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |
| मान | object | तुलना करने के लिए मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | फ़ीचर जिनका गुण मान प्रदान किए गए मान से बड़ा है। |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_9}


```
 where_greater_or_equal(attribute_name, value) 
```

प्रदान किए गए मान से बड़े या बराबर गुण मान वाले फीचर चुनता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |
| मान | object | तुलना करने के लिए मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | फ़ीचर जिनका गुण मान प्रदान किए गए मान से बड़ा या बराबर है। |


### Method: where_intersects(extent) {#where_intersects_extent_10}


```
 where_intersects(extent) 
```

विस्तार के आधार पर फीचर फ़िल्टर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | फ़िल्टर सीमा। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | प्रदान की गई ज्यामिति के साथ प्रतिच्छेद करने वाली विशेषताएँ। |


### Method: where_intersects(geometry) {#where_intersects_geometry_11}


```
 where_intersects(geometry) 
```

प्रदान की गई ज्यामिति के आधार पर फीचर फ़िल्टर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | फ़िल्टर ज्यामिति। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | प्रदान की गई ज्यामिति के साथ प्रतिच्छेद करने वाली विशेषताएँ। |


### Method: where_intersects(sequence) {#where_intersects_sequence_12}


```
 where_intersects(sequence) 
```

अन्य फीचर अनुक्रम में सभी ज्यामितियों के संघ के आधार पर फीचर फ़िल्टर करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | अन्य विशेषताओं का अनुक्रम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | अन्य विशेषताओं के अनुक्रम में सभी ज्यामितियों के संघ के साथ प्रतिच्छेद करने वाली विशेषताएँ। |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_13}


```
 where_not_equal(attribute_name, value) 
```

ऐसे फीचर चुनता है जिनका गुण मान प्रदान किए गए मान के बराबर नहीं है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |
| मान | object | तुलना करने के लिए मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | प्रदान किए गए मान के बराबर नहीं होने वाले गुण मान वाली विशेषताएँ। |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_14}


```
 where_not_null(attribute_name) 
```

ऐसे फीचर चुनता है जिनका गुण null के बराबर नहीं है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | null के बराबर नहीं होने वाले गुण मान वाली विशेषताएँ। |


### Method: where_null(attribute_name) {#where_null_attribute_name_15}


```
 where_null(attribute_name) 
```

ऐसे फीचर चुनता है जिनका गुण null के बराबर है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | null के बराबर गुण मान वाली विशेषताएँ। |


### Method: where_set(attribute_name) {#where_set_attribute_name_16}


```
 where_set(attribute_name) 
```

ऐसे फीचर चुनता है जिनमें गुण सेट है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | सेट किए गए गुण मान वाली विशेषताएँ। |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_17}


```
 where_smaller(attribute_name, value) 
```

ऐसे फीचर चुनता है जिनका गुण मान प्रदान किए गए मान से छोटा है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |
| मान | object | तुलना करने के लिए मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | प्रदान किए गए मान से छोटा गुण मान वाली विशेषताएँ। |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_18}


```
 where_smaller_or_equal(attribute_name, value) 
```

ऐसे फीचर चुनता है जिनका गुण मान प्रदान किए गए मान से छोटा या बराबर है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |
| मान | object | तुलना करने के लिए मान। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | प्रदान किए गए मान से छोटा या बराबर गुण मान वाली विशेषताएँ। |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_19}


```
 where_unset(attribute_name) 
```

ऐसे फीचर चुनता है जहाँ निर्दिष्ट गुण सेट नहीं है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| attribute_name | string | फ़िल्टर करने के लिए गुण। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | सेट नहीं किए गए गुण मान वाली विशेषताएँ। |


