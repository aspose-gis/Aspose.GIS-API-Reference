---
title: "MultiStreamPath क्लास"
type: docs
weight: 2760
url: /hi/python-net/aspose.gis/multistreampath/
---

**Summary:** This class works with formats which contains several files.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.MultiStreamPath

**Inheritance:** AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [MultiStreamPath(entry_file_name, file_names, streams)](#MultiStreamPath_entry_file_name_file_names_streams_1) | नए [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| स्थान | string | r | इस <c>AbstractPath</c> के स्थान की स्ट्रिंग प्रतिनिधित्व प्राप्त करता है। |
| separator | char | r | डायरेक्टरी स्तरों को अलग करने के लिए उपयोग किए जाने वाले सेपरेटर कैरेक्टर को प्राप्त करता है, जो [MultiStreamPath.location](/psd/python-net/aspose.gis/multistreampath/) स्ट्रिंग में है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [combine(location)](#combine_location_1) | इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) को निर्दिष्ट पाथ घटकों के साथ संयोजित करता है। |
| delete() | इस पाथ द्वारा इंगित फ़ाइल को हटाता है। |
| [from_local_path(path)](#from_local_path_path_2) | एक [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) बनाता है जो स्थानीय फ़ाइल सिस्टम पर एक स्थान को दर्शाता है। |
| [from_stream(stream)](#from_stream_stream_3) | एक स्ट्रीम से एक [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) बनाता है। |
| [get_extension()](#get_extension__4) | इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) का एक्सटेंशन लौटाता है। |
| [get_file_name()](#get_file_name__5) | इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) का फ़ाइल नाम और एक्सटेंशन लौटाता है। |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) का फ़ाइल नाम एक्सटेंशन के बिना लौटाता है। |
| [is_file()](#is_file__7) | एक मान प्राप्त करता है जो दर्शाता है कि यह पाथ किसी मौजूदा फ़ाइल की ओर इशारा करता है जिसे पढ़ने के लिए खोला जा सकता है। |
| [list_directory()](#list_directory__8) | यदि यह एक डायरेक्टरी है, तो इस <c>AbstractPath</c> के अंदर स्थित पाथ लौटाता है। |
| [open(access)](#open_access_9) | डेटा तक पहुँचने के लिए एक पाथ के रूप में खुले स्ट्रीमिंग मल्टी‑फ़ाइल फ़ॉर्मेट्स का एक सेट एब्स्ट्रैक्ट करता है। |
| [with_extension(new_extension)](#with_extension_new_extension_10) | निर्दिष्ट मान में फ़ाइल एक्सटेंशन बदलकर एक नया [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) लौटाता है। |


### Constructor: MultiStreamPath(entry_file_name, file_names, streams) {#MultiStreamPath_entry_file_name_file_names_streams_1}


```
 MultiStreamPath(entry_file_name, file_names, streams) 
```

नए [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) क्लास का एक नया इंस्टेंस इनिशियलाइज़ करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| entry_file_name | string | एंट्री फ़ाइल का नाम। |
| file_names | string | फ़ाइल नाम। |
| streams | _io.BufferedRandom[] | स्ट्रीम्स। |

### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) को निर्दिष्ट पाथ घटकों के साथ संयोजित करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| location | string | इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) में जोड़ने के लिए एक पथ घटक। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | एक नया [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) जो एक [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) की ओर इंगित करता है, जो इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) और<br/>            तर्क के स्थानों के संयोजन से बना है। |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

एक [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) बनाता है जो स्थानीय फ़ाइल सिस्टम पर एक स्थान को दर्शाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string | स्थानीय फ़ाइल प्रणाली पर एक पथ, जैसे <c>"C:\\file.shp"</c> या <c>"D:\\directory\\"</c>। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | <paramref name="path" /> द्वारा परिभाषित स्थान को दर्शाने वाला एक [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)। |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

एक स्ट्रीम से एक [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| stream | _io.BufferedRandom | एक स्ट्रीम जिससे एक [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) बनाया जा सके। <c>Aspose.GIS</c> स्ट्रीम को नष्ट नहीं करता। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | निर्दिष्ट स्ट्रीम को अपनी सामग्री के रूप में रखने वाला एक [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) का उदाहरण। |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) का एक्सटेंशन लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) का विस्तार ("." सहित) या<br/>            यदि [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) में कोई विस्तार नहीं है तो एक खाली स्ट्रिंग। |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) का फ़ाइल नाम और एक्सटेंशन लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) में अंतिम [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) अक्षर के बाद के अक्षर। यदि<br/>            अंतिम अक्षर [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) है, तो एक खाली स्ट्रिंग लौटाई जाती है। यदि [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) में कोई<br/>            [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) अक्षर नहीं है, तो स्वयं [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) लौटाया जाता है। |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

इस [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) का फ़ाइल नाम एक्सटेंशन के बिना लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string | [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) द्वारा लौटाई गई स्ट्रिंग, अंतिम बिंदु और उसके बाद के सभी अक्षरों को हटाकर। |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

एक मान प्राप्त करता है जो दर्शाता है कि यह पाथ किसी मौजूदा फ़ाइल की ओर इशारा करता है जिसे पढ़ने के लिए खोला जा सकता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| bool | यदि स्थान फ़ाइल की ओर इशारा करता है तो <see langword="true" />, अन्यथा <see langword="false" />। |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

यदि यह एक डायरेक्टरी है, तो इस <c>AbstractPath</c> के अंदर स्थित पाथ लौटाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | इस <c>AbstractPath</c> के भीतर स्थित पथ। |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

डेटा तक पहुँचने के लिए एक पाथ के रूप में खुले स्ट्रीमिंग मल्टी‑फ़ाइल फ़ॉर्मेट्स का एक सेट एब्स्ट्रैक्ट करता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| पहुंच | System.IO.FileAccess | स्ट्रीम पर किए जा सकने वाले संचालन के उपसमुच्चय को निर्दिष्ट करता है। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| _io.BufferedRandom | यह या तो एक   हो सकता है या क्लाइंट द्वारा मूल रूप से पास किया गया स्ट्रीम। |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

निर्दिष्ट मान में फ़ाइल एक्सटेंशन बदलकर एक नया [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) लौटाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| new_extension | string | एक नया विस्तार। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | एक नया [AbstractPath](/psd/python-net/aspose.gis/abstractpath/), जो उसी निर्देशिका में एक फ़ाइल की ओर इंगित करता है, लेकिन एक नए विस्तार के साथ। |


