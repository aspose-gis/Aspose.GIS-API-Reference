---
title: "FileGdbCoordinatePrecisionGrid क्लास"
type: docs
weight: 10
url: /hi/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | FileGdbCoordinatePrecisionGrid क्लास का नया उदाहरण प्रारंभ करता है |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | M निर्देशांक की मूल स्थिति प्राप्त करता है या सेट करता है। यदि <see langword=\"null\" /> पर सेट किया जाता है तो डिफ़ॉल्ट उपयोग किया जाता है। |
| m_scale | Nullable<double> | r/w | M निर्देशांक का स्केल प्राप्त करता है या सेट करता है। यदि <see langword=\"null\" /> पर सेट किया जाता है तो डिफ़ॉल्ट उपयोग किया जाता है। |
| x_origin | Nullable<double> | r/w | X निर्देशांक का मूल प्राप्त करता है या सेट करता है। यदि <see langword="null" /> पर सेट किया जाता है तो डिफ़ॉल्ट उपयोग किया जाता है। |
| xy_scale | Nullable<double> | r/w | X और Y निर्देशांक के स्केल को प्राप्त करता है या सेट करता है। यदि <see langword="null" /> पर सेट किया जाता है तो डिफ़ॉल्ट उपयोग किया जाता है। |
| y_origin | Nullable<double> | r/w | Y निर्देशांक का मूल प्राप्त करता है या सेट करता है। यदि <see langword="null" /> पर सेट किया जाता है तो डिफ़ॉल्ट उपयोग किया जाता है। |
| z_origin | Nullable<double> | r/w | Z निर्देशांक का मूल प्राप्त करता है या सेट करता है। यदि <see langword="null" /> पर सेट किया जाता है तो डिफ़ॉल्ट उपयोग किया जाता है। |
| z_scale | Nullable<double> | r/w | Z निर्देशांक के स्केल को प्राप्त करता है या सेट करता है। यदि <see langword="null" /> पर सेट किया जाता है तो डिफ़ॉल्ट उपयोग किया जाता है। |
## **Methods**
| **नाम** | **विवरण** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | नया <c>FileGdbCoordinatePrecisionGrid</c> बनाता है जिससे आयत के भीतर सभी मान प्रतिनिधित्व योग्य होते हैं। |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

FileGdbCoordinatePrecisionGrid क्लास का नया उदाहरण प्रारंभ करता है

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

नया <c>FileGdbCoordinatePrecisionGrid</c> बनाता है जिससे आयत के भीतर सभी मान प्रतिनिधित्व योग्य होते हैं।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | आयत का एक कोना। |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | आयत का विपरीत कोना। इसे <paramref name="p1" /> के समान आयाम होना चाहिए। |

**Returns**

| प्रकार | विवरण |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | यह <c>FileGdbCoordinatePrecisionGrid</c> है जिससे आयत के भीतर सभी मान प्रतिनिधित्व योग्य होते हैं।<br/>            आयत के बाहर के मान प्रतिनिधित्व योग्य नहीं होते, इसलिए सभी निर्देशांक जो FileGDB लेयर में लिखे जाएंगे<br/>            आयत के भीतर ही होने चाहिए। |


