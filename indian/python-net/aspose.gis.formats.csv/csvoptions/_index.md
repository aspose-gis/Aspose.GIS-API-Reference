---
title: "CsvOptions क्लास"
type: docs
weight: 20
url: /hi/python-net/aspose.gis.formats.csv/csvoptions/
---

**Summary:** Driver-specific options for CSV format.

**Module:** [aspose.gis.formats.csv](/psd/python-net/aspose.gis.formats.csv/)

**Full Name:** aspose.gis.formats.csv.CsvOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [CsvOptions()](#CsvOptions__1) | नया उदाहरण बनाएं। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | निर्धारित करता है कि प्रत्येक ज्यामिति में अनक्लोज़्ड [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) को बंद किया जाए या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| column_m | string | r/w | कॉलम जिसमें M निर्देशांक मान है, उसका नाम प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट <see langword="null" /> है। |
| column_wkt | string | r/w | ज्यामिति को दर्शाने के लिए Well-Known Text रखने वाले कॉलम का नाम प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट <see langword="null" /> है। |
| column_x | string | r/w | X निर्देशांक मान रखने वाले कॉलम का नाम प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट <see langword="null" /> है। |
| column_y | string | r/w | Y निर्देशांक मान रखने वाले कॉलम का नाम प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट <see langword="null" /> है। |
| column_z | string | r/w | Z निर्देशांक मान रखने वाले कॉलम का नाम प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट <see langword="null" /> है। |
| create_midpoints | bool | r/w | निर्धारित करता है कि ज्यामिति के प्रत्येक खंड के मध्य में नया बिंदु जोड़ा जाए या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| delete_near_points | bool | r/w | निर्धारित करता है कि प्रत्येक ज्यामिति में निकटवर्ती बिंदुओं को हटाया जाए या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| delete_near_points_distance | double | r/w | ड्राइवर विकल्प [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/) के लिए दूरी निर्धारित करता है। डिफ़ॉल्ट <see langword="0" /> है। |
| delimiter | चर | r/w | मानों को अलग करने के लिए उपयोग किए जाने वाले विभाजक के रूप में एक अक्षर प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट ',' है। |
| double_quote_escape | चर | r/w | डबल कोट्स के लिए एस्केप अक्षर के रूप में उपयोग किए जाने वाले अक्षर को प्राप्त करता है या सेट करता है।<br/>            डिफ़ॉल्ट '"' है। |
| has_attribute_names | bool | r/w | निर्धारित करता है कि क्या विशेषता नामों वाली हेडर पंक्ति मौजूद है।<br/>            डिफ़ॉल्ट <see langword="true" /> है। |
| linearization_tolerance | double | r/w | वक्र ज्यामितियों को रैखिक बनाने के लिए उपयोग करने वाला सहनशीलता। |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | एक [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) जो M निर्देशांक पर लागू होगा<br/>            जब ज्यामितियों को [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में जोड़ा जाता है या उन्हें [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) से पढ़ा जाता है।<br/>            डिफ़ॉल्ट मान [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) है। |
| simplify_segments | bool | r/w | प्रत्येक ज्यामिति में एक ही खंड पर स्थित बिंदुओं को हटाने का निर्धारण करता है। डिफ़ॉल्ट <see langword="false" /> है। |
| simplify_segments_distance | double | r/w | ड्राइवर विकल्प [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/) के लिए दूरी निर्धारित करता है। डिफ़ॉल्ट <see langword="0" /> है। |
| start_line_number | इंट | r/w | डेटा पढ़ते समय पहली पंक्ति होगी, इसके लिए शून्य-आधारित पंक्ति संख्या को प्राप्त या सेट करता है।<br/>            डिफ़ॉल्ट 0 है। |
| validate_geometries_on_write | bool | r/w | निर्धारित करता है कि लेयर में जोड़ते समय ज्यामितियों को मान्य किया जाना चाहिए या नहीं।<br/>            यदि इसे <see langword="true" /> पर सेट किया जाता है, तो प्रत्येक ज्यामिति के लिए [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) को लेयर में जोड़ते समय कॉल किया जाता है, और यदि मान्यकरण विफल होता है ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) <see langword="false" /> है), तो [GisException](/psd/python-net/aspose.gis/gisexception/) फेंका जाता है। |
| write_polygons_as_lines | bool | r/w | निर्धारित करता है कि बहुभुज या मल्टीबहुभुज को लाइन्स्ट्रिंग में परिवर्तित करने की अनुमति है या नहीं। डिफ़ॉल्ट <see langword="false" /> है। |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | एक [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) जो X और Y निर्देशांक पर लागू होगा<br/>            जब ज्यामितियों को [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में जोड़ा जाता है या उन्हें [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) से पढ़ा जाता है।<br/>            डिफ़ॉल्ट मान [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) है। |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | एक [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) जो Z निर्देशांक पर लागू होगा<br/>            जब ज्यामितियों को [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) में जोड़ा जाता है या उन्हें [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) से पढ़ा जाता है।<br/>            डिफ़ॉल्ट मान [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/) है। |


### Constructor: CsvOptions() {#CsvOptions__1}


```
 CsvOptions() 
```

नया उदाहरण बनाएं।

