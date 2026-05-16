---
title: "TopoJsonOptions क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.gis.formats.topojson/topojsonoptions/
---

**Summary:** Driver-specific options for TopoJSON format.

**Module:** [aspose.gis.formats.topojson](/psd/python-net/aspose.gis.formats.topojson/)

**Full Name:** aspose.gis.formats.topojson.TopoJsonOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [TopoJsonOptions()](#TopoJsonOptions__1) | नया उदाहरण बनाएं। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | निर्धारित करता है कि प्रत्येक ज्यामिति में अनक्लोज़्ड [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) को बंद किया जाए या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| create_midpoints | bool | r/w | निर्धारित करता है कि ज्यामिति के प्रत्येक खंड के मध्य में नया बिंदु जोड़ा जाए या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| default_object_name | string | r/w | डिफ़ॉल्ट रूप से फीचर जहाँ रखे जाते हैं, उस ऑब्जेक्ट का नाम। |
| delete_near_points | bool | r/w | निर्धारित करता है कि प्रत्येक ज्यामिति में निकटवर्ती बिंदुओं को हटाया जाए या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| delete_near_points_distance | double | r/w | ड्राइवर विकल्प [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) के लिए दूरी निर्धारित करता है। डिफ़ॉल्ट <see langword="0" /> है। |
| linearization_tolerance | double | r/w | वक्र ज्यामितियों को रैखिक बनाने के लिए उपयोग करने वाला सहनशीलता। |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | एक [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) जो M निर्देशांक पर लागू होगा<br/>            जब ज्यामितियों को [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में जोड़ा जाता है या उन्हें [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) से पढ़ा जाता है।<br/>            डिफ़ॉल्ट मान [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) है। |
| nested_properties_separator | string | r/w | एक स्ट्रिंग प्राप्त करता है या सेट करता है जिसका उपयोग नेस्टेड एट्रिब्यूट्स के घटकों को अलग करने के लिए किया जाता है।<br/>            डिफ़ॉल्ट "_" है। |
| object_name_attribute | string | r/w | ऐसे गुण का नाम जो उस ऑब्जेक्ट के नाम को दर्शाता है जिसमें फीचर होता है। |
| quantization_number | Nullable<int> | r/w | आउटपुट TopoJSON में निर्देशांक को क्वांटाइज़ करने और आर्क्स को डेल्टा-एन्कोड करने के लिए उपयोग किए जाने वाले क्वांटाइज़ेशन नंबर को निर्दिष्ट करता है। |
| simplify_segments | bool | r/w | प्रत्येक ज्यामिति में एक ही खंड पर स्थित बिंदुओं को हटाने का निर्धारण करता है। डिफ़ॉल्ट <see langword="false" /> है। |
| simplify_segments_distance | double | r/w | ड्राइवर विकल्प [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) के लिए दूरी निर्धारित करता है। डिफ़ॉल्ट <see langword="0" /> है। |
| transform | [TopoJsonTransform](/psd/python-net/aspose.gis.formats.topojson/topojsontransform) | r/w | आउटपुट TopoJSON में निर्देशांक को क्वांटाइज़ करने और आर्क्स को डेल्टा-एन्कोड करने के लिए उपयोग किए जाने वाले ट्रांसफ़ॉर्म ऑब्जेक्ट को निर्दिष्ट करता है। |
| validate_geometries_on_write | bool | r/w | निर्धारित करता है कि लेयर में जोड़ते समय ज्यामितियों को मान्य किया जाना चाहिए या नहीं।<br/>            यदि इसे <see langword="true" /> पर सेट किया जाता है, तो प्रत्येक ज्यामिति के लिए [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) को लेयर में जोड़ते समय कॉल किया जाता है, और यदि मान्यकरण विफल होता है ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) <see langword="false" /> है), तो [GisException](/psd/python-net/aspose.gis/gisexception/) फेंका जाता है। |
| write_polygons_as_lines | bool | r/w | निर्धारित करता है कि बहुभुज या मल्टीबहुभुज को लाइन्स्ट्रिंग में परिवर्तित करने की अनुमति है या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | एक [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) जो X और Y निर्देशांक पर लागू होगा<br/>            जब ज्यामितियों को [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में जोड़ा जाता है या उन्हें [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) से पढ़ा जाता है।<br/>            डिफ़ॉल्ट मान [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) है। |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | एक [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) जो Z निर्देशांक पर लागू होगा<br/>            जब ज्यामितियों को [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में जोड़ा जाता है या उन्हें [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) से पढ़ा जाता है।<br/>            डिफ़ॉल्ट मान [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) है। |


### Constructor: TopoJsonOptions() {#TopoJsonOptions__1}


```
 TopoJsonOptions() 
```

नया उदाहरण बनाएं।

