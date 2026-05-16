---
title: "PrecisionModel Kelas"
type: docs
weight: 3200
url: /id/python-net/aspose.gis/precisionmodel/
---

**Summary:** [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) specifies a number of significant digits in a coordinate.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.PrecisionModel

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| exact [static] | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r | Mengembalikan model presisi tepat.<br/>            Menurut model presisi tepat semua digit dalam nilai double bersifat signifikan. |
| is_exact | bool | r | Mendapatkan nilai yang menunjukkan apakah model presisi ini tepat. |
| is_rounding | bool | r | Mendapatkan nilai yang menunjukkan apakah model presisi ini melakukan pembulatan. |
| significant_digits | int | r | Mendapatkan jumlah digit signifikan dalam model presisi jika model tersebut melakukan pembulatan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [rounding(significant_digits)](#rounding_significant_digits_1) | Mengembalikan model presisi pembulatan.<br/>            Menurut model presisi pembulatan hanya sejumlah terbatas digit yang signifikan. |


### Method: rounding(significant_digits)  [static] {#rounding_significant_digits_1}


```
 rounding(significant_digits) 
```

Mengembalikan model presisi pembulatan.<br/>            Menurut model presisi pembulatan hanya sejumlah terbatas digit yang signifikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| significant_digits | int | Jumlah digit signifikan. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | Model Presisi Pembulatan. |


