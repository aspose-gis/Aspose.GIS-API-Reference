---
title: "DatabaseQueryDataSourceBuilder.GeometryField"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة DatabaseQueryDataSourceBuilder. تُكوّن اسم الحقل الذي سيتم استخراج الهندسة منه"
type: docs
weight: 40
url: /ar/net/aspose.gis.formats.database/databasequerydatasourcebuilder/geometryfield/
---
## DatabaseQueryDataSourceBuilder.GeometryField method

يضبط اسم الحقل الذي سيتم استخراج الهندسة منه.

```csharp
public DatabaseQueryDataSourceBuilder GeometryField(string name)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم حقل الهندسة. |

### قيمة الإرجاع

[`DatabaseQueryDataSourceBuilder`](../)

## ملاحظات

الصيغة الثنائية المدعومة حاليًا أي على جانب قاعدة البيانات الطرق هي ST_AsBinary، ST_AsWKB، ST_AsEWKB. وإذا استخدمت طرقًا غير Extended WKB، التي تحتوي بالفعل على معرف نظام الإحداثيات (srid)، يجب عليك استخدام حقل إضافي يحتوي على معلومات srid وتكوينه عبر [`SridField`](../sridfield/).

### انظر أيضًا

* class [DatabaseQueryDataSourceBuilder](../)
* namespace [Aspose.Gis.Formats.Database](../../databasequerydatasourcebuilder/)
* assembly [Aspose.GIS](../../../)


