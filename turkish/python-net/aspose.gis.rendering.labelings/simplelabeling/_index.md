---
title: "SimpleLabeling Sınıfı"
type: docs
weight: 80
url: /tr/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | Yeni bir [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) sınıfı örneği başlatır. |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | Yeni bir [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) sınıfı örneği başlatır. |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | Yeni bir [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) sınıfı örneği başlatır. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | Metnin rengini belirler. |
| font_family | string | r/w | Metni renderlemek için kullanılacak yazı tipi ailesi. Varsayılan, sistem bağımlı bir değerdir. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Metnin boyutu. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Metne uygulanacak stil. |
| halo_color | System.Drawing.Color | r/w | Metnin etrafındaki halo (çizgi) rengini belirler. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Metnin etrafındaki halo (çizgi) boyutu. |
| label_attribute | string | r/w | Etiketlerin kaynağı olarak kullanılacak öznitelik adı. [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) ayarlanmışsa yok sayılır.<br/>            Ya [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) ya da [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) işleme başlamadan önce ayarlanmalıdır;<br/>            Aksi takdirde InvalidOperationException fırlatılır. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | Çok parçalı geometriler için işleme davranışını belirtir. Varsayılan değer [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | Bir [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) örneği alır. |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | Etiket yerleşimi, etiketlerin özelliğin geometrilerine göre nasıl konumlandırıldığını belirtir. |
| öncelik | int | r/w | Bu etiketin başka bir etiketle çakışması durumunda önceliğini gösterir. Daha düşük önceliğe sahip etiket işlenmez.<br/>            Varsayılan değer 1000. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Bu örneği klonlar. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

Yeni bir [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) sınıfı örneği başlatır.

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

Yeni bir [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| label_attribute | string | Etiketlerin kaynağı olarak kullanılacak öznitelik adı. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

Yeni bir [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) sınıfı örneği başlatır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Veri kopyalanacak diğer [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | Bu örneğin bir klonu. |


