---
title: "MifTokenizer Класс"
type: docs
weight: 40
url: /ru/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokenizer/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.interchangeformat](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/)

**Full Name:** aspose.gis.common.formats.mapinfo.interchangeformat.MifTokenizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Описание** |
| :- | :- |
| [MifTokenizer(path)](#MifTokenizer_path_1) | Инициализирует новый экземпляр класса MifTokenizer |
| [MifTokenizer(path)](#MifTokenizer_path_2) | Инициализирует новый экземпляр класса MifTokenizer |
## **Properties**
| **Name** | **Type** | **Access** | **Описание** |
| :- | :- | :- | :- |
| кодировка | System.Text.Encoding | r/w |  |
| line_number | long | r |  |
| позиция | long | r |  |
## **Methods**
| **Name** | **Описание** |
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

Инициализирует новый экземпляр класса MifTokenizer

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | string |  |

### Constructor: MifTokenizer(path) {#MifTokenizer_path_2}


```
 MifTokenizer(path) 
```

Инициализирует новый экземпляр класса MifTokenizer

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

### Method: peek_token() {#peek_token__1}


```
 peek_token() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_char(description) {#read_char_description_2}


```
 read_char(description) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| описание | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| char |  |


### Method: read_double(description) {#read_double_description_3}


```
 read_double(description) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| описание | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| double |  |


### Method: read_int(description) {#read_int_description_4}


```
 read_int(description) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| описание | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| int |  |


### Method: read_keyword(description) {#read_keyword_description_5}


```
 read_keyword(description) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| описание | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| string |  |


### Method: read_string(description) {#read_string_description_6}


```
 read_string(description) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| описание | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| string |  |


### Method: read_token() {#read_token__7}


```
 read_token() 
```

  

**Returns**

| Тип | Описание |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_token(expected_type, description) {#read_token_expected_type_description_8}


```
 read_token(expected_type, description) 
```

  

**Parameters:**

| Параметр | Тип | Описание |
| :- | :- | :- |
| expected_type | [MifTokenType](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokentype) |  |
| описание | string |  |

**Returns**

| Тип | Описание |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


