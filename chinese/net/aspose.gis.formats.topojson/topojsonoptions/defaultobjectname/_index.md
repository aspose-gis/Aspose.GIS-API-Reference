---
title: "TopoJsonOptions.DefaultObjectName"
second_title: "Aspose.GIS for .NET API 参考"
description: "TopoJsonOptions 属性。默认放置要素的对象的名称"
type: docs
weight: 20
url: /zh/net/aspose.gis.formats.topojson/topojsonoptions/defaultobjectname/
---
## TopoJsonOptions.DefaultObjectName property

默认情况下放置要素的对象名称。

```csharp
public string DefaultObjectName { get; set; }
```

## 备注

这是写入选项——它不影响读取。TopoJSON 可以包含任意数量的命名对象。每个此类对象可以包含多个要素。为了指定将要素放入哪个对象，请使用 [`ObjectNameAttribute`](../objectnameattribute/) 属性。如果名称为 [`ObjectNameAttribute`](../objectnameattribute/) 的属性为 `null` 或未为某些要素设置，则该要素将添加到名称为 `DefaultObjectName` 的对象中。如果名称为 [`ObjectNameAttribute`](../objectnameattribute/) 的属性在 [`Attributes`](../../../aspose.gis/vectorlayer/attributes/) 集合中不存在，则所有要素都放入名称为 [`ObjectNameAttribute`](../objectnameattribute/) 的对象中。默认值为 "unnamed"。

### 另见

* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


