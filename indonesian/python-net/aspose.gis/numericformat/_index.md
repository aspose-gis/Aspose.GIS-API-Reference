---
title: "Kelas NumericFormat"
type: docs
weight: 2870
url: /id/python-net/aspose.gis/numericformat/
---

**Summary:** [NumericFormat](/psd/python-net/aspose.gis/numericformat/) are used to format common numeric types in text.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.NumericFormat

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| round_trip [static] | [NumericFormat](/psd/python-net/aspose.gis/numericformat) | r | Mengonversi dan berusaha memastikan bahwa nilai numerik yang dikonversi menjadi<br/>            string dapat diurai kembali menjadi nilai numerik yang sama. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [flat(significant_digits)](#flat_significant_digits_1) | Mengonversi angka menjadi teks titik tetap tanpa notasi ilmiah. |
| [general(precision)](#general_precision_2) | Mengonversi angka menjadi notasi yang lebih ringkas, baik titik tetap maupun ilmiah,<br/>            tergantung pada tipe angka dan apakah ada spesifikasi presisi. Disarankan untuk digunakan. |


### Method: flat(significant_digits)  [static] {#flat_significant_digits_1}


```
 flat(significant_digits) 
```

Mengonversi angka menjadi teks titik tetap tanpa notasi ilmiah.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| significant_digits | int | Jumlah digit signifikan. Presisi maksimum yang tersedia adalah "308" |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Penentu Presisi Pembulatan. |


### Method: general(precision)  [static] {#general_precision_2}


```
 general(precision) 
```

Mengonversi angka menjadi notasi yang lebih ringkas, baik titik tetap maupun ilmiah,<br/>            tergantung pada tipe angka dan apakah ada spesifikasi presisi. Disarankan untuk digunakan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| precision | int | Presisi menentukan jumlah maksimum digit signifikan yang dapat muncul dalam string hasil.<br/>            Jika presisi nol, nilai "15" digunakan. Presisi maksimum yang tersedia adalah "17". |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [NumericFormat](/psd/python-net/aspose.gis/numericformat) | Penentu Format Umum. |


