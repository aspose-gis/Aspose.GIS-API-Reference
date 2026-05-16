---
title: "SimpleLabeling Class"
type: docs
weight: 80
url: /hi/python-net/aspose.gis.rendering.labelings/simplelabeling/
---

**Summary:** A simple labeling places label on every feature.

**Module:** [aspose.gis.rendering.labelings](/psd/python-net/aspose.gis.rendering.labelings/)

**Full Name:** aspose.gis.rendering.labelings.SimpleLabeling

**Inheritance:** Labeling

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [SimpleLabeling()](#SimpleLabeling__1) | एक नया उदाहरण प्रारंभ करता है [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) क्लास का। |
| [SimpleLabeling(label_attribute)](#SimpleLabeling_label_attribute_2) | एक नया उदाहरण प्रारंभ करता है [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) क्लास का। |
| [SimpleLabeling(other)](#SimpleLabeling_other_3) | एक नया उदाहरण प्रारंभ करता है [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) क्लास का। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| font_color | System.Drawing.Color | r/w | पाठ का रंग निर्धारित करता है। |
| font_family | string | r/w | पाठ को रेंडर करने के लिए उपयोग किया जाने वाला फ़ॉन्ट परिवार। डिफ़ॉल्ट सिस्टम-निर्भर मान है। |
| font_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Size of the text. |
| font_style | [FontStyle](/psd/python-net/aspose.gis.rendering.labelings/fontstyle) | r/w | Style to apply to text. |
| halo_color | System.Drawing.Color | r/w | पाठ के चारों ओर हैलो (स्ट्रोक) का रंग। |
| halo_size | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | पाठ के चारों ओर हैलो (स्ट्रोक) का आकार। |
| label_attribute | string | r/w | लेबल्स के स्रोत के रूप में उपयोग करने के लिए गुण का नाम। यदि [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) सेट है तो इसे अनदेखा किया जाता है।<br/>            या तो [SimpleLabeling.label_attribute](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) या [None](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) को रेंडरिंग से पहले सेट किया जाना चाहिए;<br/>            अन्यथा InvalidOperationException फेंका जाता है। |
| multipart_mode | [MultipartMode](/psd/python-net/aspose.gis.rendering.labelings/multipartmode) | r/w | मल्टीपार्ट ज्योमेट्रीज़ के लिए रेंडरिंग व्यवहार निर्दिष्ट करता है। डिफ़ॉल्ट है [MultipartMode.ALL](/psd/python-net/aspose.gis.rendering.labelings/multipartmode/)। |
| null [static] | [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling) | r | एक इंस्टेंस प्राप्त करता है [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/). |
| placement | [LabelPlacement](/psd/python-net/aspose.gis.rendering.labelings/labelplacement) | r/w | लेबल प्लेसमेंट यह निर्दिष्ट करता है कि लेबल्स फीचर की ज्योमेट्रीज़ के सापेक्ष कैसे रखे जाते हैं। |
| प्राथमिकता | इंट | r/w | यदि यह लेबल किसी अन्य लेबल के साथ ओवरलैप करता है तो इसकी प्राथमिकता दर्शाता है। कम प्राथमिकता वाला लेबल रेंडर नहीं किया जाता।<br/>            डिफ़ॉल्ट 1000 है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [clone()](#clone__1) | इस उदाहरण की प्रतिलिपि बनाता है। |


### Constructor: SimpleLabeling() {#SimpleLabeling__1}


```
 SimpleLabeling() 
```

एक नया उदाहरण प्रारंभ करता है [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) क्लास का।

### Constructor: SimpleLabeling(label_attribute) {#SimpleLabeling_label_attribute_2}


```
 SimpleLabeling(label_attribute) 
```

एक नया उदाहरण प्रारंभ करता है [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| label_attribute | string | लेबल्स के स्रोत के रूप में उपयोग करने के लिए गुण का नाम। |

### Constructor: SimpleLabeling(other) {#SimpleLabeling_other_3}


```
 SimpleLabeling(other) 
```

एक नया उदाहरण प्रारंभ करता है [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/) क्लास का।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| other | [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | डेटा कॉपी करने के लिए अन्य [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling/)। |

### Method: clone() {#clone__1}


```
 clone() 
```

इस उदाहरण की प्रतिलिपि बनाता है।

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [SimpleLabeling](/psd/python-net/aspose.gis.rendering.labelings/simplelabeling) | इस इंस्टेंस की एक क्लोन। |


