---
title: "MapOptions क्लास"
type: docs
weight: 30
url: /hi/python-net/aspose.gis.geotools.layersmap/mapoptions/
---

**Summary:** Map Options for creating maps using [LayersMapBuilder](/psd/python-net/aspose.gis.geotools.layersmap/layersmapbuilder/)

**Module:** [aspose.gis.geotools.layersmap](/psd/python-net/aspose.gis.geotools.layersmap/)

**Full Name:** aspose.gis.geotools.layersmap.MapOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **नाम** | **विवरण** |
| :- | :- |
| [MapOptions()](#MapOptions__1) | MapOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है |
## **Properties**
| **नाम** | **प्रकार** | **पहुँच** | **विवरण** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | मानचित्र की पृष्ठभूमि रंग। डिफ़ॉल्ट System.Drawing.Color.Transparent है। |
| height | int | r/w | मानचित्र की दृश्य ऊँचाई। डिफ़ॉल्ट 400 है। जब [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) उपयोग किया जाता है। |
| layers | [MapLayerOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maplayeroptions) | r/w | Aspose.Gis.GeoTools.LayersMap.MapLayerOptions द्वारा प्रस्तुत वेक्टर लेयर्स के विकल्पों का संग्रह। |
| rasters | [MapRasterOptions[]](/psd/python-net/aspose.gis.geotools.layersmap/maprasteroptions) | r/w | Aspose.Gis.GeoTools.LayersMap.MapRasterOptions द्वारा प्रस्तुत रास्टर लेयर्स के विकल्पों का संग्रह। |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer/) | r/w | उपयोग करने के लिए रेंडरर। डिफ़ॉल्ट Aspose.Gis.Rendering.Renders.Jpeg है। |
| size_mode | [MapSizeModes](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes) | r/w | आकार मोड। डिफ़ॉल्ट [MapSizeModes.AUTO](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) है। |
| spatial_reference | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | स्पैशियल रेफ़रेंस। डिफ़ॉल्ट Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.WebMercator है। |
| tiles | [MapTilesOptions](/psd/python-net/aspose.gis.geotools.layersmap/maptilesoptions) | r/w | टाइल्स विकल्प। |
| width | int | r/w | मानचित्र की दृश्य चौड़ाई। डिफ़ॉल्ट 400 है। जब [MapSizeModes.CUSTOM](/psd/python-net/aspose.gis.geotools.layersmap/mapsizemodes/) उपयोग किया जाता है। |


### Constructor: MapOptions() {#MapOptions__1}


```
 MapOptions() 
```

MapOptions क्लास का नया इंस्टेंस इनिशियलाइज़ करता है

