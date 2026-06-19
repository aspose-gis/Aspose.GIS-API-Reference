---
title: "Aspose.Gis.SpatialReferencing"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "مساحة الأسماء Aspose.Gis.SpatialReferencing توفر فئات للعمل مع مراجع الفضاء وأنظمة الإحداثيات المرجعية."
type: docs
weight: 750
url: /ar/net/aspose.gis.spatialreferencing/
---
مساحة الأسماء `Aspose.Gis.SpatialReferencing` توفر فئات للعمل مع المراجع المكانية (أنظمة الإحداثيات المرجعية).

## الفئات

| فئة | الوصف |
| --- | --- |
| [Axis](./axis/) | المحور يصف بُعدًا واحدًا من نظام الإشارة المكانية (SRS). |
| [BursaWolfParameters](./bursawolfparameters/) | فئة تحتوي على معلمات صيغة بورسا-وولف للتحويل إلى مرجع آخر. |
| [CompoundSpatialReferenceSystem](./compoundspatialreferencesystem/) | نظام الإشارة المكانية المركب يجمع نظامين أساسيين، ولا يمكن لأي منهما أن يكون مركبًا. |
| [Ellipsoid](./ellipsoid/) | القطعة البيضاوية تمثل بيضاويًا، وهو تقريب للأرض. |
| [GeocentricSpatialReferenceSystem](./geocentricspatialreferencesystem/) | نظام الإشارة المكانية الجيوسنترية هو نظام إحداثيات ديكارتي ثلاثي الأبعاد مع الأصل في مركز الأرض. |
| [GeocentricSpatialReferenceSystemParameters](./geocentricspatialreferencesystemparameters/) | معلمات لإنشاء نظام الإشارة المكانية الجيوسنترية. للمعلمات قيم افتراضية معقولة، لذلك سيتعين عليك تعيين بعضها فقط. إذا قمت بتعيين `null` لأي معلمة، سيتم استخدام القيمة الافتراضية. |
| [GeographicDatum](./geographicdatum/) | المرجع الجغرافي يربط خط الطول وخط العرض بمكان معين على الأرض. |
| [GeographicSpatialReferenceSystem](./geographicspatialreferencesystem/) | نظام الإشارة المكانية الجغرافي هو نظام إشارة يعتمد على خط الطول وخط العرض. يمكن أن يكون نظام الإشارة المكانية الجغرافي ثنائي الأبعاد أو ثلاثي الأبعاد. إذا كان نظام الإشارة المكانية الجغرافي ثلاثيًا الأبعاد، فإنه في الواقع نظام مركب يتكون من نظام إشارة ثنائي الأبعاد ونظام إشارة عمودي. |
| [GeographicSpatialReferenceSystemParameters](./geographicspatialreferencesystemparameters/) | معلمات لإنشاء نظام الإشارة المكانية الجغرافي. للمعلمات قيم افتراضية معقولة، لذا سيتعين عليك تعيين بعضها فقط. إذا قمت بتعيين `null` لأي معلمة، سيتم استخدام القيمة الافتراضية. |
| [IdentifiableObject](./identifiableobject/) | يمثل كائنًا قد يحتوي على رمز EPSG واسم. |
| [Identifier](./identifier/) | يمثل معرفًا - إشارة إلى وصف خارجي لكائن. إذا أنشأت نظام إشارة مكانية من WKT، فإن [`Identifier`](../aspose.gis.spatialreferencing/identifier/) يتطابق مع كلمة "AUTHORITY". |
| [LocalDatum](./localdatum/) | يشير إلى الطريقة المستخدمة للقياسات في نظام الإشارة المكانية المحلي. |
| [LocalSpatialReferenceSystem](./localspatialreferencesystem/) | نظام الإشارة المكانية المحلي يربط الإحداثيات بكائن ما، وليس بالأرض. |
| [PrimeMeridian](./primemeridian/) | خط الزوال الرئيسي يمثل خط طول تُعرّف فيه قيمة الطول بـ 0. |
| [ProjectedSpatialReferenceSystem](./projectedspatialreferencesystem/) | نظام الإشارة المكانية الإسقاطي هو نتيجة تطبيق إسقاط على نظام إشارة مكانية جغرافي. يمكن أن يكون نظام الإشارة المكانية الإسقاطي ثنائي الأبعاد أو ثلاثي الأبعاد. إذا كان نظام الإشارة المكانية الإسقاطي ثلاثيًا الأبعاد، فإنه في الواقع نظام مركب يتكون من نظام إشارة إسقاطي ثنائي الأبعاد ونظام إشارة عمودي أحادي البعد. |
| [ProjectedSpatialReferenceSystemParameters](./projectedspatialreferencesystemparameters/) | معلمات لإنشاء نظام الإشارة المكانية الإسقاطي. بعض المعلمات لها قيم افتراضية. بعض المعلمات لها قيم افتراضية معقولة، لذا لا يتعين عليك تعيينها. إذا قمت بتعيين `null` لتلك المعلمات، سيتم استخدام القيمة الافتراضية. لا تحتوي [`ProjectionMethodName`](../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/projectionmethodname/) و[`Base`](../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/base/) على قيم افتراضية - عليك تعيين قيمة غير `null` لهذه الخصائص. |
| [Projection](./projection/) | يمثل طريقة إسقاط مع معلمات، تحول (خط الطول، خط العرض) إلى (س، ص). |
| [SpatialReferenceSystem](./spatialreferencesystem/) | نظام الإشارة المكانية يربط الإحداثيات بالأماكن على الأرض. هناك أنواع مختلفة من SRS، راجع [`Type`](../aspose.gis.spatialreferencing/spatialreferencesystem/type/). علاوة على ذلك، إذا كان نوع SRS جغرافيًا أو إسقاطيًا، يمكن أن يكون SRS مركبًا أو فرديًا، راجع [`IsCompound`](../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/). |
| [SpatialReferenceSystemTransformation](./spatialreferencesystemtransformation/) | تحويل نظام الإشارة المكانية يحول الأشكال الهندسية من نظام الإشارة المكانية المصدر إلى نظام الإشارة المكانية الهدف. |
| [TransformationException](./transformationexception/) | يتم إلقاء استثناء التحويل عندما يحدث خطأ أثناء تحويل الإحداثيات أو أثناء إنشاء التحويل. |
| [Unit](./unit/) | يمثل وحدة القياس. |
| [VerticalDatum](./verticaldatum/) | يشير إلى الطريقة المستخدمة للقياسات العمودية. |
| [VerticalSpatialReferenceSystem](./verticalspatialreferencesystem/) | نظام الإحداثيات المرجعية العمودي هو نظام إحداثيات مرجعية أحادي البعد يصف إحداثيات الارتفاع. |
## تعداد

| تعداد | الوصف |
| --- | --- |
| [AxisDirection](./axisdirection/) | اتجاه المحور يحدد الاتجاه الذي يشير إليه المحور. |
| [GeocentricAxisesOrder](./geocentricaxisesorder/) | يمثل ترتيب المحاور في نظام الإحداثيات المرجعية الجيوسنترية. |
| [GeographicAxisesOrder](./geographicaxisesorder/) | يمثل ترتيب المحاور في نظام الإحداثيات المرجعية الجغرافية. |
| [ParameterType](./parametertype/) | يحدد نوع المعامل في [`Projection`](../aspose.gis.spatialreferencing/projection/). |
| [ProjectedAxisesOrder](./projectedaxisesorder/) | يمثل ترتيب المحاور في نظام الإحداثيات المرجعية الجغرافية. |
| [SpatialReferenceSystemType](./spatialreferencesystemtype/) | يمثل نوع نظام الإحداثيات المرجعية. |


