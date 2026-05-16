---
title: "Kelas SimpleLabeling"
type: docs
weight: 80
url: /id/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Menginisialisasi sebuah instance baru dari kelas [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Menginisialisasi sebuah instance baru dari kelas [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Menginisialisasi sebuah instance baru dari kelas [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | Menentukan warna teks. |
| font_family | string | r/w | Keluarga font yang digunakan untuk merender teks. Nilai default bergantung pada sistem. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Ukuran teks. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Gaya yang diterapkan pada teks. |
| halo_color | System.Drawing.Color | r/w | Warna halo (garis tepi) di sekitar teks. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Ukuran halo (garis tepi) di sekitar teks. |
| label_attribute | string | r/w | Nama atribut yang digunakan sebagai sumber label. Diabaikan jika [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) diatur.<br/>            Baik [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) atau [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) harus diatur sebelum rendering;<br/>            InvalidOperationException dilemparkan sebaliknya. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Menentukan perilaku rendering untuk geometri multipart. Defaultnya adalah [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Mendapatkan instance dari [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | Penempatan label menentukan bagaimana label ditempatkan relatif terhadap geometri fitur. |
| prioritas | int | r/w | Menunjukkan prioritas label ini jika tumpang tindih dengan label lain. Label dengan prioritas lebih rendah tidak akan dirender.<br/>            Defaultnya adalah 1000. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [clone()](#clone__1) | Menggandakan instance ini. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Menginisialisasi sebuah instance baru dari kelas [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Menginisialisasi sebuah instance baru dari kelas [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| label_attribute | string | Nama atribut yang digunakan sebagai sumber label. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Menginisialisasi sebuah instance baru dari kelas [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Yang lain [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) untuk menyalin data darinya. |

### Method: clone() {#clone__1}


```
 clone() 
```

Menggandakan instance ini.

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Klon dari instance ini. |


