---
title: "MifTokenizer 클래스"
type: docs
weight: 40
url: /ko/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokenizer/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.interchangeformat](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/)

**Full Name:** aspose.gis.common.formats.mapinfo.interchangeformat.MifTokenizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MifTokenizer(path)](#MifTokenizer_path_1) | MifTokenizer 클래스의 새 인스턴스를 초기화합니다. |
| [MifTokenizer(path)](#MifTokenizer_path_2) | MifTokenizer 클래스의 새 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| 인코딩 | System.Text.Encoding | r/w |  |
| line_number | long | r |  |
| 위치 | long | r |  |
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

MifTokenizer 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string |  |

### Constructor: MifTokenizer(path) {#MifTokenizer_path_2}


```
 MifTokenizer(path) 
```

MifTokenizer 클래스의 새 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

### Method: peek_token() {#peek_token__1}


```
 peek_token() 
```

  

**Returns**

| 형식 | 설명 |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_char(description) {#read_char_description_2}


```
 read_char(description) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 설명 | string |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| char |  |


### Method: read_double(description) {#read_double_description_3}


```
 read_double(description) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 설명 | string |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| double |  |


### Method: read_int(description) {#read_int_description_4}


```
 read_int(description) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 설명 | string |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| int |  |


### Method: read_keyword(description) {#read_keyword_description_5}


```
 read_keyword(description) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 설명 | string |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| string |  |


### Method: read_string(description) {#read_string_description_6}


```
 read_string(description) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 설명 | string |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| string |  |


### Method: read_token() {#read_token__7}


```
 read_token() 
```

  

**Returns**

| 형식 | 설명 |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_token(expected_type, description) {#read_token_expected_type_description_8}


```
 read_token(expected_type, description) 
```

  

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| expected_type | [MifTokenType](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokentype) |  |
| 설명 | string |  |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


