---
title: TopoJsonOptions.ObjectNameAttribute
second_title: Aspose.GIS for .NET API Reference
description: TopoJsonOptions property. Name of the attribute that reflects the name of the object that contains a feature
type: docs
weight: 40
url: /net/aspose.gis.formats.topojson/topojsonoptions/objectnameattribute/
---
## TopoJsonOptions.ObjectNameAttribute property

Name of the attribute, that reflects the name of the object that contains a feature.

```csharp
public string ObjectNameAttribute { get; set; }
```

## Remarks

TopoJSON may contain any number of named objects. Every such object can contain multiple features. Refer to TopoJSON specification to more detail on named objects. When reading TopoJSON, this property specifies, what attribute should reflect name of the object that contains a feature. When writing TopoJSON, this property specifies, what attribute should be used to group features in objects. Default is "topojson_object_name".

### See Also

* class [TopoJsonOptions](../)
* namespace [Aspose.Gis.Formats.TopoJson](../../topojsonoptions/)
* assembly [Aspose.GIS](../../../)


