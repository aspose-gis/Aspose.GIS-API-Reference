---
title: "SimpleLabeling فئة"
type: docs
weight: 80
url: /ar/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | يُنشئ مثلاً جديداً من الفئة [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | يُنشئ مثلاً جديداً من الفئة [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | يُنشئ مثلاً جديداً من الفئة [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/). |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | قراءة/كتابة | يحدد لون النص. |
| font_family | string | قراءة/كتابة | عائلة الخط المستخدمة لعرض النص. القيمة الافتراضية تعتمد على النظام. |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | حجم النص. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | النمط المطبق على النص. |
| halo_color | System.Drawing.Color | قراءة/كتابة | لون الهالة (الحد) حول النص. |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | حجم الهالة (الحد) حول النص. |
| label_attribute | string | r/w | اسم السمة لاستخدامه كمصدر للتسميات. يتم تجاهله إذا تم تعيين [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) .<br/> إما [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) أو [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) يجب تعيينه قبل التصيير;<br/> يتم رفع استثناء InvalidOperationException خلاف ذلك. |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | يحدد سلوك التصيير للأشكال المتعددة الأجزاء. القيمة الافتراضية هي [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/). |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | يحصل على مثيل من [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | تحديد موضع التسمية يوضح كيفية وضع التسميات بالنسبة لأشكال الميزة. |
| الأولوية | int | قراءة/كتابة | يشير إلى أولوية هذه التسمية في حالة تداخلها مع تسمية أخرى. التسمية ذات الأولوية الأقل لا يتم تصييرها.<br/> القيمة الافتراضية هي 1000. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | ينسخ هذا الكائن. |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

يُنشئ مثلاً جديداً من الفئة [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

يُنشئ مثلاً جديداً من الفئة [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| label_attribute | string | اسم السمة لاستخدامه كمصدر للتسميات. |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

يُنشئ مثلاً جديداً من الفئة [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | الـ [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) الآخر لنسخ البيانات منه. |

### Method: clone() {#clone__1}


```
 clone() 
```

ينسخ هذا الكائن.

**Returns**

| نوع | وصف |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | نسخة من هذا المثيل. |


