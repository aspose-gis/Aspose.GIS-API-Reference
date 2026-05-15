---
title: "GeoConvert.ParsePointText"
second_title: "Aspose.GIS for .NET API 参考"
description: "GeoConvert 方法。将包含坐标的字符串转换为 IPoint 对象。"
type: docs
weight: 20
url: /zh/net/aspose.gis/geoconvert/parsepointtext/
---
## GeoConvert.ParsePointText method

将包含坐标的字符串转换为 IPoint 对象。

```csharp
public static IPoint ParsePointText(string text)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 文本 | String | 一个包含待转换坐标的字符串。该字符串应同时包含纬度和经度坐标。坐标应以空格、逗号或分号分隔。 |

### 返回值

与输入字符串等效的坐标的 IPoint 对象。

### 异常

| 异常 | 条件 |
| --- | --- |
| [GisException](../../gisexception/) |  |

## 备注

示例：\"80° 151°\", \"74°50.82', 172°08.21'\", \"80°;151°\", \"2CMB\", \"2CMB6682893142\", \"2C MB 66828 93142\", \"WMAQ12405535\"。

### 另见

* interface [IPoint](../../../aspose.gis.geometries/ipoint/)
* class [GeoConvert](../)
* namespace [Aspose.Gis](../../geoconvert/)
* assembly [Aspose.GIS](../../../)


