---
title: "الواجهة ICircularString"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "واجهة Aspose.Gis.Geometries.ICircularString. منحنى متعدد القمم مع استيفاء دائري بين النقاط"
type: docs
weight: 2740
url: /ar/net/aspose.gis.geometries/icircularstring/
---
## ICircularString interface

منحنى متعدد الرؤوس مع استيفاء دائري بين النقاط.

```csharp
public interface ICircularString : ICurve, IEquatable<ICircularString>, IReadOnlyList<IPoint>
```

## الطرق

| الاسم | الوصف |
| --- | --- |
| [ToEditable](../../aspose.gis.geometries/icircularstring/toeditable/)() | يحصل على نسخة قابلة للتحرير من هذه الهندسة. |

## ملاحظات

تتكون `CircularString` من مقطع أو أكثر من أقواس دائرية متصلة من النهاية إلى النهاية. تحدد النقاط الثلاث الأولى المقطع الأول. النقطة الأولى هي نقطة بدء القوس. النقطة الثانية هي أي نقطة وسطية على القوس غير نقطة البدء أو النهاية. النقطة الثالثة هي نهاية القوس. تُعرّف الأقواس اللاحقة بنقاطها الوسطية والنهاية فقط، حيث تُعرّف نقطة البدء ضمنيًا كنقطة نهاية المقطع السابق.

### انظر أيضًا

* interface [ICurve](../icurve/)
* interface [IPoint](../ipoint/)
* namespace [Aspose.Gis.Geometries](../../aspose.gis.geometries/)
* assembly [Aspose.GIS](../../)


