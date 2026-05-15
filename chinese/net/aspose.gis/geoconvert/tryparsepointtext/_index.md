---
title: "GeoConvert.TryParsePointText"
second_title: "Aspose.GIS for .NET API 参考"
description: "GeoConvert 方法。将包含坐标的字符串转换为 IPoint 对象。返回值指示转换是成功还是失败。"
type: docs
weight: 30
url: /zh/net/aspose.gis/geoconvert/tryparsepointtext/
---
## GeoConvert.TryParsePointText method

将包含坐标的字符串转换为 IPoint 对象。返回值指示转换是成功还是失败。

```csharp
public static bool TryParsePointText(string text, out IPoint point)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | String | 一个包含待转换坐标的字符串。该字符串应同时包含纬度和经度坐标。坐标应以空格、逗号或分号分隔。 |
| 点 | IPoint& | 当此方法返回时，若转换成功，则包含解析后的坐标 IPoint 对象；若转换失败，则为 null。 |

### 返回值

若文本解析成功则为 True，否则为 False。

## 备注

示例：\"80° 151°\", \"74°50.82', 172°08.21'\", \"80°;151°\", \"2CMB\", \"2CMB6682893142\", \"2C MB 66828 93142\", \"WMAQ12405535\"。

### 另见

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [GeoConvert](../)
* namespace [Aspose.Gis](../../geoconvert/)
* assembly [Aspose.GIS](../../../)


