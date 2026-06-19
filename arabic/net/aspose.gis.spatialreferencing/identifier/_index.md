---
title: "الفئة Identifier"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.Identifier. تمثل معرفًا مرجعًا للوصف الخارجي لكائن. إذا قمت بإنشاء SRS من WKT فإن Identifier يتطابق مع كلمة AUTHORITY."
type: docs
weight: 4610
url: /ar/net/aspose.gis.spatialreferencing/identifier/
---
## Identifier class

تمثل معرفًا - مرجعًا للوصف الخارجي لكائن. إذا قمت بإنشاء SRS من WKT، فإن `Identifier` يتطابق مع كلمة "AUTHORITY".

```csharp
public class Identifier : IEquatable<Identifier>
```

## المنشئات

| الاسم | الوصف |
| --- | --- |
| [Identifier](identifier/)(string, string) | إنشاء نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| [AuthorityName](../../aspose.gis.spatialreferencing/identifier/authorityname/) { get; } | اسم السلطة التي أعطت [`AuthorityUniqueIdentifier`](./authorityuniqueidentifier/). |
| [AuthorityUniqueIdentifier](../../aspose.gis.spatialreferencing/identifier/authorityuniqueidentifier/) { get; } | طريقة فريدة لتمثيل كائن داخل [`AuthorityName`](./authorityname/). |

## الطرق

| الاسم | الوصف |
| --- | --- |
| static [Epsg](../../aspose.gis.spatialreferencing/identifier/epsg/)(int) | ينشئ معرفًا جديدًا يمثل معرف EPSG بالرمز *epsgCode*. |
| [Equals](../../aspose.gis.spatialreferencing/identifier/equals/#equals)(Identifier) | يشير إلى ما إذا كان الكائن الحالي مساويًا لكائن آخر من نفس النوع. |
| override [Equals](../../aspose.gis.spatialreferencing/identifier/equals/#equals_1)(object) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [GetEpsgCode](../../aspose.gis.spatialreferencing/identifier/getepsgcode/)() | إذا كان هذا الكائن يمثل معرف EPSG صالح (مثلاً - اسم السلطة هو "EPSG" والمعرف الفريد للسلطة هو عدد صحيح) - إرجعه. وإلا - إرجع -1. |
| override [GetHashCode](../../aspose.gis.spatialreferencing/identifier/gethashcode/)() | يعمل كدالة تجزئة افتراضية. |
| [operator ==](../../aspose.gis.spatialreferencing/identifier/op_equality/) | ينفّذ العامل ==. |
| [operator !=](../../aspose.gis.spatialreferencing/identifier/op_inequality/) | ينفّذ العامل !=. |

## أمثلة

نظام الإحداثيات المكانية WGS 84 لديه رمز EPSG 4326، لذا قد يحتوي على معرف:

```csharp
new  {  = "EPSG",  = 4326 };
```

القطب الأرضي WGS 84 لديه رمز EPSG 7030، وقد يحتوي على معرف:

```csharp
new  {  = "EPSG",  = 7030 };
```

### انظر أيضًا

* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


