---
title: "GeoConvert Sınıfı"
type: docs
weight: 1140
url: /tr/python-net/aspose.gis/geoconvert/
---

**Summary:** Converts coordinates to/from the different formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.GeoConvert

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [as_point_text(latitude, longitude, format)](#as_point_text_latitude_longitude_format_1) | Hesaplanan konumu belirtilen formatta bir dize olarak döndürür. |
| [as_point_text(point, format)](#as_point_text_point_format_2) | Hesaplanan konumu belirtilen formatta bir dize olarak döndürür. |
| [parse_point_text(text)](#parse_point_text_text_3) | Koordinatları içeren dizeyi IPoint nesnesine dönüştürür. |
| [try_parse_point_text(text, point)](#try_parse_point_text_text_point_4) | Koordinatları içeren dizeyi IPoint nesnesine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir. |


### Method: as_point_text(latitude, longitude, format)  [static] {#as_point_text_latitude_longitude_format_1}


```
 as_point_text(latitude, longitude, format) 
```

Hesaplanan konumu belirtilen formatta bir dize olarak döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| enlem | double | Konum enlemi. |
| boylam | double | Konum boylamı. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Sonucun formatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Konum dize olarak. |


### Method: as_point_text(point, format)  [static] {#as_point_text_point_format_2}


```
 as_point_text(point, format) 
```

Hesaplanan konumu belirtilen formatta bir dize olarak döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | IPoint nesnesi. |
| format | [PointFormats](/psd/python-net/aspose.gis/pointformats) | Sonucun formatı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Konum dize olarak. |


### Method: parse_point_text(text)  [static] {#parse_point_text_text_3}


```
 parse_point_text(text) 
```

Koordinatları içeren dizeyi IPoint nesnesine dönüştürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | string | Dönüştürülecek koordinatları içeren bir dize.<br/>            Dize hem enlem hem de boylam koordinatlarını içermelidir.<br/>            Koordinatlar boşluk, virgül veya noktalı virgül ile ayrılmalıdır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Girdi dizesine eşdeğer koordinatlara sahip IPoint nesnesi. |


### Method: try_parse_point_text(text, point)  [static] {#try_parse_point_text_text_point_4}


```
 try_parse_point_text(text, point) 
```

Koordinatları içeren dizeyi IPoint nesnesine dönüştürür. Dönen değer, dönüşümün başarılı olup olmadığını gösterir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| text | string | Dönüştürülecek koordinatları içeren bir dize.<br/>            Dize hem enlem hem de boylam koordinatlarını içermelidir.<br/>            Koordinatlar boşluk, virgül veya noktalı virgül ile ayrılmalıdır. |
| point | [IPoint[]](/psd/python-net/aspose.gis.geometries/ipoint/) | Bu yöntem döndüğünde, dönüşüm başarılıysa ayrıştırılmış koordinatlarla IPoint nesnesini, başarısızsa null değerini içerir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Metin başarıyla ayrıştırıldıysa True, aksi takdirde False. |


