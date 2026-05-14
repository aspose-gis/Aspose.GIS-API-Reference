---
title: "الفئة Unit"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "الفئة Aspose.Gis.SpatialReferencing.Unit. تمثل وحدة قياس"
type: docs
weight: 4740
url: /ar/net/aspose.gis.spatialreferencing/unit/
---
## Unit class

يمثل وحدة القياس.

```csharp
public class Unit : IdentifiableObject
```

## المُنشئات

| الاسم | الوصف |
| --- | --- |
| [Unit](unit/)(string, double, Identifier) | إنشاء نسخة جديدة. |

## الخصائص

| الاسم | الوصف |
| --- | --- |
| static [Degree](../../aspose.gis.spatialreferencing/unit/degree/) { get; } | احصل على الوحدة التي تمثل الدرجات. |
| static [Meter](../../aspose.gis.spatialreferencing/unit/meter/) { get; } | احصل على الوحدة التي تمثل الأمتار. |
| static [Radian](../../aspose.gis.spatialreferencing/unit/radian/) { get; } | احصل على الوحدة التي تمثل الراديان. |
| [EpsgCode](../../aspose.gis.spatialreferencing/identifiableobject/epsgcode/) { get; } | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| [Factor](../../aspose.gis.spatialreferencing/unit/factor/) { get; } | عامل إلى المتر إذا كانت هذه وحدة طول، وعامل إلى الراديان إذا كانت وحدة زاوية. |
| [Identifier](../../aspose.gis.spatialreferencing/identifiableobject/identifier/) { get; } | معرف هذا الكائن القابل للتعريف. |
| [Name](../../aspose.gis.spatialreferencing/identifiableobject/name/) { get; } | اسم هذا الكائن. |

## الطرق

| الاسم | الوصف |
| --- | --- |
| [Apply](../../aspose.gis.spatialreferencing/unit/apply/)(double) | يحول الوسيط إلى الوحدة التي يصفها هذا الكائن. |
| [Deapply](../../aspose.gis.spatialreferencing/unit/deapply/)(double) | يحول الوسيط من الوحدة التي يصفها هذا الكائن إلى راديان أو أمتار. |
| override [ToString](../../aspose.gis.spatialreferencing/identifiableobject/tostring/)() | يعيد سلسلة تمثل الكائن الحالي. |

### انظر أيضًا

* class [IdentifiableObject](../identifiableobject/)
* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


