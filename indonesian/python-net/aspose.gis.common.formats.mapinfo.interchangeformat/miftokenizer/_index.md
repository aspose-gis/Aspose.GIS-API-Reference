---
title: "MifTokenizer Kelas"
type: docs
weight: 40
url: /id/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokenizer/
---

**Summary:** 

**Module:** [aspose.gis.common.formats.mapinfo.interchangeformat](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/)

**Full Name:** aspose.gis.common.formats.mapinfo.interchangeformat.MifTokenizer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [MifTokenizer(path)](#MifTokenizer_path_1) | Menginisialisasi sebuah instance baru dari kelas MifTokenizer |
| [MifTokenizer(path)](#MifTokenizer_path_2) | Menginisialisasi sebuah instance baru dari kelas MifTokenizer |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| pengkodean | System.Text.Encoding | r/w |  |
| line_number | long | r |  |
| posisi | long | r |  |
## **Methods**
| **Name** | **Deskripsi** |
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

Menginisialisasi sebuah instance baru dari kelas MifTokenizer

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| jalur | string |  |

### Constructor: MifTokenizer(path) {#MifTokenizer_path_2}


```
 MifTokenizer(path) 
```

Menginisialisasi sebuah instance baru dari kelas MifTokenizer

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| path | [AbstractPathInternal](/psd/python-net/aspose.gis.common/abstractpathinternal) |  |

### Method: peek_token() {#peek_token__1}


```
 peek_token() 
```

  

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_char(description) {#read_char_description_2}


```
 read_char(description) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| description | string |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| char |  |


### Method: read_double(description) {#read_double_description_3}


```
 read_double(description) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| description | string |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| double |  |


### Method: read_int(description) {#read_int_description_4}


```
 read_int(description) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| description | string |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| int |  |


### Method: read_keyword(description) {#read_keyword_description_5}


```
 read_keyword(description) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| description | string |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string |  |


### Method: read_string(description) {#read_string_description_6}


```
 read_string(description) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| description | string |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| string |  |


### Method: read_token() {#read_token__7}


```
 read_token() 
```

  

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


### Method: read_token(expected_type, description) {#read_token_expected_type_description_8}


```
 read_token(expected_type, description) 
```

  

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| expected_type | [MifTokenType](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftokentype) |  |
| description | string |  |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [MifToken](/psd/python-net/aspose.gis.common.formats.mapinfo.interchangeformat/miftoken) |  |


