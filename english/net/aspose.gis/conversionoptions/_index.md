---
title: ConversionOptions
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 40
url: /net/aspose.gis/conversionoptions/
---
## ConversionOptions class

Options for converting data between formats.

```csharp
public class ConversionOptions
```

## Constructors

| Name | Description |
| --- | --- |
| [ConversionOptions](conversionoptions)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| [AttributesConverter](attributesconverter) { get; set; } | A custom converter for attributes. It allows us to rename or exclude destination attributes. If not `null`, it is called for each attribute of the source layer and is expected to change it if necessary. |
| [DestinationDriverOptions](destinationdriveroptions) { get; set; } | Driver-specific options for the destination layer. |
| [DestinationSpatialReferenceSystem](destinationspatialreferencesystem) { get; set; } | Spatial reference system to assign to destination layer. |
| [SourceDriverOptions](sourcedriveroptions) { get; set; } | Driver-specific options for the source layer. |

### See Also

* namespace [Aspose.Gis](../../aspose.gis)
* assembly [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->