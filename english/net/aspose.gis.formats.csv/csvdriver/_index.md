---
title: CsvDriver
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 180
url: /net/aspose.gis.formats.csv/csvdriver/
---
## CsvDriver class

A driver for the CSV format.

```csharp
public class CsvDriver : FileDriver
```

## Constructors

| Name | Description |
| --- | --- |
| [CsvDriver](csvdriver)() | The default constructor. |

## Properties

| Name | Description |
| --- | --- |
| override [CanCreateDatasets](../../aspose.gis.formats.csv/csvdriver/cancreatedatasets) { get; } | Gets a value indicating whether this driver can create datasets. |
| override [CanCreateLayers](../../aspose.gis.formats.csv/csvdriver/cancreatelayers) { get; } | Gets a value indicating whether this driver can create vector layers. |
| virtual [CanOpenDatasets](../../aspose.gis/filedriver/canopendatasets) { get; } | Gets a value indicating whether this driver can open datasets. |
| override [CanOpenLayers](../../aspose.gis.formats.csv/csvdriver/canopenlayers) { get; } | Gets a value indicating whether this driver can open vector layers. |

## Methods

| Name | Description |
| --- | --- |
| [CreateDataset](../../aspose.gis/filedriver/createdataset)(AbstractPath) | Creates a dataset. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset)(string) | Creates a dataset. |
| virtual [CreateDataset](../../aspose.gis/filedriver/createdataset)(AbstractPath, DriverOptions) | Creates a dataset. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset)(string, DriverOptions) | Creates a dataset. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(AbstractPath) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis.formats.csv/csvdriver/createlayer)(AbstractPath, CsvOptions) | Creates a layer and opens it for adding new features. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(AbstractPath, DriverOptions) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(AbstractPath, SpatialReferenceSystem) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis.formats.csv/csvdriver/createlayer)(string, CsvOptions) | Creates a layer and opens it for adding new features. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string, DriverOptions) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string, SpatialReferenceSystem) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis.formats.csv/csvdriver/createlayer)(AbstractPath, CsvOptions, SpatialReferenceSystem) | Creates a layer and opens it for adding new features. |
| override [CreateLayer](../../aspose.gis.formats.csv/csvdriver/createlayer)(AbstractPath, DriverOptions, SpatialReferenceSystem) | Creates a layer and opens it for adding new features. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string, DriverOptions, SpatialReferenceSystem) | Creates the layer and opens it for appending. |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer)(AbstractPath, DriverOptions) | Opens a layer for editing. |
| [EditLayer](../../aspose.gis/filedriver/editlayer)(string, DriverOptions) | Opens a layer for editing. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset)(AbstractPath) | Opens the dataset. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset)(string) | Opens the dataset. |
| virtual [OpenDataset](../../aspose.gis/filedriver/opendataset)(AbstractPath, DriverOptions) | Opens the dataset. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset)(string, DriverOptions) | Opens the dataset. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer)(AbstractPath) | Opens the layer for reading. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer)(string) | Opens the layer for reading. |
| [OpenLayer](../../aspose.gis.formats.csv/csvdriver/openlayer)(AbstractPath, CsvOptions) | Opens a layer for reading. |
| override [OpenLayer](../../aspose.gis.formats.csv/csvdriver/openlayer)(AbstractPath, DriverOptions) | Opens a layer for reading. |
| [OpenLayer](../../aspose.gis.formats.csv/csvdriver/openlayer)(string, CsvOptions) | Opens a layer for reading. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer)(string, DriverOptions) | Opens the layer for reading. |
| override [SupportsSpatialReferenceSystem](../../aspose.gis.formats.csv/csvdriver/supportsspatialreferencesystem)(SpatialReferenceSystem) | Determines, whether specified spatial reference system is supported by the driver. |

### See Also

* class [FileDriver](../../aspose.gis/filedriver)
* namespace [Aspose.Gis.Formats.Csv](../../aspose.gis.formats.csv)
* assembly [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
