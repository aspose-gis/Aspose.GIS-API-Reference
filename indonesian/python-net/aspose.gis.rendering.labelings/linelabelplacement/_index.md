---
title: "Kelas LineLabelPlacement"
type: docs
weight: 40
url: /id/python-net/aspose.gis.rendering.labelings/linelabelplacement/
---

**Summary:** Line label placement places labels along line.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.LineLabelPlacement

**Inheritance:** LabelPlacement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [LineLabelPlacement()](#LineLabelPlacement__1) | Membuat instance baru. |
| [LineLabelPlacement(other)](#LineLabelPlacement_other_2) | Membuat instance baru. |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| alignment | [LineLabelAlignment](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment) | r/w | Menentukan bagaimana label disejajarkan dengan jalur linier. Defaultnya adalah [LineLabelAlignment.PARALLEL](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/). |
| max_angle_delta | double | r/w | Saat digunakan dengan [LineLabelAlignment.CURVED](/psd/python-net/aspose.gis.rendering.labelings/linelabelalignment/) menetapkan sudut maksimum dalam derajat antara dua<br/>            karakter berurutan dalam label melengkung. Defaultnya adalah 25. |
| offset | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Offset dari jalur linier.<br/>            Nilai positif mengoffset ke kiri garis, nilai negatif ke kanan. Defaultnya adalah 0. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Menggandakan instance ini. |


### Constructor: LineLabelPlacement() {#LineLabelPlacement__1}


```
 LineLabelPlacement() 
```

Membuat instance baru.

### Constructor: LineLabelPlacement(other) {#LineLabelPlacement_other_2}


```
 LineLabelPlacement(other) 
```

Membuat instance baru.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement) | [LineLabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/linelabelplacement/) lain untuk menyalin data darinya. |

### Method: clone() {#clone__1}


```
 clone() 
```

Menggandakan instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | Klon dari instance ini. |


