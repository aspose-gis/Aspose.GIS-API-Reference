---
title: "TopoJsonOptions.ObjectNameAttribute"
second_title: "Aspose.GIS for .NET API 参考"
description: "TopoJsonOptions 属性。表示反映包含要素的对象名称的属性名称"
type: docs
weight: 40
url: /zh/net/aspose.gis.formats.topojson/topojsonoptions/objectnameattribute/
---
## TopoJsonOptions.ObjectNameAttribute property

反映包含要素的对象名称的属性名称。

```csharp
public string ObjectNameAttribute { get; set; }
```

## 备注

TopoJSON 可以包含任意数量的命名对象。每个此类对象可以包含多个要素。请参阅 TopoJSON 规范以获取有关命名对象的更多详细信息。读取 TopoJSON 时，此属性指定应使用哪个属性来反映包含要素的对象的名称。写入 TopoJSON 时，此属性指定应使用哪个属性来将要素分组到对象中。默认值为 "topojson_object_name"。

### 另见

* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


