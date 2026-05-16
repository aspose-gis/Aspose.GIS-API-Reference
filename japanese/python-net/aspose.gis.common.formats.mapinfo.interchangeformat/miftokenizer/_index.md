---
title: "MifTokenizer クラス"
type: docs
weight: 40
url: /ja/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokenizer/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.interchangeformat](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/)

**Full Name:** aspose.gis.common.formats.mapinfo.interchangeformat.MifTokenizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [MifTokenizer(path)](#MifTokenizer_path_1) | MifTokenizer クラスの新しいインスタンスを初期化します。 |
| [MifTokenizer(path)](#MifTokenizer_path_2) | MifTokenizer クラスの新しいインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| エンコーディング | System.Text.Encoding | 読み/書き |  |
| line_number | long | r |  |
| 位置 | long | r |  |
## **Methods**
| **Name** | **説明** |
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

MifTokenizer クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string |  |

### Constructor: MifTokenizer(path) {#MifTokenizer_path_2}


```
 MifTokenizer(path) 
```

MifTokenizer クラスの新しいインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

### Method: peek_token() {#peek_token__1}


```
 peek_token() 
```

  

**Returns**

| 型 | 説明 |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_char(description) {#read_char_description_2}


```
 read_char(description) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 説明 | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| char |  |


### Method: read_double(description) {#read_double_description_3}


```
 read_double(description) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 説明 | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| double |  |


### Method: read_int(description) {#read_int_description_4}


```
 read_int(description) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 説明 | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| int |  |


### Method: read_keyword(description) {#read_keyword_description_5}


```
 read_keyword(description) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 説明 | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| string |  |


### Method: read_string(description) {#read_string_description_6}


```
 read_string(description) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 説明 | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| string |  |


### Method: read_token() {#read_token__7}


```
 read_token() 
```

  

**Returns**

| 型 | 説明 |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_token(expected_type, description) {#read_token_expected_type_description_8}


```
 read_token(expected_type, description) 
```

  

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| expected_type | [MifTokenType](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokentype) |  |
| 説明 | string |  |

**Returns**

| 型 | 説明 |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


