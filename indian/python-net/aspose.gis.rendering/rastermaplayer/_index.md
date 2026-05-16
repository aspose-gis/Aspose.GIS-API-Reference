---
title: "RasterMapLayer क्लास"
type: docs
weight: 250
url: /hi/python-net/aspose.gis.rendering/rastermaplayer/
---

**Summary:** A layer inside [Map](/psd/python-net/aspose.gis.rendering/map/) that represents a raster layer data.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.RasterMapLayer

**Inheritance:** MapLayer

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [RasterMapLayer(layer, colorizer, keep_open)](#RasterMapLayer_layer_colorizer_keep_open_1) | नया इंस्टेंस बनाता है। |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | r/w | रास्टर की कोशिकाओं को रेंडर करने के लिए उपयोग किया जाने वाला कलराइज़र। |
| opacity | double | r/w | लेयर की अपारदर्शिता। |
| resampling | [RasterMapResampling](/psd/python-net/aspose.gis.rendering/rastermapresampling) | r/w | मानचित्र पर लेयर के वॉर्प विकल्प निर्दिष्ट करता है। |


### Constructor: RasterMapLayer(layer, colorizer, keep_open) {#RasterMapLayer_layer_colorizer_keep_open_1}


```
 RasterMapLayer(layer, colorizer, keep_open) 
```

नया इंस्टेंस बनाता है।

**Parameters:**

| पैरामीटर | प्रकार | विवरण |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | रास्टर लेयर। |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | लेयर को रेंडर करने के लिए उपयोग किया जाने वाला सिंबलाइज़र। यदि <see langword=\"null\" />, तो डिफ़ॉल्ट कलराइज़र उपयोग किया जाएगा। |
| keep_open | bool | <see langword=\"true\" /> लेयर को खुला रखने के लिए जब [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) ऑब्जेक्ट नष्ट हो जाए; अन्यथा, <see langword=\"false\" />। |

