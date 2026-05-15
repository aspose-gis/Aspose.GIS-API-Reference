---
title: "ImageMetadataReader.GetReader"
second_title: "Aspose.GIS for .NET API 参考"
description: "ImageMetadataReader 方法。创建用于 EXIF 标记的读取器实例"
type: docs
weight: 10
url: /zh/net/aspose.gis.imagemetadata/imagemetadatareader/getreader/
---
## GetReader(string) {#getreader_1}

创建一个用于 EXIF 标签的读取器实例

```csharp
public static ImageMetadataReader GetReader(string fileName)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| fileName | String | 图像文件的完整名称。 |

### 返回值

元数据读取器实例

## 备注

在执行读取器的 Dispose 之前，图像文件将被锁定，无法进行更改。

### 另见

* class [ImageMetadataReader](../)
* namespace [Aspose.Gis.ImageMetadata](../../imagemetadatareader/)
* assembly [Aspose.GIS](../../../)

---

## GetReader(Stream) {#getreader}

创建一个用于 EXIF 标签的读取器实例

```csharp
public static ImageMetadataReader GetReader(Stream stream)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 流 | 流 | 图像数据源流 |

### 返回值

元数据读取器实例

## 备注

在执行读取器的 Dispose 之前，重要的是不要关闭源流。

### 另见

* class [ImageMetadataReader](../)
* namespace [Aspose.Gis.ImageMetadata](../../imagemetadatareader/)
* assembly [Aspose.GIS](../../../)


