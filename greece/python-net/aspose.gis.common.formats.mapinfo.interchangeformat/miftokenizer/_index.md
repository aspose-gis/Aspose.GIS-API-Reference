---
title: "Κλάση MifTokenizer"
type: docs
weight: 40
url: /el/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokenizer/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.interchangeformat](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/)

**Full Name:** aspose.gis.common.formats.mapinfo.interchangeformat.MifTokenizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MifTokenizer(path)](#MifTokenizer_path_1) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MifTokenizer |
| [MifTokenizer(path)](#MifTokenizer_path_2) | Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MifTokenizer |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| κωδικοποίηση | System.Text.Encoding | r/w |  |
| line_number | long | r |  |
| θέση | long | r |  |
## **Methods**
| **Name** | **Description** |
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

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MifTokenizer

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | string |  |

### Constructor: MifTokenizer(path) {#MifTokenizer_path_2}


```
 MifTokenizer(path) 
```

Αρχικοποιεί ένα νέο στιγμιότυπο της κλάσης MifTokenizer

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

### Method: peek_token() {#peek_token__1}


```
 peek_token() 
```

  

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_char(description) {#read_char_description_2}


```
 read_char(description) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| περιγραφή | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| char |  |


### Method: read_double(description) {#read_double_description_3}


```
 read_double(description) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| περιγραφή | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| double |  |


### Method: read_int(description) {#read_int_description_4}


```
 read_int(description) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| περιγραφή | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| int |  |


### Method: read_keyword(description) {#read_keyword_description_5}


```
 read_keyword(description) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| περιγραφή | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string |  |


### Method: read_string(description) {#read_string_description_6}


```
 read_string(description) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| περιγραφή | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| string |  |


### Method: read_token() {#read_token__7}


```
 read_token() 
```

  

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_token(expected_type, description) {#read_token_expected_type_description_8}


```
 read_token(expected_type, description) 
```

  

**Parameters:**

| Παράμετρος | Τύπος | Περιγραφή |
| :- | :- | :- |
| expected_type | [MifTokenType](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokentype) |  |
| περιγραφή | string |  |

**Returns**

| Τύπος | Περιγραφή |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


