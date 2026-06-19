---
title: "ImageMetadataReader.TryGetGeoLocation"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "ImageMetadataReader 方法。它尝试查找 EXIF 中的一组标签 GPSLatitudeRef、GPSLongitudeRef、GPSLatitude、GPSLongitude，如果这些标签不存在，则返回 null"
type: docs
weight: 120
url: /zh/net/aspose.gis.imagemetadata/imagemetadatareader/trygetgeolocation/
---
## ImageMetadataReader.TryGetGeoLocation method

尝试查找 EXIF 标记集 GPSLatitudeRef、GPSLongitudeRef、GPSLatitude、GPSLongitude，如果这些标记不存在则返回 null。

```csharp
public bool TryGetGeoLocation(out GeoLocation geoLocation)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| geoLocation | GeoLocation& | 地理位置。 |

### 返回值

成功则为 True

### 另见

* class [GeoLocation](../../geolocation/)
* class [ImageMetadataReader](../)
* namespace [Aspose.Gis.ImageMetadata](../../imagemetadatareader/)
* assembly [Aspose.GIS](../../../)


