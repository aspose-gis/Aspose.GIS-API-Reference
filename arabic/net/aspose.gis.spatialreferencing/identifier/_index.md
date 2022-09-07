---
title: Identifier
second_title: Aspose.GIS لمرجع .NET API
description: يمثل معرّفًا  مرجعًا لوصف خارجي لكائن . إذا قمت بإنشاء SRS من WKT Identifier./identifier يتوافق مع الكلمة الرئيسية AUTHORITY .
type: docs
weight: 2060
url: /ar/net/aspose.gis.spatialreferencing/identifier/
---
## Identifier class

يمثل معرّفًا - مرجعًا لوصف خارجي لكائن . إذا قمت بإنشاء SRS من WKT ،[`Identifier`](../identifier) يتوافق مع الكلمة الرئيسية "AUTHORITY" .

```csharp
public class Identifier : IEquatable<Identifier>
```

## المنشئون

| اسم | وصف |
| --- | --- |
| [Identifier](identifier)(string, string) | إنشاء مثيل جديد . |

## الخصائص

| اسم | وصف |
| --- | --- |
| [AuthorityName](../../aspose.gis.spatialreferencing/identifier/authorityname) { get; } | اسم السلطة الذي أعطى[`AuthorityUniqueIdentifier`](./authorityuniqueidentifier) . |
| [AuthorityUniqueIdentifier](../../aspose.gis.spatialreferencing/identifier/authorityuniqueidentifier) { get; } | طريقة فريدة لتمثيل كائن داخل ملف[`AuthorityName`](./authorityname) . |

## طُرق

| اسم | وصف |
| --- | --- |
| static [Epsg](../../aspose.gis.spatialreferencing/identifier/epsg)(int) | إنشاء معرّف جديد يمثل معرّف EPSG مع التعليمات البرمجية*epsgCode* . |
| [Equals](../../aspose.gis.spatialreferencing/identifier/equals#equals)(Identifier) | يشير إلى ما إذا كان الكائن الحالي يساوي كائنًا آخر من نفس النوع. |
| override [Equals](../../aspose.gis.spatialreferencing/identifier/equals#equals_1)(object) | يحدد ما إذا كان الكائن المحدد مساويًا للكائن الحالي. |
| [GetEpsgCode](../../aspose.gis.spatialreferencing/identifier/getepsgcode)() | إذا كان هذا الكائن يمثل معرف EPSG صالحًا (على سبيل المثال - اسم الاستناد هو "EPSG" والمعرف الفريد الاستنادي هو عدد صحيح) - قم بإعادته. خلاف ذلك - إرجاع -1 . |
| override [GetHashCode](../../aspose.gis.spatialreferencing/identifier/gethashcode)() | بمثابة وظيفة التجزئة الافتراضية. |
| [operator ==](../../aspose.gis.spatialreferencing/identifier/op_equality) | تنفيذ عامل التشغيل == . |
| [operator !=](../../aspose.gis.spatialreferencing/identifier/op_inequality) | تنفذ عامل التشغيل! = . |

### أمثلة

WGS 84 يحتوي نظام الإسناد المكاني على كود EPSG 4326 ، لذلك قد يحتوي على المعرف: WGS 84 Ellipsoid لها كود EPSG 7030 ، وقد تحتوي على المعرف:

```csharp
new  {  = "EPSG",  = 4326 };
```

```csharp
new  {  = "EPSG",  = 7030 };
```

### أنظر أيضا

* مساحة الاسم [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing)
* المجسم [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->