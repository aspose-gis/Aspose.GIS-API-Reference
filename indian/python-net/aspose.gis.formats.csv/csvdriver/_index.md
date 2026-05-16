---
title: "CsvDriver क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.gis.formats.csv/csvdriver/
---

**Summary:** A driver for the CSV format.

**Module:** [aspose.gis.formats.csv](/psd/python-net/aspose.gis.formats.csv/)

**Full Name:** aspose.gis.formats.csv.CsvDriver

**Inheritance:** FileDriver

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [CsvDriver()](#CsvDriver__1) | CsvDriver क्लास का नया उदाहरण आरंभ करता है |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| can_create_datasets | bool | r | इस driver द्वारा datasets बनाये जा सकते हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| can_create_layers | bool | r | इस driver द्वारा vector layers बनाये जा सकते हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| can_open_datasets | bool | r | इस driver द्वारा datasets खोले जा सकते हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
| can_open_layers | bool | r | इस driver द्वारा vector layers खोले जा सकते हैं या नहीं, यह दर्शाने वाला मान प्राप्त करता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [create_dataset(path)](#create_dataset_path_1) | एक dataset बनाता है। |
| [create_dataset(path)](#create_dataset_path_2) | एक dataset बनाता है। |
| [create_dataset(path, options)](#create_dataset_path_options_3) | एक dataset बनाता है। |
| [create_dataset(path, options)](#create_dataset_path_options_4) | एक dataset बनाता है। |
| [create_layer(path)](#create_layer_path_5) | लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create_layer(path)](#create_layer_path_6) | लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create_layer(path, options)](#create_layer_path_options_7) | एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है। |
| [create_layer(path, options)](#create_layer_path_options_8) | एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है। |
| [create_layer(path, options)](#create_layer_path_options_9) | एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है। |
| [create_layer(path, options)](#create_layer_path_options_10) | एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है। |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_11) | एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है। |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_12) | एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है। |
| [create_layer(path, options, spatial_reference_system)](#create_layer_path_options_spatial_reference_system_13) | एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है। |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_14) | लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [create_layer(path, spatial_reference_system)](#create_layer_path_spatial_reference_system_15) | लेयर बनाता है और उसे जोड़ने के लिए खोलता है। |
| [edit_layer(path, options)](#edit_layer_path_options_16) | संपादन के लिए एक लेयर खोलता है। |
| [edit_layer(path, options)](#edit_layer_path_options_17) | संपादन के लिए एक लेयर खोलता है। |
| [open_dataset(path)](#open_dataset_path_18) | डेटासेट खोलता है। |
| [open_dataset(path)](#open_dataset_path_19) | डेटासेट खोलता है। |
| [open_dataset(path, options)](#open_dataset_path_options_20) | डेटासेट खोलता है। |
| [open_dataset(path, options)](#open_dataset_path_options_21) | डेटासेट खोलता है। |
| [open_layer(path)](#open_layer_path_22) | पढ़ने के लिए लेयर खोलता है। |
| [open_layer(path)](#open_layer_path_23) | पढ़ने के लिए लेयर खोलता है। |
| [open_layer(path, options)](#open_layer_path_options_24) | पढ़ने के लिए एक लेयर खोलता है। |
| [open_layer(path, options)](#open_layer_path_options_25) | पढ़ने के लिए एक लेयर खोलता है। |
| [open_layer(path, options)](#open_layer_path_options_26) | पढ़ने के लिए एक लेयर खोलता है। |
| [open_layer(path, options)](#open_layer_path_options_27) | पढ़ने के लिए एक लेयर खोलता है। |
| [supports_spatial_reference_system(spatial_reference_system)](#supports_spatial_reference_system_spatial_reference_system_28) | निर्धारित करता है कि निर्दिष्ट स्पैशियल रेफ़रेंस सिस्टम ड्राइवर द्वारा समर्थित है या नहीं। |


### Constructor: CsvDriver() {#CsvDriver__1}


```
 CsvDriver() 
```

CsvDriver क्लास का नया उदाहरण आरंभ करता है

### Method: create_dataset(path) {#create_dataset_path_1}


```
 create_dataset(path) 
```

एक dataset बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | डेटासेट का पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: create_dataset(path) {#create_dataset_path_2}


```
 create_dataset(path) 
```

एक dataset बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | डेटासेट का पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: create_dataset(path, options) {#create_dataset_path_options_3}


```
 create_dataset(path, options) 
```

एक dataset बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | डेटासेट का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: create_dataset(path, options) {#create_dataset_path_options_4}


```
 create_dataset(path, options) 
```

एक dataset बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | डेटासेट का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: create_layer(path) {#create_layer_path_5}


```
 create_layer(path) 
```

लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path) {#create_layer_path_6}


```
 create_layer(path) 
```

लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path, options) {#create_layer_path_options_7}


```
 create_layer(path, options) 
```

एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| options | [CsvOptions](/psd/python-net/aspose.gis.formats.csv/csvoptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path, options) {#create_layer_path_options_8}


```
 create_layer(path, options) 
```

एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| options | [CsvOptions](/psd/python-net/aspose.gis.formats.csv/csvoptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path, options) {#create_layer_path_options_9}


```
 create_layer(path, options) 
```

एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path, options) {#create_layer_path_options_10}


```
 create_layer(path, options) 
```

एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_11}


```
 create_layer(path, options, spatial_reference_system) 
```

एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_12}


```
 create_layer(path, options, spatial_reference_system) 
```

एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| options | [CsvOptions](/psd/python-net/aspose.gis.formats.csv/csvoptions) | ड्राइवर-विशिष्ट विकल्प। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path, options, spatial_reference_system) {#create_layer_path_options_spatial_reference_system_13}


```
 create_layer(path, options, spatial_reference_system) 
```

एक लेयर बनाता है और नई विशेषताएँ जोड़ने के लिए उसे खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_14}


```
 create_layer(path, spatial_reference_system) 
```

लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: create_layer(path, spatial_reference_system) {#create_layer_path_spatial_reference_system_15}


```
 create_layer(path, spatial_reference_system) 
```

लेयर बनाता है और उसे जोड़ने के लिए खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: edit_layer(path, options) {#edit_layer_path_options_16}


```
 edit_layer(path, options) 
```

संपादन के लिए एक लेयर खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: edit_layer(path, options) {#edit_layer_path_options_17}


```
 edit_layer(path, options) 
```

संपादन के लिए एक लेयर खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: open_dataset(path) {#open_dataset_path_18}


```
 open_dataset(path) 
```

डेटासेट खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | डेटासेट का पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: open_dataset(path) {#open_dataset_path_19}


```
 open_dataset(path) 
```

डेटासेट खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | डेटासेट का पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: open_dataset(path, options) {#open_dataset_path_options_20}


```
 open_dataset(path, options) 
```

डेटासेट खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | डेटासेट का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: open_dataset(path, options) {#open_dataset_path_options_21}


```
 open_dataset(path, options) 
```

डेटासेट खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | डेटासेट का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [Dataset](/psd/python-net/aspose.gis/dataset) | एक उदाहरण [Dataset](/psd/python-net/aspose.gis/dataset/) का। |


### Method: open_layer(path) {#open_layer_path_22}


```
 open_layer(path) 
```

पढ़ने के लिए लेयर खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: open_layer(path) {#open_layer_path_23}


```
 open_layer(path) 
```

पढ़ने के लिए लेयर खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: open_layer(path, options) {#open_layer_path_options_24}


```
 open_layer(path, options) 
```

पढ़ने के लिए एक लेयर खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| options | [CsvOptions](/psd/python-net/aspose.gis.formats.csv/csvoptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: open_layer(path, options) {#open_layer_path_options_25}


```
 open_layer(path, options) 
```

पढ़ने के लिए एक लेयर खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: open_layer(path, options) {#open_layer_path_options_26}


```
 open_layer(path, options) 
```

पढ़ने के लिए एक लेयर खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | फ़ाइल का पथ। |
| options | [CsvOptions](/psd/python-net/aspose.gis.formats.csv/csvoptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: open_layer(path, options) {#open_layer_path_options_27}


```
 open_layer(path, options) 
```

पढ़ने के लिए एक लेयर खोलता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | फ़ाइल का पथ। |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | ड्राइवर-विशिष्ट विकल्प। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | एक उदाहरण [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) का। |


### Method: supports_spatial_reference_system(spatial_reference_system) {#supports_spatial_reference_system_spatial_reference_system_28}


```
 supports_spatial_reference_system(spatial_reference_system) 
```

निर्धारित करता है कि निर्दिष्ट स्पैशियल रेफ़रेंस सिस्टम ड्राइवर द्वारा समर्थित है या नहीं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | स्पैशियल रेफ़रेंस सिस्टम। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | बूलियन मान, जो दर्शाता है कि निर्दिष्ट स्पैशियल रेफ़रेंस सिस्टम ड्राइवर द्वारा समर्थित है या नहीं। |


