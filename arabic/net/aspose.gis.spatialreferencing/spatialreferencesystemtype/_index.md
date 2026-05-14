---
title: "التعداد SpatialReferenceSystemType"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "التعداد Aspose.Gis.SpatialReferencing.SpatialReferenceSystemType. يمثل نوع نظام الإحداثيات المكانية."
type: docs
weight: 4720
url: /ar/net/aspose.gis.spatialreferencing/spatialreferencesystemtype/
---
## SpatialReferenceSystemType enumeration

يمثل نوع نظام الإحداثيات المرجعية.

```csharp
public enum SpatialReferenceSystemType
```

### القيم

| الاسم | القيمة | الوصف |
| --- | --- | --- |
| Unknown | `0` | القيمة الافتراضية. يمكن إرجاعها من [`Type`](../spatialreferencesystem/type/) إذا كان هذا نظام إحداثيات مركب مع تركيبة غير صالحة من الأنظمة الأساسية. راجع [`IsCompound`](../spatialreferencesystem/iscompound/). |
| Geographic | `1` | نظام الإحداثيات الجغرافي يعتمد على خط الطول الزاوي وخط العرض الزاوي. يمكن تحويل نظام الإحداثيات الجغرافي إلى [`GeographicSpatialReferenceSystem`](../geographicspatialreferencesystem/) عبر طريقة [`AsGeographic`](../spatialreferencesystem/asgeographic/). |
| Geocentric | `2` | نظام الإحداثيات المركزي هو نظام إحداثيات ديكارتي ثلاثي الأبعاد مع الأصل في مركز الأرض. يمكن تحويل نظام الإحداثيات المركزي إلى [`GeocentricSpatialReferenceSystem`](../geocentricspatialreferencesystem/) عبر طريقة [`AsGeocentric`](../spatialreferencesystem/asgeocentric/). |
| Projected | `3` | نظام الإحداثيات الإسقاطي يعتمد على X خطي وY خطي. هو نتيجة تطبيق إسقاط على نظام إحداثيات جغرافي. يمكن تحويل نظام الإحداثيات الإسقاطي إلى [`ProjectedSpatialReferenceSystem`](../projectedspatialreferencesystem/) عبر طريقة [`AsProjected`](../spatialreferencesystem/asprojected/). |
| Vertical | `4` | نظام الإحداثيات العمودي يصف إحداثية الارتفاع الخطية. يمكن تحويل نظام الإحداثيات العمودي إلى [`VerticalSpatialReferenceSystem`](../verticalspatialreferencesystem/) عبر طريقة [`AsVertical`](../spatialreferencesystem/asvertical/). |
| Local | `5` | نظام الإحداثيات المحلي يربط الإحداثيات ببعض الكائنات، غير الأرض. يمكن تحويل نظام الإحداثيات المحلي إلى [`LocalSpatialReferenceSystem`](../localspatialreferencesystem/) عبر طريقة [`AsLocal`](../spatialreferencesystem/aslocal/). |

### انظر أيضًا

* namespace [Aspose.Gis.SpatialReferencing](../../aspose.gis.spatialreferencing/)
* assembly [Aspose.GIS](../../)


