---
title: "ConversionOptions-klass"
type: docs
weight: 380
url: /sv/python-net/aspose.gis/conversionoptions/
---

**Summary:** Options for converting data between formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.ConversionOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Beskrivning** |
| :- | :- |
| [ConversionOptions()](#ConversionOptions__1) | Initierar en ny instans av ConversionOptions-klass |
## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| attributes_converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | r/w | En anpassad konverterare för attribut. Den låter oss byta namn på eller utesluta destinationsattribut.<br/>            Om inte <see langword="null" />, anropas den för varje attribut i källskiktet och förväntas ändra det vid behov. |
| destination_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | Drivrutinsspecifika alternativ för destinationslagret. |
| destination_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | Rumsligt referenssystem att tilldela destinationslagret. |
| source_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | Drivrutinsspecifika alternativ för källlagret. |


### Constructor: ConversionOptions() {#ConversionOptions__1}


```
 ConversionOptions() 
```

Initierar en ny instans av ConversionOptions-klass

