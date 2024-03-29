---
title: FileDriver.EditLayer
second_title: Aspose.GIS for .NET API Reference
description: FileDriver method. Opens a layer for editing
type: docs
weight: 70
url: /net/aspose.gis/filedriver/editlayer/
---
## EditLayer(string, DriverOptions) {#editlayer_1}

Opens a layer for editing.

```csharp
public VectorLayer EditLayer(string path, DriverOptions options = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | String | Path to the file. |
| options | DriverOptions | Driver-specific options. |

### Return Value

An instance of [`VectorLayer`](../../vectorlayer/).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Options object has an incorrect type for this driver. |
| ArgumentNullException | The path is `null`. |
| [GisException](../../gisexception/) | Error reading the feature from the file. |
| IOException | An I/O error occurred. |

### See Also

* class [VectorLayer](../../vectorlayer/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)

---

## EditLayer(AbstractPath, DriverOptions) {#editlayer}

Opens a layer for editing.

```csharp
public virtual VectorLayer EditLayer(AbstractPath path, DriverOptions options = null)
```

| Parameter | Type | Description |
| --- | --- | --- |
| path | AbstractPath | Path to the file. |
| options | DriverOptions | Driver-specific options. |

### Return Value

An instance of [`VectorLayer`](../../vectorlayer/).

### Exceptions

| exception | condition |
| --- | --- |
| ArgumentException | Options object has an incorrect type for this driver. |
| ArgumentNullException | The path is `null`. |
| [GisException](../../gisexception/) | Error reading the feature from the file. |
| NotSupportedException | Driver can not edit layers. |
| IOException | An I/O error occurred. |

## Remarks

The driver creates an inner layer with all the features. But we have the option to use disk space instead RAM. There are drivers for more optimal use of resources (see the specific driver documentation). Also the driver can edit a layer If it can create and open the layers.

### See Also

* class [VectorLayer](../../vectorlayer/)
* class [AbstractPath](../../abstractpath/)
* class [DriverOptions](../../driveroptions/)
* class [FileDriver](../)
* namespace [Aspose.Gis](../../filedriver/)
* assembly [Aspose.GIS](../../../)


