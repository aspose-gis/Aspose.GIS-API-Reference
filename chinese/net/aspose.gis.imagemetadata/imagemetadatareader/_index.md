---
title: "类 ImageMetadataReader"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.ImageMetadata.ImageMetadataReader 类。用于编辑添加某些 EXIF 标记的类"
type: docs
weight: 3080
url: /zh/net/aspose.gis.imagemetadata/imagemetadatareader/
---
## ImageMetadataReader class

用于编辑、添加某些 EXIF 标签的类

```csharp
public class ImageMetadataReader : IDisposable
```

## 方法

| 名称 | 描述 |
| --- | --- |
| static [GetReader](../../aspose.gis.imagemetadata/imagemetadatareader/getreader/#getreader)(Stream) | 创建一个用于 EXIF 标记的读取器实例 |
| static [GetReader](../../aspose.gis.imagemetadata/imagemetadatareader/getreader/#getreader_1)(string) | 创建一个用于 EXIF 标记的读取器实例 |
| [Dispose](../../aspose.gis.imagemetadata/imagemetadatareader/dispose/)() | 供消费者调用的 Dispose 模式的公共实现。 |
| [ReadData](../../aspose.gis.imagemetadata/imagemetadatareader/readdata/)() | 提取所有受支持的 EXIF 标记 |
| [Save](../../aspose.gis.imagemetadata/imagemetadatareader/save/#save)(Stream) | 将更改保存到单独的流 |
| [Save](../../aspose.gis.imagemetadata/imagemetadatareader/save/#save_2)(string) | 保存到新文件，因为原文件已锁定，无法更改 |
| [Save](../../aspose.gis.imagemetadata/imagemetadatareader/save/#save_1)(Stream, ImageFormat) | 将更改保存到单独的流 |
| [Save](../../aspose.gis.imagemetadata/imagemetadatareader/save/#save_3)(string, ImageFormat) | 保存到新文件，因为原文件已锁定，无法更改 |
| [SetArtist](../../aspose.gis.imagemetadata/imagemetadatareader/setartist/)(string) | 保存 EXIF Artist 标记，添加或覆盖数据。 |
| [SetDescription](../../aspose.gis.imagemetadata/imagemetadatareader/setdescription/)(string) | 保存 EXIF ImageDescription 标记，添加或覆盖数据。 |
| [SetGeoLocation](../../aspose.gis.imagemetadata/imagemetadatareader/setgeolocation/)(double, double) | 保存 EXIF GPSLatitudeRef、GPSLongitudeRef、GPSLatitude 和 GPSLongitude 标记，添加或覆盖数据。 |
| [SetImageSize](../../aspose.gis.imagemetadata/imagemetadatareader/setimagesize/)(int, int) | 保存 EXIF ImageWidth 和 ImageHeight 标记，添加或覆盖数据。 |
| [SetModifyDate](../../aspose.gis.imagemetadata/imagemetadatareader/setmodifydate/)(DateTime) | 保存 EXIF ModifyDate (DataTime) 标记，添加或覆盖数据。 |
| [TryGetArtist](../../aspose.gis.imagemetadata/imagemetadatareader/trygetartist/)(out string) | 尝试查找 EXIF 标记 Artist，如果未找到该标记则返回 null。 |
| [TryGetDescription](../../aspose.gis.imagemetadata/imagemetadatareader/trygetdescription/)(out string) | 尝试查找 EXIF 标记 ImageDescription，如果未找到该标记则返回 null。 |
| [TryGetGeoLocation](../../aspose.gis.imagemetadata/imagemetadatareader/trygetgeolocation/)(out GeoLocation) | 尝试查找 EXIF 标记集 GPSLatitudeRef、GPSLongitudeRef、GPSLatitude、GPSLongitude，如果这些标记不存在则返回 null。 |
| [TryGetImageSize](../../aspose.gis.imagemetadata/imagemetadatareader/trygetimagesize/)(out ImageSize) | 尝试查找 EXIF 标记集 ImageWidth 和 ImageHeight，如果这些标记不存在则返回 null。 |
| [TryGetModifyDate](../../aspose.gis.imagemetadata/imagemetadatareader/trygetmodifydate/)(out DateTime) | 尝试查找 EXIF 标记 ModifyDate (DataTime)，如果未找到该标记则返回默认的 DataTime 值。 |

### 另见

* namespace [Aspose.Gis.ImageMetadata](../../aspose.gis.imagemetadata/)
* assembly [Aspose.GIS](../../)


