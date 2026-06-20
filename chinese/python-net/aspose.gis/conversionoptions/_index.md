---
title: "ConversionOptions 类"
type: docs
weight: 380
url: /zh/python-net/aspose.gis/conversionoptions/
---

**Summary:** Options for converting data between formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.ConversionOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [ConversionOptions()](#ConversionOptions__1) | 初始化 ConversionOptions 类的新实例 |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes_converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | r/w | 属性的自定义转换器。它允许我们重命名或排除目标属性。<br/>            如果不为 <see langword="null" />，则会针对源图层的每个属性调用它，并在必要时对其进行更改。 |
| destination_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | 针对目标图层的驱动程序特定选项。 |
| destination_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 分配给目标图层的空间参考系统。 |
| source_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | 针对源图层的驱动程序特定选项。 |


### Constructor: ConversionOptions() {#ConversionOptions__1}


```
 ConversionOptions() 
```

初始化 ConversionOptions 类的新实例

