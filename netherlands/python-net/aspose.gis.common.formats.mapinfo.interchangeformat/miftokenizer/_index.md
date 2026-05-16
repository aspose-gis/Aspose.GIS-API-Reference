---
title: "MifTokenizer Klasse"
type: docs
weight: 40
url: /nl/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokenizer/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.interchangeformat](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/)

**Full Name:** aspose.gis.common.formats.mapinfo.interchangeformat.MifTokenizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beschrijving** |
| :- | :- |
| [MifTokenizer(path)](#MifTokenizer_path_1) | Initialiseert een nieuwe instantie van de MifTokenizer klasse |
| [MifTokenizer(path)](#MifTokenizer_path_2) | Initialiseert een nieuwe instantie van de MifTokenizer klasse |
## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| codering | System.Text.Encoding | r/w |  |
| line_number | long | r |  |
| positie | long | r |  |
## **Methods**
| **Name** | **Beschrijving** |
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

Initialiseert een nieuwe instantie van de MifTokenizer klasse

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string |  |

### Constructor: MifTokenizer(path) {#MifTokenizer_path_2}


```
 MifTokenizer(path) 
```

Initialiseert een nieuwe instantie van de MifTokenizer klasse

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

### Method: peek_token() {#peek_token__1}


```
 peek_token() 
```

  

**Returns**

| Type | Beschrijving |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_char(description) {#read_char_description_2}


```
 read_char(description) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| beschrijving | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| char |  |


### Method: read_double(description) {#read_double_description_3}


```
 read_double(description) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| beschrijving | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| double |  |


### Method: read_int(description) {#read_int_description_4}


```
 read_int(description) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| beschrijving | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| int |  |


### Method: read_keyword(description) {#read_keyword_description_5}


```
 read_keyword(description) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| beschrijving | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string |  |


### Method: read_string(description) {#read_string_description_6}


```
 read_string(description) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| beschrijving | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| string |  |


### Method: read_token() {#read_token__7}


```
 read_token() 
```

  

**Returns**

| Type | Beschrijving |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_token(expected_type, description) {#read_token_expected_type_description_8}


```
 read_token(expected_type, description) 
```

  

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| expected_type | [MifTokenType](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokentype) |  |
| beschrijving | string |  |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


