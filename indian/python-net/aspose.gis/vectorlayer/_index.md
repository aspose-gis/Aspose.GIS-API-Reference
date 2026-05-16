---
title: "VectorLayer क्लास"
type: docs
weight: 4060
url: /hi/python-net/aspose.gis/vectorlayer/
---

**Summary:** Represents a vector layer.<br/>            A vector layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.VectorLayer

**Inheritance:** FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | इस [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में फीचर्स के लिए कस्टम एट्रिब्यूट्स का संग्रह प्राप्त करता है। |
| गिनती | इंट | r | इस लेयर में फीचर्स की संख्या प्राप्त करता है। |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | उस [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) को प्राप्त करता है जिसने इस लेयर को इंस्टैंशिएट किया। |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | लेयर के लिए ज्यामिति का प्रकार प्राप्त करता है। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | इस फीचर अनुक्रम की स्थानिक संदर्भ प्रणाली प्राप्त करता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [add(feature)](#add_feature_1) | लेयर में एक नया फीचर जोड़ता है, यदि [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) द्वारा समर्थित हो। |
| [add(feature, style)](#add_feature_style_2) | लेयर में निर्दिष्ट शैली के साथ एक नया फीचर जोड़ता है, यदि [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) द्वारा समर्थित हो। |
| [as_in_memory()](#as_in_memory__3) | इन‑मेमोरी फ़ॉर्मेट के रूप में एक लेयर क्लोन बनाएं। |
| [construct_feature()](#construct_feature__4) | लेयर में नहीं जोड़ते हुए (परंतु) इस लेयर के गुणों के संग्रह से मेल खाने वाले गुणों के साथ एक नया फीचर बनाता है।<br/>            फीचर के डेटा सेट करने के बाद, फीचर को लेयर में जोड़ने के लिए [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) का उपयोग करें। |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | लेयर को किसी अलग फ़ॉर्मेट में परिवर्तित करें। |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | लेयर को किसी अलग फ़ॉर्मेट में परिवर्तित करें। |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | लेयर को किसी अलग फ़ॉर्मेट में परिवर्तित करें। |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | लेयर को किसी अलग फ़ॉर्मेट में परिवर्तित करें। |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | अन्य [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) के गुणों को इस में कॉपी करता है। |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | अन्य [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) के गुणों को इस में कॉपी करता है। |
| [create(path, driver)](#create_path_driver_11) | लेयर बनाता है और नए फीचर जोड़ने के लिए इसे खोलता है। |
| [create(path, driver)](#create_path_driver_12) | लेयर बनाता है और नए फीचर जोड़ने के लिए इसे खोलता है। |
| [create(path, driver, options)](#create_path_driver_options_13) | लेयर बनाता है और नए फीचर जोड़ने के लिए इसे खोलता है। |
| [create(path, driver, options)](#create_path_driver_options_14) | लेयर बनाता है और नए फीचर जोड़ने के लिए इसे खोलता है। |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [get_extent()](#get_extent__19) | इस लेयर का स्थानिक विस्तार प्राप्त करता है। |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | ज्यामिति द्वारा लेयर को वर्तमान लेयर के साथ प्रतिच्छेद करता है। |
| [join(layer, options)](#join_layer_options_21) | लेयर को वर्तमान लेयर के साथ जोड़ता है। |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | ज्यामिति द्वारा लेयर को वर्तमान लेयर के साथ जोड़ता है। |
| [nearest_to(point)](#nearest_to_point_23) | प्रदान किए गए बिंदु के सबसे निकट फीचर को प्राप्त करता है। |
| [nearest_to(x, y)](#nearest_to_x_y_24) | प्रदान किए गए निर्देशांक के सबसे निकट फीचर को प्राप्त करता है। |
| [open(path, driver)](#open_path_driver_25) | लेयर को पढ़ने के लिए खोलें। |
| [open(path, driver)](#open_path_driver_26) | लेयर को पढ़ने के लिए खोलें। |
| [open(path, driver, options)](#open_path_driver_options_27) | लेयर को पढ़ने के लिए खोलें। |
| [open(path, driver, options)](#open_path_driver_options_28) | लेयर को पढ़ने के लिए खोलें। |
| [remove_at(index)](#remove_at_index_29) | निर्दिष्ट अनुक्रमणिका पर [Feature](/psd/python-net/aspose.gis/feature/) को हटाएँ। |
| [replace_at(index, feature)](#replace_at_index_feature_30) | निर्दिष्ट अनुक्रमणिका पर [Feature](/psd/python-net/aspose.gis/feature/) को बदलें। |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | फीचर अनुक्रम को लेयर में सहेजता है। |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | फीचर अनुक्रम को लेयर में सहेजता है। |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | फीचर अनुक्रम को लेयर में सहेजता है। |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | फीचर अनुक्रम को लेयर में सहेजता है। |
| [split_to()](#split_to__35) | फीचर को ज्यामिति प्रकार के अनुसार विभाजित करता है। |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | फ़िल्टर मेथड जैसे Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) में गुण मान द्वारा फ़िल्टरिंग को तेज करने के लिए एट्रिब्यूट इंडेक्स लोड करता है।<br/>            यदि इंडेक्स मौजूद नहीं है तो पहले इसे बनाता है। इंडेक्स पुनर्निर्माण को मजबूर करने के लिए <paramref name="forceRebuild" /> का उपयोग करें। |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | फ़िल्टर मेथड जैसे Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) में गुण मान द्वारा फ़िल्टरिंग को तेज करने के लिए एट्रिब्यूट इंडेक्स लोड करता है।<br/>            यदि इंडेक्स मौजूद नहीं है तो पहले इसे बनाता है। इंडेक्स पुनर्निर्माण को मजबूर करने के लिए <paramref name="forceRebuild" /> का उपयोग करें। |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | फ़िल्टर मेथड जैसे Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) और Aspose.Gis.VectorLayer.NearestTo(float,float) में गुण मान द्वारा फ़िल्टरिंग को तेज करने के लिए स्पैशियल इंडेक्स लोड करता है।<br/>            यदि इंडेक्स मौजूद नहीं है तो पहले इसे बनाता है। इंडेक्स पुनर्निर्माण को मजबूर करने के लिए <paramref name="forceRebuild" /> का उपयोग करें। |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | फ़िल्टर मेथड जैसे Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) और Aspose.Gis.VectorLayer.NearestTo(float,float) में गुण मान द्वारा फ़िल्टरिंग को तेज करने के लिए स्पैशियल इंडेक्स लोड करता है।<br/>            यदि इंडेक्स मौजूद नहीं है तो पहले इसे बनाता है। इंडेक्स पुनर्निर्माण को मजबूर करने के लिए <paramref name="forceRebuild" /> का उपयोग करें। |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | प्रदान किए गए मान के बराबर गुण मान वाले फीचर चुनता है। |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | प्रदान किए गए मान से बड़े गुण मान वाले फीचर चुनता है। |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | प्रदान किए गए मान से बड़े या बराबर गुण मान वाले फीचर चुनता है। |
| [where_intersects(extent)](#where_intersects_extent_43) | विस्तार के आधार पर फीचर फ़िल्टर करता है। |
| [where_intersects(geometry)](#where_intersects_geometry_44) | प्रदान की गई ज्यामिति के आधार पर फीचर फ़िल्टर करता है। |
| [where_intersects(sequence)](#where_intersects_sequence_45) | अन्य फीचर अनुक्रम में सभी ज्यामितियों के संघ के आधार पर फीचर फ़िल्टर करता है। |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | ऐसे फीचर चुनता है जिनका गुण मान प्रदान किए गए मान के बराबर नहीं है। |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | ऐसे फीचर चुनता है जिनका गुण null के बराबर नहीं है। |
| [where_null(attribute_name)](#where_null_attribute_name_48) | ऐसे फीचर चुनता है जिनका गुण null के बराबर है। |
| [where_set(attribute_name)](#where_set_attribute_name_49) | ऐसे फीचर चुनता है जिनमें गुण सेट है। |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | ऐसे फीचर चुनता है जिनका गुण मान प्रदान किए गए मान से छोटा है। |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | ऐसे फीचर चुनता है जिनका गुण मान प्रदान किए गए मान से छोटा या बराबर है। |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | ऐसे फीचर चुनता है जहाँ निर्दिष्ट गुण सेट नहीं है। |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

लेयर में एक नया फीचर जोड़ता है, यदि [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) द्वारा समर्थित हो।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | जोड़ने के लिए फीचर। |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

लेयर में निर्दिष्ट शैली के साथ एक नया फीचर जोड़ता है, यदि [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) द्वारा समर्थित हो।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | जोड़ने के लिए फीचर। |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | फीचर शैली। अनुपलब्ध शैली को दर्शाने के लिए <see langword=\"null\" /> का उपयोग करें। |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

इन‑मेमोरी फ़ॉर्मेट के रूप में एक लेयर क्लोन बनाएं।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | इन‑मेमोरी लेयर। |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

लेयर में नहीं जोड़ते हुए (परंतु) इस लेयर के गुणों के संग्रह से मेल खाने वाले गुणों के साथ एक नया फीचर बनाता है।<br/>            फीचर के डेटा सेट करने के बाद, फीचर को लेयर में जोड़ने के लिए [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) का उपयोग करें।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | एक नया फीचर। |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

लेयर को किसी अलग फ़ॉर्मेट में परिवर्तित करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_path | string | लेयर का पथ जो परिवर्तित किया जाएगा। |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | स्रोत लेयर के लिए फॉर्मेट ड्राइवर। |
| destination_path | string | लेयर का पथ जो रूपांतरण के परिणामस्वरूप बनाया जाएगा। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | गंतव्य लेयर के लिए फॉर्मेट ड्राइवर। |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

लेयर को किसी अलग फ़ॉर्मेट में परिवर्तित करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | लेयर का पथ जो परिवर्तित किया जाएगा। |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | स्रोत लेयर के लिए फॉर्मेट ड्राइवर। |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | लेयर का पथ जो रूपांतरण के परिणामस्वरूप बनाया जाएगा। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | गंतव्य लेयर के लिए फॉर्मेट ड्राइवर। |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

लेयर को किसी अलग फ़ॉर्मेट में परिवर्तित करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_path | string | लेयर का पथ जो परिवर्तित किया जाएगा। |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | स्रोत लेयर के लिए फॉर्मेट ड्राइवर। |
| destination_path | string | लेयर का पथ जो रूपांतरण के परिणामस्वरूप बनाया जाएगा। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | गंतव्य लेयर के लिए फॉर्मेट ड्राइवर। |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | रूपांतरण प्रक्रिया के विकल्प। |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

लेयर को किसी अलग फ़ॉर्मेट में परिवर्तित करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | लेयर का पथ जो परिवर्तित किया जाएगा। |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | स्रोत लेयर के लिए फॉर्मेट ड्राइवर। |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | लेयर का पथ जो रूपांतरण के परिणामस्वरूप बनाया जाएगा। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | गंतव्य लेयर के लिए फॉर्मेट ड्राइवर। |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | रूपांतरण प्रक्रिया के विकल्प। |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

अन्य [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) के गुणों को इस में कॉपी करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | गुणों को कॉपी करने के लिए फीचर अनुक्रम। |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

अन्य [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) के गुणों को इस में कॉपी करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | गुणों को कॉपी करने के लिए फीचर अनुक्रम। |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | एक कस्टम [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) का उदाहरण जो गुणों को एक‑एक करके प्रोसेस करेगा। |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

लेयर बनाता है और नए फीचर जोड़ने के लिए इसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | केवल‑लेखन लेयर। |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

लेयर बनाता है और नए फीचर जोड़ने के लिए इसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | केवल‑लेखन लेयर। |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

लेयर बनाता है और नए फीचर जोड़ने के लिए इसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | केवल‑लेखन लेयर। |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

लेयर बनाता है और नए फीचर जोड़ने के लिए इसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | केवल‑लेखन लेयर। |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

इस लेयर का स्थानिक विस्तार प्राप्त करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | इस लेयर का स्थानिक विस्तार। |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

ज्यामिति द्वारा लेयर को वर्तमान लेयर के साथ प्रतिच्छेद करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक परत को प्रतिच्छेद करने हेतु। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | दो परतों के प्रतिच्छेद के परिणामस्वरूप एक नई परत। |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

लेयर को वर्तमान लेयर के साथ जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | जोड़ने के लिए एक परत। |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | जोड़ने के पैरामीटर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | दो परतों को जोड़ने के परिणामस्वरूप एक नई परत। |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

ज्यामिति द्वारा लेयर को वर्तमान लेयर के साथ जोड़ता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | जोड़ने के लिए एक परत। |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | जोड़ने के पैरामीटर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | दो परतों को जोड़ने के परिणामस्वरूप एक नई परत। |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

प्रदान किए गए बिंदु के सबसे निकट फीचर को प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | बिंदु। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | प्रदान किए गए बिंदु के सबसे निकटतम फीचर। |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

प्रदान किए गए निर्देशांक के सबसे निकट फीचर को प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| x | double | निर्देशांक का X। |
| y | double | निर्देशांक का Y। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | प्रदान किए गए निर्देशांक के सबसे निकटतम फीचर। |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

लेयर को पढ़ने के लिए खोलें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | केवल‑पढ़ने योग्य परत। |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

लेयर को पढ़ने के लिए खोलें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | केवल‑पढ़ने योग्य परत। |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

लेयर को पढ़ने के लिए खोलें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | केवल‑पढ़ने योग्य परत। |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

लेयर को पढ़ने के लिए खोलें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | केवल‑पढ़ने योग्य परत। |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

निर्दिष्ट अनुक्रमणिका पर [Feature](/psd/python-net/aspose.gis/feature/) को हटाएँ।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | फ़ीचर का सूचकांक। |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

निर्दिष्ट अनुक्रमणिका पर [Feature](/psd/python-net/aspose.gis/feature/) को बदलें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | फ़ीचर का सूचकांक। |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | सेट करने के लिए फ़ीचर। |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

फीचर अनुक्रम को लेयर में सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| destination_path | string | आउटपुट परत का पथ। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | आउटपुट परत के लिए फ़ॉर्मेट ड्राइवर। |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

फीचर अनुक्रम को लेयर में सहेजता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | आउटपुट परत का पथ। |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | आउटपुट परत के लिए फ़ॉर्मेट ड्राइवर। |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


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

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


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

### Method: split_to() {#split_to__35}


```
 split_to() 
```

फीचर को ज्यामिति प्रकार के अनुसार विभाजित करता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | एक ही प्रकार की ज्यामिति वाली परतें। |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

फ़िल्टर मेथड जैसे Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) में गुण मान द्वारा फ़िल्टरिंग को तेज करने के लिए एट्रिब्यूट इंडेक्स लोड करता है।<br/>            यदि इंडेक्स मौजूद नहीं है तो पहले इसे बनाता है। इंडेक्स पुनर्निर्माण को मजबूर करने के लिए <paramref name="forceRebuild" /> का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index_path | string | सूचकांक फ़ाइल का पथ। |
| attribute_name | string | जिस गुण पर सूचकांक बनाना है उसका नाम। |
| force_rebuild | bool | भले ही सूचकांक पहले से मौजूद हो, उसे पुनः बनाने की आवश्यकता है या नहीं। |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

फ़िल्टर मेथड जैसे Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) में गुण मान द्वारा फ़िल्टरिंग को तेज करने के लिए एट्रिब्यूट इंडेक्स लोड करता है।<br/>            यदि इंडेक्स मौजूद नहीं है तो पहले इसे बनाता है। इंडेक्स पुनर्निर्माण को मजबूर करने के लिए <paramref name="forceRebuild" /> का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | सूचकांक फ़ाइल का पथ। |
| attribute_name | string | जिस गुण पर सूचकांक बनाना है उसका नाम। |
| force_rebuild | bool | भले ही सूचकांक पहले से मौजूद हो, उसे पुनः बनाने की आवश्यकता है या नहीं। |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

फ़िल्टर मेथड जैसे Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) और Aspose.Gis.VectorLayer.NearestTo(float,float) में गुण मान द्वारा फ़िल्टरिंग को तेज करने के लिए स्पैशियल इंडेक्स लोड करता है।<br/>            यदि इंडेक्स मौजूद नहीं है तो पहले इसे बनाता है। इंडेक्स पुनर्निर्माण को मजबूर करने के लिए <paramref name="forceRebuild" /> का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index_path | string | सूचकांक फ़ाइल का पथ। |
| force_rebuild | bool | भले ही सूचकांक पहले से मौजूद हो, उसे पुनः बनाने की आवश्यकता है या नहीं। |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

फ़िल्टर मेथड जैसे Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) और Aspose.Gis.VectorLayer.NearestTo(float,float) में गुण मान द्वारा फ़िल्टरिंग को तेज करने के लिए स्पैशियल इंडेक्स लोड करता है।<br/>            यदि इंडेक्स मौजूद नहीं है तो पहले इसे बनाता है। इंडेक्स पुनर्निर्माण को मजबूर करने के लिए <paramref name="forceRebuild" /> का उपयोग करें।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | सूचकांक फ़ाइल का पथ। |
| force_rebuild | bool | भले ही सूचकांक पहले से मौजूद हो, उसे पुनः बनाने की आवश्यकता है या नहीं। |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


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


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


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


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


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


### Method: where_intersects(extent) {#where_intersects_extent_43}


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


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


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


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


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


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


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


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


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


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


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


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


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


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


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


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


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


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


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


