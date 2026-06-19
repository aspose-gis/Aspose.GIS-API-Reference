---
title: "ProjectedSpatialReferenceSystemParameters.AddProjectionParameter"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة ProjectedSpatialReferenceSystemParameters. تضيف معلمة إسقاط إلى هذا النظام. إذا كانت معلمة بهذا الاسم مضافة مسبقًا، فقم بتحديثها."
type: docs
weight: 100
url: /ar/net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/addprojectionparameter/
---
## ProjectedSpatialReferenceSystemParameters.AddProjectionParameter method

يضيف معامل الإسقاط إلى هذا SRS. إذا كان معامل بهذا الاسم مضافًا بالفعل - يتم تحديثه.

```csharp
public void AddProjectionParameter(string parameterName, double value)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| parameterName | String | اسم معلمة الإسقاط. |
| value | Double | قيمة المعلمة. يجب أن تكون وحدة القيمة في [`LinearUnit`](../linearunit/) أو [`AngularUnit`](../../geographicspatialreferencesystem/angularunit/) من [`Base`](../base/). |

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | *parameterName* هو null. |

### انظر أيضًا

* class [ProjectedSpatialReferenceSystemParameters](../)
* namespace [Aspose.Gis.SpatialReferencing](../../projectedspatialreferencesystemparameters/)
* assembly [Aspose.GIS](../../../)


