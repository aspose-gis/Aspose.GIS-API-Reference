---
title: "GeoPackageDataset क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.gis.formats.geopackage/geopackagedataset/
---

**Summary:** Represents a collection of feature layers and tile layers in GeoPackage format.

**Module:** [aspose.gis.formats.geopackage](/psd/python-net/aspose.gis.formats.geopackage/)

**Full Name:** aspose.gis.formats.geopackage.GeoPackageDataset

**Inheritance:** Dataset

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [GeoPackageDataset(path, options)](#GeoPackageDataset_path_options_1) | नया इंस्टेंस बनाता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| can_create_layers | bool | r | यह मान प्राप्त करता है जो दर्शाता है कि यह डेटासेट वेक्टर लेयर बना सकता है या नहीं। |
| can_remove_layers | bool | r | यह मान प्राप्त करता है जो दर्शाता है कि यह डेटासेट वेक्टर लेयर को हटा सकता है या नहीं। |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | इस डेटासेट को इंस्टैंशिएट करने वाले [GeoPackageDataset.driver](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) को प्राप्त करता है। |
| layers_count | इंट | r | इस डेटासेट में लेयरों की संख्या प्राप्त करता है। |
| tile_layers_count | इंट | r | इस डेटासेट में टाइल लेयर्स की संख्या प्राप्त करता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [create(path, driver)](#create_path_driver_1) | एक dataset बनाता है। |
| [create(path, driver)](#create_path_driver_2) | एक dataset बनाता है। |
| [create(path, driver, options)](#create_path_driver_options_3) | एक dataset बनाता है। |
| [create(path, driver, options)](#create_path_driver_options_4) | एक dataset बनाता है। |
| [create_layer()](#create_layer__5) | एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create_layer(name, options, spatial_reference_system)](#create_layer_name_options_spatial_reference_system_6) | निर्दिष्ट नाम के साथ एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create_layer(name, spatial_reference_system)](#create_layer_name_spatial_reference_system_7) | निर्दिष्ट नाम के साथ एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create_layer(options, spatial_reference_system)](#create_layer_options_spatial_reference_system_8) | एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create_layer(spatial_reference_system)](#create_layer_spatial_reference_system_9) | एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [edit_layer(name, options, spatial_reference_system)](#edit_layer_name_options_spatial_reference_system_10) | यह मेथड अभी भी विकासाधीन है। |
| [edit_layer_at(index, options, spatial_reference_system)](#edit_layer_at_index_options_spatial_reference_system_11) | यह मेथड अभी भी विकासाधीन है। |
| [get_layer_name(index)](#get_layer_name_index_12) | निर्दिष्ट सूचकांक पर लेयर का नाम प्राप्त करता है। |
| [get_tile_layer_name(index)](#get_tile_layer_name_index_13) | निर्दिष्ट इंडेक्स पर टाइल लेयर का नाम प्राप्त करता है। |
| [has_layer_with_name(name)](#has_layer_with_name_name_14) | जाँचें कि वर्तमान डेटासेट में विशिष्ट नाम वाला लेयर है या नहीं |
| [open(path, driver)](#open_path_driver_15) | डेटासेट खोलता है। |
| [open(path, driver)](#open_path_driver_16) | डेटासेट खोलता है। |
| [open(path, driver, options)](#open_path_driver_options_17) | डेटासेट खोलता है। |
| [open(path, driver, options)](#open_path_driver_options_18) | डेटासेट खोलता है। |
| [open(path, options)](#open_path_options_19) | gpkg फ़ाइल से डेटासेट बनाने के लिए फ़ैक्टरी मेथड। |
| [open_layer(name, options)](#open_layer_name_options_20) | निर्दिष्ट नाम वाले लेयर को पढ़ने के लिए खोलता है। |
| [open_layer_at(index, options)](#open_layer_at_index_options_21) | निर्दिष्ट सूचकांक पर लेयर को पढ़ने के लिए खोलता है। |
| [open_layer_at(index, options)](#open_layer_at_index_options_22) | निर्दिष्ट सूचकांक पर लेयर को पढ़ने के लिए खोलता है। |
| [open_tile_layer(name, options)](#open_tile_layer_name_options_23) | निर्दिष्ट नाम के साथ टाइल लेयर को पढ़ने के लिए खोलता है। |
| [open_tile_layer_at(index, options)](#open_tile_layer_at_index_options_24) | निर्दिष्ट इंडेक्स पर टाइल लेयर को पढ़ने के लिए खोलता है। |
| [remove_layer(name)](#remove_layer_name_25) | निर्दिष्ट नाम वाले वेक्टर लेयर को हटाता है। |
| [remove_layer_at(index)](#remove_layer_at_index_26) | निर्दिष्ट सूचकांक पर वेक्टर लेयर को हटाता है। |
| [rename_layer(current_name, new_name)](#rename_layer_current_name_new_name_27) | डेटासेट में लेयर का नाम बदलें |


### Constructor: GeoPackageDataset(path, options) {#GeoPackageDataset_path_options_1}


```
 GeoPackageDataset(path, options) 
```

नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | gpkg फ़ाइल का पाथ। |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | gpkg फ़ाइल को पढ़ने की विशेषताओं से संबंधित सेटिंग्स। |

### Method: create(path, driver)  [static] {#create_path_driver_1}


```
 create(path, driver) 
```

एक dataset बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | डेटासेट का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: create(path, driver)  [static] {#create_path_driver_2}


```
 create(path, driver) 
```

एक dataset बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | डेटासेट का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_3}


```
 create(path, driver, options) 
```

एक dataset बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | डेटासेट का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_4}


```
 create(path, driver, options) 
```

एक dataset बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | डेटासेट का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: create_layer() {#create_layer__5}


```
 create_layer() 
```

एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) लिखने के लिए खोला गया। |


### Method: create_layer(name, options, spatial_reference_system) {#create_layer_name_options_spatial_reference_system_6}


```
 create_layer(name, options, spatial_reference_system) 
```

निर्दिष्ट नाम के साथ एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | लेयर का नाम। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | खोलने के विकल्प। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | नए लेयर का स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) लिखने के लिए खोला गया। |


### Method: create_layer(name, spatial_reference_system) {#create_layer_name_spatial_reference_system_7}


```
 create_layer(name, spatial_reference_system) 
```

निर्दिष्ट नाम के साथ एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | लेयर का नाम। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | नए लेयर का स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) लिखने के लिए खोला गया। |


### Method: create_layer(options, spatial_reference_system) {#create_layer_options_spatial_reference_system_8}


```
 create_layer(options, spatial_reference_system) 
```

एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | खोलने के विकल्प। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | नए लेयर का स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) लिखने के लिए खोला गया। |


### Method: create_layer(spatial_reference_system) {#create_layer_spatial_reference_system_9}


```
 create_layer(spatial_reference_system) 
```

एक नया वेक्टर लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | नए लेयर का स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) लिखने के लिए खोला गया। |


### Method: edit_layer(name, options, spatial_reference_system) {#edit_layer_name_options_spatial_reference_system_10}


```
 edit_layer(name, options, spatial_reference_system) 
```

यह मेथड अभी भी विकासाधीन है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | संपादन के लिए लेयर का नाम। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | खोलने के विकल्प। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | नए ज्यामितियों के लिए स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: edit_layer_at(index, options, spatial_reference_system) {#edit_layer_at_index_options_spatial_reference_system_11}


```
 edit_layer_at(index, options, spatial_reference_system) 
```

यह मेथड अभी भी विकासाधीन है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | संपादन के लिए लेयर का सूचकांक। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | खोलने के विकल्प। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | नए ज्यामितियों के लिए स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) |


### Method: get_layer_name(index) {#get_layer_name_index_12}


```
 get_layer_name(index) 
```

निर्दिष्ट सूचकांक पर लेयर का नाम प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | लेयर का सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | लेयर का नाम। |


### Method: get_tile_layer_name(index) {#get_tile_layer_name_index_13}


```
 get_tile_layer_name(index) 
```

निर्दिष्ट इंडेक्स पर टाइल लेयर का नाम प्राप्त करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | लेयर का सूचकांक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | लेयर का नाम। |


### Method: has_layer_with_name(name) {#has_layer_with_name_name_14}


```
 has_layer_with_name(name) 
```

जाँचें कि वर्तमान डेटासेट में विशिष्ट नाम वाला लेयर है या नहीं

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | लेयर का नाम |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | <see langword="true" />, यदि डेटासेट में इस नाम वाला लेयर है; अन्यथा, <see langword="false" /> |


### Method: open(path, driver)  [static] {#open_path_driver_15}


```
 open(path, driver) 
```

डेटासेट खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | डेटासेट का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: open(path, driver)  [static] {#open_path_driver_16}


```
 open(path, driver) 
```

डेटासेट खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | डेटासेट का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_17}


```
 open(path, driver, options) 
```

डेटासेट खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | डेटासेट का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_18}


```
 open(path, driver, options) 
```

डेटासेट खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | डेटासेट का पथ। |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | उपयोग करने के लिए ड्राइवर। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: open(path, options)  [static] {#open_path_options_19}


```
 open(path, options) 
```

gpkg फ़ाइल से डेटासेट बनाने के लिए फ़ैक्टरी मेथड।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | gpkg फ़ाइल का पाथ। |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | gpkg फ़ाइल को पढ़ने की विशेषताओं से संबंधित सेटिंग्स। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset) | [GeoPackageDataset](/psd/python-net/aspose.gis.formats.geopackage/geopackagedataset/) |


### Method: open_layer(name, options) {#open_layer_name_options_20}


```
 open_layer(name, options) 
```

निर्दिष्ट नाम वाले लेयर को पढ़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | खोलने के लिए लेयर का नाम। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | खोलने के विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | पढ़ने के लिए खोला गया लेयर। |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_21}


```
 open_layer_at(index, options) 
```

निर्दिष्ट सूचकांक पर लेयर को पढ़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | खोलने के लिए लेयर का सूचकांक। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | खोलने के विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | पढ़ने के लिए खोला गया लेयर। |


### Method: open_layer_at(index, options) {#open_layer_at_index_options_22}


```
 open_layer_at(index, options) 
```

निर्दिष्ट सूचकांक पर लेयर को पढ़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | खोलने के लिए लेयर का सूचकांक। |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | खोलने के विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | पढ़ने के लिए खोला गया लेयर। |


### Method: open_tile_layer(name, options) {#open_tile_layer_name_options_23}


```
 open_tile_layer(name, options) 
```

निर्दिष्ट नाम के साथ टाइल लेयर को पढ़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | खोलने के लिए लेयर का नाम। |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | खोलने के विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | टाइल लेयर पढ़ने के लिए खोला गया। |


### Method: open_tile_layer_at(index, options) {#open_tile_layer_at_index_options_24}


```
 open_tile_layer_at(index, options) 
```

निर्दिष्ट इंडेक्स पर टाइल लेयर को पढ़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | खोलने के लिए लेयर का सूचकांक। |
| options | [GeoPackageOptions](/psd/python-net/aspose.gis.formats.geopackage/geopackageoptions) | खोलने के विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) | [XyzTiles](/psd/python-net/aspose.gis.formats.xyztile/xyztiles/) |


### Method: remove_layer(name) {#remove_layer_name_25}


```
 remove_layer(name) 
```

निर्दिष्ट नाम वाले वेक्टर लेयर को हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| नाम | string | लेयर का नाम |

### Method: remove_layer_at(index) {#remove_layer_at_index_26}


```
 remove_layer_at(index) 
```

निर्दिष्ट सूचकांक पर वेक्टर लेयर को हटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| index | इंट | लेयर का सूचकांक |

### Method: rename_layer(current_name, new_name) {#rename_layer_current_name_new_name_27}


```
 rename_layer(current_name, new_name) 
```

डेटासेट में लेयर का नाम बदलें

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| current_name | string | लेयर का वर्तमान नाम |
| new_name | string | लेयर के लिए नया नाम |

