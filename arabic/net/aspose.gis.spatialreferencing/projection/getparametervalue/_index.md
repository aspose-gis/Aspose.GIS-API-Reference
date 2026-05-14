---
title: "Projection.GetParameterValue"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Projection. تحصل على المعامل بالاسم المحدد لهذا الإسقاط"
type: docs
weight: 40
url: /ar/net/aspose.gis.spatialreferencing/projection/getparametervalue/
---
## Projection.GetParameterValue method

يحصل على المعلمة ذات الاسم المحدد لهذا الإسقاط.

```csharp
public double GetParameterValue(string name, ParameterType type = ParameterType.Other)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاسم | String | اسم المعلمة. |
| type | ParameterType | نوع المعامل. يحدد عامل الوحدة الذي سيتم إلغاء تطبيقه: إذا كان النوع Linear فإن [`LinearParametersUnit`](../linearparametersunit/) سيتم إلغاء تطبيقه وستكون النتيجة بالمتر. إذا كان النوع Angular فإن [`AngularParametersUnit`](../angularparametersunit/) سيتم إلغاء تطبيقه وستكون النتيجة بالراديان. إذا كان النوع Other فستُعاد قيمة المعامل كما هي. |

### قيمة الإرجاع

معامل بالاسم المحدد.

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المعطى فارغ. |
| InvalidOperationException | لا يوجد معامل بهذا الاسم. |

### انظر أيضًا

* enum [ParameterType](../../parametertype/)
* class [Projection](../)
* namespace [Aspose.Gis.SpatialReferencing](../../projection/)
* assembly [Aspose.GIS](../../../)


