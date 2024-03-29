---
title: Class PostGisOptions
second_title: .NET API संदर्भ के लिए Aspose.GIS
description: Aspose.Gis.Formats.PostGis.PostGisOptions कक्ष. पस्टजस प्ररूप के लए ड्रइवरवशष्ट वकल्प फलहल ड्रइवर कई अनुकूलन यग्य वकल्प प्रदन नहं करत है
type: docs
weight: 650
url: /hi/net/aspose.gis.formats.postgis/postgisoptions/
---
## PostGisOptions class

पोस्टजीस प्रारूप के लिए ड्राइवर-विशिष्ट विकल्प। फिलहाल, ड्राइवर कोई अनुकूलन योग्य विकल्प प्रदान नहीं करता है।

```csharp
public class PostGisOptions : DatabaseDriverOptions
```

## कंस्ट्रक्टर्स

| नाम | विवरण |
| --- | --- |
| [PostGisOptions](postgisoptions/)() | नया उदाहरण बनाएँ। |

## गुण

| नाम | विवरण |
| --- | --- |
| [CloseLinearRing](../../aspose.gis/driveroptions/closelinearring/) { get; set; } | निर्धारित करता है कि बंद है या नहींLinearRing प्रत्येक ज्यामिति में। करने के लिए चूक`false` . |
| [CreateMidpoints](../../aspose.gis/driveroptions/createmidpoints/) { get; set; } | निर्धारित करता है कि ज्यामिति के प्रत्येक खंड के बीच में एक नया बिंदु जोड़ें या नहीं। करने के लिए चूक`false` . |
| [DeleteNearPoints](../../aspose.gis/driveroptions/deletenearpoints/) { get; set; } | निर्धारित करता है कि प्रत्येक ज्यामिति में निकट बिंदु हटाएं या नहीं। करने के लिए चूक`false` . |
| [DeleteNearPointsDistance](../../aspose.gis/driveroptions/deletenearpointsdistance/) { get; set; } | के लिए दूरी निर्धारित करता है[`DeleteNearPoints`](../../aspose.gis/driveroptions/deletenearpoints/) . करने के लिए चूक`0` . |
| [LinearizationTolerance](../../aspose.gis/driveroptions/linearizationtolerance/) { get; set; } | वक्र ज्यामिति को रैखिक करने के लिए उपयोग करने के लिए एक सहिष्णुता। |
| [MPrecisionModel](../../aspose.gis/driveroptions/mprecisionmodel/) { get; set; } | ए[`PrecisionModel`](../../aspose.gis/precisionmodel/) जो M निर्देशांक पर लागू किया जाएगा जब ज्यामिति को इसमें जोड़ा जाएगा[`VectorLayer`](../../aspose.gis/vectorlayer/) या जब वे से पढ़ा जाता है[`VectorLayer`](../../aspose.gis/vectorlayer/) . डिफ़ॉल्ट मान है[`Exact`](../../aspose.gis/precisionmodel/exact/) . |
| [SimplifySegments](../../aspose.gis/driveroptions/simplifysegments/) { get; set; } | निर्धारित करता है कि प्रत्येक ज्यामिति में एक ही खंड पर स्थित बिंदुओं को हटाएं या नहीं। करने के लिए चूक`false` . |
| [SimplifySegmentsDistance](../../aspose.gis/driveroptions/simplifysegmentsdistance/) { get; set; } | के लिए दूरी निर्धारित करता है[`SimplifySegments`](../../aspose.gis/driveroptions/simplifysegments/) . करने के लिए चूक`0` . |
| [SpatialReferenceSystemMode](../../aspose.gis/databasedriveroptions/spatialreferencesystemmode/) { get; set; } | यह निर्धारित करता है कि जब वे परत में जोड़े जाते हैं तो डेटाबेस के लिए अज्ञात ज्यामिति के SRS को कैसे संभालना चाहिए। डिफ़ॉल्ट मान हैThrowException . |
| [ValidateGeometriesOnWrite](../../aspose.gis/driveroptions/validategeometriesonwrite/) { get; set; } | यह निर्धारित करता है कि क्या ज्यामिति को परत में जोड़े जाने पर मान्य किया जाना चाहिए। यदि पर सेट किया गया है`true` ,[`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) प्रत्येक ज्यामिति के लिए कहा जाता है जब इसे परत में जोड़ा जाता है, और यदि सत्यापन विफल हो जाता है ([`IsValid`](../../aspose.gis.geometries/geometry/isvalid/) है`false` ),[`GisException`](../../aspose.gis/gisexception/) फेंक दिया जाता है। |
| [WritePolygonsAsLines](../../aspose.gis/driveroptions/writepolygonsaslines/) { get; set; } | यह निर्धारित करता है कि बहुभुज या बहुबहुभुज को लिनेस्ट्रिंग में बदलने की अनुमति है या नहीं। करने के लिए चूक`false` . |
| [XYPrecisionModel](../../aspose.gis/driveroptions/xyprecisionmodel/) { get; set; } | ए[`PrecisionModel`](../../aspose.gis/precisionmodel/) जो X और Y निर्देशांकों पर लागू होगा, जब ज्यामिति को इसमें जोड़ा जाएगा[`VectorLayer`](../../aspose.gis/vectorlayer/) या जब वे से पढ़ा जाता है[`VectorLayer`](../../aspose.gis/vectorlayer/) . डिफ़ॉल्ट मान है[`Exact`](../../aspose.gis/precisionmodel/exact/) . |
| [ZPrecisionModel](../../aspose.gis/driveroptions/zprecisionmodel/) { get; set; } | ए[`PrecisionModel`](../../aspose.gis/precisionmodel/) जो Z निर्देशांक पर तब लागू होगा जब ज्यामिति को इसमें जोड़ा जाएगा[`VectorLayer`](../../aspose.gis/vectorlayer/) या जब वे से पढ़ा जाता है[`VectorLayer`](../../aspose.gis/vectorlayer/) . डिफ़ॉल्ट मान है[`Exact`](../../aspose.gis/precisionmodel/exact/) . |

### यह सभी देखें

* class [DatabaseDriverOptions](../../aspose.gis/databasedriveroptions/)
* नाम स्थान [Aspose.Gis.Formats.PostGis](../../aspose.gis.formats.postgis/)
* सभा [Aspose.GIS](../../)


