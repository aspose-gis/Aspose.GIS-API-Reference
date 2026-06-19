---
title: "类 GdbTableFile"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Aspose.Gis.Common.Formats.GdbTable.GdbTableFile 类."
type: docs
weight: 460
url: /zh/net/aspose.gis.common.formats.gdbtable/gdbtablefile/
---
## GdbTableFile class

```csharp
public class GdbTableFile : IDisposable, IEnumerable<GdbTableRowReader>
```

## 属性

| 名称 | 描述 |
| --- | --- |
| [Count](../../aspose.gis.common.formats.gdbtable/gdbtablefile/count/) { get; } |  |
| [Fields](../../aspose.gis.common.formats.gdbtable/gdbtablefile/fields/) { get; } |  |
| [GdbTableVersion](../../aspose.gis.common.formats.gdbtable/gdbtablefile/gdbtableversion/) { get; } |  |
| [IsDirty](../../aspose.gis.common.formats.gdbtable/gdbtablefile/isdirty/) { get; } |  |
| [NextRowId](../../aspose.gis.common.formats.gdbtable/gdbtablefile/nextrowid/) { get; } |  |
| [ObjectIdField](../../aspose.gis.common.formats.gdbtable/gdbtablefile/objectidfield/) { get; } |  |
| [ShapeField](../../aspose.gis.common.formats.gdbtable/gdbtablefile/shapefield/) { get; } |  |
| [ShapeType](../../aspose.gis.common.formats.gdbtable/gdbtablefile/shapetype/) { get; set; } |  |

## 方法

| 名称 | 描述 |
| --- | --- |
| static [Create](../../aspose.gis.common.formats.gdbtable/gdbtablefile/create/#create)(AbstractPathInternal) |  |
| static [Create](../../aspose.gis.common.formats.gdbtable/gdbtablefile/create/#create_1)(string) |  |
| static [Open](../../aspose.gis.common.formats.gdbtable/gdbtablefile/open/#open)(AbstractPathInternal) |  |
| static [Open](../../aspose.gis.common.formats.gdbtable/gdbtablefile/open/#open_1)(string) |  |
| [AddField](../../aspose.gis.common.formats.gdbtable/gdbtablefile/addfield/)(GdbFieldDescription) |  |
| [AddRow](../../aspose.gis.common.formats.gdbtable/gdbtablefile/addrow/)(GdbTableRowWriter) |  |
| [CreateRow](../../aspose.gis.common.formats.gdbtable/gdbtablefile/createrow/)() |  |
| [DeleteRow](../../aspose.gis.common.formats.gdbtable/gdbtablefile/deleterow/)(int) |  |
| [DeleteRowAt](../../aspose.gis.common.formats.gdbtable/gdbtablefile/deleterowat/)(int) |  |
| [Dispose](../../aspose.gis.common.formats.gdbtable/gdbtablefile/dispose/)() |  |
| [GetEnumerator](../../aspose.gis.common.formats.gdbtable/gdbtablefile/getenumerator/)() |  |
| [HasField](../../aspose.gis.common.formats.gdbtable/gdbtablefile/hasfield/)(string) |  |
| [IsValidAndUnqiueFieldName](../../aspose.gis.common.formats.gdbtable/gdbtablefile/isvalidandunqiuefieldname/)(string, out string) |  |
| [ReadRow](../../aspose.gis.common.formats.gdbtable/gdbtablefile/readrow/)(int) |  |
| [ReadRowAt](../../aspose.gis.common.formats.gdbtable/gdbtablefile/readrowat/)(int) |  |
| [UpdateRow](../../aspose.gis.common.formats.gdbtable/gdbtablefile/updaterow/)(GdbTableRowWriter, int) |  |
| static [IsValidFieldName](../../aspose.gis.common.formats.gdbtable/gdbtablefile/isvalidfieldname/)(string, out string) |  |

### 另见

* class [GdbTableRowReader](../gdbtablerowreader/)
* namespace [Aspose.Gis.Common.Formats.GdbTable](../../aspose.gis.common.formats.gdbtable/)
* assembly [Aspose.GIS](../../)


