---
title: "Identifier.Epsg"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Identifier. تنشئ Identifier جديد يمثل معرف EPSG بالرمز epsgCode"
type: docs
weight: 20
url: /ar/net/aspose.gis.spatialreferencing/identifier/epsg/
---
## Identifier.Epsg method

ينشئ معرفًا جديدًا يمثل معرف EPSG بالرمز *epsgCode*.

```csharp
public static Identifier Epsg(int epsgCode)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| epsgCode | Int32 | رمز EPSG. |

### قيمة الإرجاع

معرف جديد مع [`AuthorityName`](../authorityname/) "EPSG" و [`AuthorityUniqueIdentifier`](../authorityuniqueidentifier/)*epsgCode*. إذا كان *epsgCode* أقل من 0 - أعد `null`;

### انظر أيضًا

* class [Identifier](../)
* namespace [Aspose.Gis.SpatialReferencing](../../identifier/)
* assembly [Aspose.GIS](../../../)


