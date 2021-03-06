---
title: CreateLayer
second_title: Aspose.GIS for .NET API Reference
description: 
type: docs
weight: 60
url: /net/aspose.gis.formats.filegdb/filegdbdriver/createlayer/
---
## FileGdbDriver.CreateLayer method (1 of 4)

Creates a layer and opens it for adding new features.

```csharp
public VectorLayer CreateLayer(string path, FileGdbOptions options)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Path to the file. |
| options | FileGdbOptions | Driver-specific options. |

## Return Value

An instance of [`VectorLayer`](../../../aspose.gis/vectorlayer).

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The layer already exists. |

### See Also

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [FileGdbOptions](../../filegdboptions)
* class [FileGdbDriver](../../filegdbdriver)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver)
* assembly [Aspose.GIS](../../../)

---

## FileGdbDriver.CreateLayer method (2 of 4)

Creates a layer and opens it for appending.

```csharp
public VectorLayer CreateLayer(string path, FileGdbOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Path to the file. |
| options | FileGdbOptions | Driver-specific options. |
| spatialReferenceSystem | SpatialReferenceSystem | Spatial reference system. |

## Return Value

An instance of [`VectorLayer`](../../../aspose.gis/vectorlayer).

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The layer already exists. |
| NotSupportedException | Spatial reference system is not supported by the driver. |

### See Also

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [FileGdbOptions](../../filegdboptions)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [FileGdbDriver](../../filegdbdriver)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver)
* assembly [Aspose.GIS](../../../)

---

## FileGdbDriver.CreateLayer method (3 of 4)

Creates a layer and opens it for appending.

```csharp
public override VectorLayer CreateLayer(AbstractPath path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | AbstractPath | Path to the file. |
| options | DriverOptions | Driver-specific options. |
| spatialReferenceSystem | SpatialReferenceSystem | Spatial reference system. |

## Return Value

An instance of [`VectorLayer`](../../../aspose.gis/vectorlayer).

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The layer already exists. |
| NotSupportedException | Spatial reference system is not supported by the driver. |

### See Also

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [AbstractPath](../../../aspose.gis/abstractpath)
* class [DriverOptions](../../../aspose.gis/driveroptions)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [FileGdbDriver](../../filegdbdriver)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver)
* assembly [Aspose.GIS](../../../)

---

## FileGdbDriver.CreateLayer method (4 of 4)

Creates a layer and opens it for appending.

```csharp
public VectorLayer CreateLayer(AbstractPath path, FileGdbOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | AbstractPath | Path to the file. |
| options | FileGdbOptions | Driver-specific options. |
| spatialReferenceSystem | SpatialReferenceSystem | Spatial reference system. |

## Return Value

An instance of [`VectorLayer`](../../../aspose.gis/vectorlayer).

### Exceptions

| exception | condition |
| --- | --- |
| InvalidOperationException | The layer already exists. |
| NotSupportedException | Spatial reference system is not supported by the driver. |

### See Also

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [AbstractPath](../../../aspose.gis/abstractpath)
* class [FileGdbOptions](../../filegdboptions)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [FileGdbDriver](../../filegdbdriver)
* namespace [Aspose.Gis.Formats.FileGdb](../../filegdbdriver)
* assembly [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->
