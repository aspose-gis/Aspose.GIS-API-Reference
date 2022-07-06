---
title: CreateLayer
second_title: Aspose.GIS for .NET API 参考
description: 创建一个图层并打开它以添加新功能
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.mapinfointerchange/mapinfointerchangedriver/createlayer/
---
## CreateLayer(string, MapInfoInterchangeOptions) {#createlayer_7}

创建一个图层并打开它以添加新功能。

```csharp
public VectorLayer CreateLayer(string path, MapInfoInterchangeOptions options)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件路径。 |
| options | MapInfoInterchangeOptions | 驱动程序特定选项。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer)的一个实例。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 层已经存在。 |

### 也可以看看

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [MapInfoInterchangeOptions](../../mapinfointerchangeoptions)
* class [MapInfoInterchangeDriver](../../mapinfointerchangedriver)
* 命名空间 [Aspose.Gis.Formats.MapInfoInterchange](../../mapinfointerchangedriver)
* 部件 [Aspose.GIS](../../../)

---

## CreateLayer(AbstractPath, DriverOptions, SpatialReferenceSystem) {#createlayer_2}

创建一个图层并打开它以添加新功能。

```csharp
public override VectorLayer CreateLayer(AbstractPath path, DriverOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | AbstractPath | 文件路径。 |
| options | DriverOptions | 驱动程序特定选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer)的一个实例。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 层已经存在。 |

### 也可以看看

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [AbstractPath](../../../aspose.gis/abstractpath)
* class [DriverOptions](../../../aspose.gis/driveroptions)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [MapInfoInterchangeDriver](../../mapinfointerchangedriver)
* 命名空间 [Aspose.Gis.Formats.MapInfoInterchange](../../mapinfointerchangedriver)
* 部件 [Aspose.GIS](../../../)

---

## CreateLayer(string, MapInfoInterchangeOptions, SpatialReferenceSystem) {#createlayer_8}

创建一个图层并打开它以添加新功能。

```csharp
public VectorLayer CreateLayer(string path, MapInfoInterchangeOptions options, 
    SpatialReferenceSystem spatialReferenceSystem)
```

| 范围 | 类型 | 描述 |
| --- | --- | --- |
| path | String | 文件路径。 |
| options | MapInfoInterchangeOptions | 驱动程序特定选项。 |
| spatialReferenceSystem | SpatialReferenceSystem | 空间参考系统。 |

### 返回值

[`VectorLayer`](../../../aspose.gis/vectorlayer)的一个实例。

### 例外

| 例外 | （健康）状况 |
| --- | --- |
| InvalidOperationException | 层已经存在。 |
| NotSupportedException | 驱动程序不支持空间参考系统。 |

### 也可以看看

* class [VectorLayer](../../../aspose.gis/vectorlayer)
* class [MapInfoInterchangeOptions](../../mapinfointerchangeoptions)
* class [SpatialReferenceSystem](../../../aspose.gis.spatialreferencing/spatialreferencesystem)
* class [MapInfoInterchangeDriver](../../mapinfointerchangedriver)
* 命名空间 [Aspose.Gis.Formats.MapInfoInterchange](../../mapinfointerchangedriver)
* 部件 [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->