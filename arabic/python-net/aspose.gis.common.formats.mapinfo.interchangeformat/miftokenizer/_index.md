---
title: "فئة MifTokenizer"
type: docs
weight: 40
url: /ar/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokenizer/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.interchangeformat](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/)

**Full Name:** aspose.gis.common.formats.mapinfo.interchangeformat.MifTokenizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MifTokenizer(path)](#MifTokenizer_path_1) | ينشئ نسخة جديدة من فئة MifTokenizer |
| [MifTokenizer(path)](#MifTokenizer_path_2) | ينشئ نسخة جديدة من فئة MifTokenizer |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| الترميز | System.Text.Encoding | قراءة/كتابة |  |
| line_number | long | r |  |
| الموضع | long | r |  |
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

ينشئ نسخة جديدة من فئة MifTokenizer

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | string |  |

### Constructor: MifTokenizer(path) {#MifTokenizer_path_2}


```
 MifTokenizer(path) 
```

ينشئ نسخة جديدة من فئة MifTokenizer

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

### Method: peek_token() {#peek_token__1}


```
 peek_token() 
```

  

**Returns**

| نوع | وصف |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_char(description) {#read_char_description_2}


```
 read_char(description) 
```

  

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الوصف | string |  |

**Returns**

| نوع | وصف |
| :- | :- |
| حرف |  |


### Method: read_double(description) {#read_double_description_3}


```
 read_double(description) 
```

  

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الوصف | string |  |

**Returns**

| نوع | وصف |
| :- | :- |
| double |  |


### Method: read_int(description) {#read_int_description_4}


```
 read_int(description) 
```

  

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الوصف | string |  |

**Returns**

| نوع | وصف |
| :- | :- |
| int |  |


### Method: read_keyword(description) {#read_keyword_description_5}


```
 read_keyword(description) 
```

  

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الوصف | string |  |

**Returns**

| نوع | وصف |
| :- | :- |
| string |  |


### Method: read_string(description) {#read_string_description_6}


```
 read_string(description) 
```

  

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الوصف | string |  |

**Returns**

| نوع | وصف |
| :- | :- |
| string |  |


### Method: read_token() {#read_token__7}


```
 read_token() 
```

  

**Returns**

| نوع | وصف |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_token(expected_type, description) {#read_token_expected_type_description_8}


```
 read_token(expected_type, description) 
```

  

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| expected_type | [MifTokenType](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokentype) |  |
| الوصف | string |  |

**Returns**

| نوع | وصف |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


