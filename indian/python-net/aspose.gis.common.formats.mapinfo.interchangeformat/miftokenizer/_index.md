---
title: "MifTokenizer क्लास"
type: docs
weight: 40
url: /hi/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokenizer/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.interchangeformat](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/)

**Full Name:** aspose.gis.common.formats.mapinfo.interchangeformat.MifTokenizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [MifTokenizer(path)](#MifTokenizer_path_1) | MifTokenizer क्लास का एक नया उदाहरण प्रारंभ करता है |
| [MifTokenizer(path)](#MifTokenizer_path_2) | MifTokenizer क्लास का एक नया उदाहरण प्रारंभ करता है |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| एन्कोडिंग | System.Text.Encoding | r/w |  |
| line_number | लॉन्ग | r |  |
| स्थिति | लॉन्ग | r |  |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [peek_token()](#peek_token__1) |    |
| [read_char(description)](#read_char_description_2) |    |
| [read_double(description)](#read_double_description_3) |    |
| [read_int(description)](#read_int_description_4) |    |
| [read_keyword(description)](#read_keyword_description_5) |    |
| [read_string(description)](#read_string_description_6) |    |
| [read_token()](#read_token__7) |    |
| [read_token(expected_type, description)](#read_token_expected_type_description_8) |    |
| seek(new_position, new_line_number) |  |
| skip_to_new_line() |  |


### Constructor: MifTokenizer(path) {#MifTokenizer_path_1}


```
 MifTokenizer(path) 
```

MifTokenizer क्लास का एक नया उदाहरण प्रारंभ करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | string |  |

### Constructor: MifTokenizer(path) {#MifTokenizer_path_2}


```
 MifTokenizer(path) 
```

MifTokenizer क्लास का एक नया उदाहरण प्रारंभ करता है

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

### Method: peek_token() {#peek_token__1}


```
 peek_token() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_char(description) {#read_char_description_2}


```
 read_char(description) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| विवरण | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| चर |  |


### Method: read_double(description) {#read_double_description_3}


```
 read_double(description) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| विवरण | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| double |  |


### Method: read_int(description) {#read_int_description_4}


```
 read_int(description) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| विवरण | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| इंट |  |


### Method: read_keyword(description) {#read_keyword_description_5}


```
 read_keyword(description) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| विवरण | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string |  |


### Method: read_string(description) {#read_string_description_6}


```
 read_string(description) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| विवरण | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| string |  |


### Method: read_token() {#read_token__7}


```
 read_token() 
```

  

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_token(expected_type, description) {#read_token_expected_type_description_8}


```
 read_token(expected_type, description) 
```

  

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| expected_type | [MifTokenType](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokentype) |  |
| विवरण | string |  |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


