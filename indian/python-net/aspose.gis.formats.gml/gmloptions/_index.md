---
title: "GmlOptions क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.gis.formats.gml/gmloptions/
---

**Summary:** Driver-specific options for GML format.

**Module:** [aspose.gis.formats.gml](/psd/python-net/aspose.gis.formats.gml/)

**Full Name:** aspose.gis.formats.gml.GmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [GmlOptions()](#GmlOptions__1) | नया उदाहरण बनाएं। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| application_namespace | string | r/w | यह एक कस्टम नेमस्पेस निर्दिष्ट करता है जिसे gml दस्तावेज़ उत्पन्न करने के लिए एप्लिकेशन नेमस्पेस के रूप में उपयोग किया जाएगा। |
| close_linear_ring | bool | r/w | निर्धारित करता है कि प्रत्येक ज्यामिति में अनक्लोज़्ड [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) को बंद किया जाए या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| create_midpoints | bool | r/w | निर्धारित करता है कि ज्यामिति के प्रत्येक खंड के मध्य में नया बिंदु जोड़ा जाए या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| delete_near_points | bool | r/w | निर्धारित करता है कि प्रत्येक ज्यामिति में निकटवर्ती बिंदुओं को हटाया जाए या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| delete_near_points_distance | double | r/w | ड्राइवर विकल्प [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) के लिए दूरी निर्धारित करता है। डिफ़ॉल्ट <see langword="0" /> है। |
| linearization_tolerance | double | r/w | वक्र ज्यामितियों को रैखिक बनाने के लिए उपयोग करने वाला सहनशीलता। |
| load_schemas_from_internet | bool | r/w | निर्धारित करता है कि Aspose.GIS को इंटरनेट से XML स्कीमा लोड करने की अनुमति है या नहीं।<br/>            यदि इसे <see langword=\"false\" /> पर सेट किया जाता है, तो उन स्कीमा जो 'file://' से शुरू नहीं होते हैं, लोड नहीं किए जाएंगे।<br/>            डिफ़ॉल्ट है <see langword=\"false\" />। |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | एक [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) जो M निर्देशांक पर लागू होगा<br/>            जब ज्यामितियों को [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में जोड़ा जाता है या उन्हें [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) से पढ़ा जाता है।<br/>            डिफ़ॉल्ट मान [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) है। |
| nested_properties_separator | string | r/w | एक स्ट्रिंग प्राप्त करता है या सेट करता है जिसका उपयोग नेस्टेड एट्रिब्यूट्स के घटकों को अलग करने के लिए किया जाता है।<br/>            डिफ़ॉल्ट "_" है। |
| restore_schema | bool | r/w | निर्धारित करता है कि Aspose.GIS को ऐसे Gml फ़ाइल में एट्रिब्यूट्स पार्स करने की अनुमति है जहाँ XML स्कीमा अनुपलब्ध है या लोड नहीं हो सकता।<br/>            यदि इसे <see langword=\"true\" /> पर सेट किया जाता है, तो Aspose.GIS रीडर को XML स्कीमा की आवश्यकता नहीं होगी।<br/>            डिफ़ॉल्ट है <see langword=\"false\" />। |
| schema_location | string | r/w | स्पेस द्वारा अलग की गई URI जोड़ों की सूची। प्रत्येक जोड़े में पहला URI नेमस्पेस का URI है, दूसरा URI नेमस्पेस के XML स्कीमा का पाथ है।<br/>            यदि इसे <see langword=\"null\" /> पर सेट किया जाता है, तो [GmlDriver](/psd/python-net/aspose.gis.formats.gml/gmldriver/) दस्तावेज़ के रूट एलिमेंट से schemaLocation पढ़ने का प्रयास करेगा।<br/>            डिफ़ॉल्ट है <see langword=\"null\" />। |
| simplify_segments | bool | r/w | प्रत्येक ज्यामिति में एक ही खंड पर स्थित बिंदुओं को हटाने का निर्धारण करता है। डिफ़ॉल्ट <see langword="false" /> है। |
| simplify_segments_distance | double | r/w | ड्राइवर विकल्प [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) के लिए दूरी निर्धारित करता है। डिफ़ॉल्ट <see langword="0" /> है। |
| validate_geometries_on_write | bool | r/w | निर्धारित करता है कि लेयर में जोड़ते समय ज्यामितियों को मान्य किया जाना चाहिए या नहीं।<br/>            यदि इसे <see langword="true" /> पर सेट किया जाता है, तो प्रत्येक ज्यामिति के लिए [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) को लेयर में जोड़ते समय कॉल किया जाता है, और यदि मान्यकरण विफल होता है ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) <see langword="false" /> है), तो [GisException](/psd/python-net/aspose.gis/gisexception/) फेंका जाता है। |
| write_polygons_as_lines | bool | r/w | निर्धारित करता है कि बहुभुज या मल्टीबहुभुज को लाइन्स्ट्रिंग में परिवर्तित करने की अनुमति है या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | एक [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) जो X और Y निर्देशांक पर लागू होगा<br/>            जब ज्यामितियों को [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में जोड़ा जाता है या उन्हें [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) से पढ़ा जाता है।<br/>            डिफ़ॉल्ट मान [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) है। |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | एक [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) जो Z निर्देशांक पर लागू होगा<br/>            जब ज्यामितियों को [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में जोड़ा जाता है या उन्हें [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) से पढ़ा जाता है।<br/>            डिफ़ॉल्ट मान [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) है। |


### Constructor: GmlOptions() {#GmlOptions__1}


```
 GmlOptions() 
```

नया उदाहरण बनाएं।

