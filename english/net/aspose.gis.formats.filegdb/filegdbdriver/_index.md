---
title: FileGdbDriver
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 230
url: /net/aspose.gis.formats.filegdb/filegdbdriver/
---
## FileGdbDriver class

A driver for the ESRI File Geodatabase format.

```csharp
public sealed class FileGdbDriver : FileDriver
```

## Properties

| Name | Description |
| --- | --- |
| override [CanCreateDatasets](../../aspose.gis.formats.filegdb/filegdbdriver/cancreatedatasets) { get; } | Gets a value indicating whether this driver can create datasets. |
| override [CanCreateLayers](../../aspose.gis.formats.filegdb/filegdbdriver/cancreatelayers) { get; } | Gets a value indicating whether this driver can create vector layers. |
| override [CanOpenDatasets](../../aspose.gis.formats.filegdb/filegdbdriver/canopendatasets) { get; } | Gets a value indicating whether this driver can open datasets. |
| override [CanOpenLayers](../../aspose.gis.formats.filegdb/filegdbdriver/canopenlayers) { get; } | Gets a value indicating whether this driver can open vector layers. |

## Methods

| Name | Description |
| --- | --- |
| [CreateDataset](../../aspose.gis/filedriver/createdataset)(AbstractPath) | Creates a dataset. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset)(string) | Creates a dataset. |
| override [CreateDataset](../../aspose.gis.formats.filegdb/filegdbdriver/createdataset)(AbstractPath, DriverOptions) | Creates a dataset. |
| [CreateDataset](../../aspose.gis.formats.filegdb/filegdbdriver/createdataset)(AbstractPath, FileGdbOptions) | Creates a dataset. |
| [CreateDataset](../../aspose.gis/filedriver/createdataset)(string, DriverOptions) | Creates a dataset. |
| [CreateDataset](../../aspose.gis.formats.filegdb/filegdbdriver/createdataset)(string, FileGdbOptions) | Creates a dataset. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(AbstractPath) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(AbstractPath, DriverOptions) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(AbstractPath, SpatialReferenceSystem) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string, DriverOptions) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis.formats.filegdb/filegdbdriver/createlayer)(string, FileGdbOptions) | Creates a layer and opens it for adding new features. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string, SpatialReferenceSystem) | Creates the layer and opens it for appending. |
| override [CreateLayer](../../aspose.gis.formats.filegdb/filegdbdriver/createlayer)(AbstractPath, DriverOptions, SpatialReferenceSystem) | Creates a layer and opens it for appending. |
| [CreateLayer](../../aspose.gis.formats.filegdb/filegdbdriver/createlayer)(AbstractPath, FileGdbOptions, SpatialReferenceSystem) | Creates a layer and opens it for appending. |
| [CreateLayer](../../aspose.gis/filedriver/createlayer)(string, DriverOptions, SpatialReferenceSystem) | Creates the layer and opens it for appending. |
| [CreateLayer](../../aspose.gis.formats.filegdb/filegdbdriver/createlayer)(string, FileGdbOptions, SpatialReferenceSystem) | Creates a layer and opens it for appending. |
| virtual [EditLayer](../../aspose.gis/filedriver/editlayer)(AbstractPath, DriverOptions) | Opens a layer for editing. |
| [EditLayer](../../aspose.gis/filedriver/editlayer)(string, DriverOptions) | Opens a layer for editing. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset)(AbstractPath) | Opens the dataset. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset)(string) | Opens the dataset. |
| override [OpenDataset](../../aspose.gis.formats.filegdb/filegdbdriver/opendataset)(AbstractPath, DriverOptions) | Opens the dataset. |
| [OpenDataset](../../aspose.gis.formats.filegdb/filegdbdriver/opendataset)(AbstractPath, FileGdbOptions) | Opens the dataset. |
| [OpenDataset](../../aspose.gis/filedriver/opendataset)(string, DriverOptions) | Opens the dataset. |
| [OpenDataset](../../aspose.gis.formats.filegdb/filegdbdriver/opendataset)(string, FileGdbOptions) | Opens the dataset. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer)(AbstractPath) | Opens the layer for reading. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer)(string) | Opens the layer for reading. |
| override [OpenLayer](../../aspose.gis.formats.filegdb/filegdbdriver/openlayer)(AbstractPath, DriverOptions) | Opens a layer for reading. |
| [OpenLayer](../../aspose.gis.formats.filegdb/filegdbdriver/openlayer)(AbstractPath, FileGdbOptions) | Opens a layer for reading. |
| [OpenLayer](../../aspose.gis/filedriver/openlayer)(string, DriverOptions) | Opens the layer for reading. |
| [OpenLayer](../../aspose.gis.formats.filegdb/filegdbdriver/openlayer)(string, FileGdbOptions) | Opens a layer for reading. |
| override [SupportsSpatialReferenceSystem](../../aspose.gis.formats.filegdb/filegdbdriver/supportsspatialreferencesystem)(SpatialReferenceSystem) | Determines, whether specified spatial reference system is supported by the driver. |

### See Also

* class [FileDriver](../../aspose.gis/filedriver)
* namespace [Aspose.Gis.Formats.FileGdb](../../aspose.gis.formats.filegdb)
* assembly [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
