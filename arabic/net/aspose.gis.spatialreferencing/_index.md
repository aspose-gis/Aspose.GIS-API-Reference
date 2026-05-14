---
title: "Aspose.Gis.SpatialReferencing"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "مساحة الأسماء Aspose.Gis.SpatialReferencing توفر فئات للعمل مع مراجع الفضاء وأنظمة الإحداثيات المرجعية."
type: docs
weight: 750
url: /ar/net/aspose.gis.spatialreferencing/
---
مساحة الاسم `Aspose.Gis.SpatialReferencing` توفر فئات للعمل مع الإشارات المكانية (أنظمة الإحداثيات المرجعية).

## الفئات

| فئة | الوصف |
| --- | --- |
| [Axis](./axis/) | المحور يصف بُعدًا واحدًا من نظام الإسناد المكاني (SRS). |
| [BursaWolfParameters](./bursawolfparameters/) | فئة تحتوي على معلمات صيغة بورسا-وولف لتحويل إلى معيار آخر. |
| [CompoundSpatialReferenceSystem](./compoundspatialreferencesystem/) | نظام الإسناد المكاني المركب يجمع نظامين أساسيين، ولا يمكن لأي منهما أن يكون مركبًا. |
| [Ellipsoid](./ellipsoid/) | الإهليلج يمثل إهليلجًا يقترب من شكل الأرض. |
| [GeocentricSpatialReferenceSystem](./geocentricspatialreferencesystem/) | نظام الإسناد المكاني الجيوسنترى هو نظام إسناد ثلاثي الأبعاد كارتيسي مع الأصل في مركز الأرض. |
| [GeocentricSpatialReferenceSystemParameters](./geocentricspatialreferencesystemparameters/) | معلمات لإنشاء نظام إسناد جيوسنترى. المعلمات لها قيم افتراضية معقولة، لذا سيتعين عليك تعيين بعضها فقط. إذا قمت بتعيين `null` لأي معلمة، سيتم استخدام القيمة الافتراضية. |
| [GeographicDatum](./geographicdatum/) | المعيار الجغرافي يربط خط الطول والعرض بمكان معين على الأرض. |
| [GeographicSpatialReferenceSystem](./geographicspatialreferencesystem/) | نظام إسناد جغرافي هو نظام إسناد يعتمد على خط الطول والعرض. يمكن أن يكون نظام إسناد جغرافي ثنائي الأبعاد أو ثلاثي الأبعاد. إذا كان نظام الإسناد الجغرافي ثلاثيًا الأبعاد، فهو في الواقع نظام إسناد مركب يتكون من نظام إسناد ثنائي الأبعاد ونظام إسناد عمودي. |
| [GeographicSpatialReferenceSystemParameters](./geographicspatialreferencesystemparameters/) | معلمات لإنشاء نظام إسناد جغرافي. المعلمات لها قيم افتراضية معقولة، لذا سيتعين عليك تعيين بعضها فقط. إذا قمت بتعيين `null` لأي معلمة، سيتم استخدام القيمة الافتراضية. |
| [IdentifiableObject](./identifiableobject/) | يمثل كائنًا قد يحتوي على رمز EPSG واسم. |
| [Identifier](./identifier/) | يمثل معرفًا - إشارة إلى وصف خارجي لكائن. إذا أنشأت نظام إسناد من WKT، فإن [`Identifier`](../aspose.gis.spatialreferencing/identifier/) يتطابق مع كلمة "AUTHORITY". |
| [LocalDatum](./localdatum/) | يشير إلى الطريقة المستخدمة للقياسات في نظام الإسناد المكاني المحلي. |
| [LocalSpatialReferenceSystem](./localspatialreferencesystem/) | نظام الإسناد المحلي يربط الإحداثيات ببعض الكائنات، وليس بالأرض. |
| [PrimeMeridian](./primemeridian/) | خط الزوال الأساسي يمثل خط طول تُعرّف فيه قيمة الطول بـ 0. |
| [ProjectedSpatialReferenceSystem](./projectedspatialreferencesystem/) | نظام الإسناد الإسقاطي هو نتيجة تطبيق إسقاط على نظام إسناد جغرافي. يمكن أن يكون نظام إسناد إسقاطي ثنائي الأبعاد أو ثلاثي الأبعاد. إذا كان نظام الإسناد الإسقاطي ثلاثيًا الأبعاد، فهو في الواقع نظام إسناد مركب يتكون من نظام إسناد إسقاطي ثنائي الأبعاد ونظام إسناد عمودي أحادي البعد. |
| [ProjectedSpatialReferenceSystemParameters](./projectedspatialreferencesystemparameters/) | معلمات لإنشاء نظام إسناد إسقاطي. بعض المعلمات لها قيم افتراضية. بعض المعلمات لها قيم افتراضية معقولة، لذا لا يتعين عليك تعيينها فقط. إذا قمت بتعيين `null` لتلك المعلمات، سيتم استخدام قيمة افتراضية. [`ProjectionMethodName`](../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/projectionmethodname/) و[`Base`](../aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/base/) لا يمتلكان قيمًا افتراضية - عليك تعيين قيمة غير `null` لهذه الخصائص. |
| [Projection](./projection/) | يمثل طريقة إسقاط مع معلمات، تحول (خط الطول، خط العرض) إلى (س، ص). |
| [SpatialReferenceSystem](./spatialreferencesystem/) | نظام الإسناد المكاني يربط الإحداثيات بالأماكن على الأرض. هناك أنواع مختلفة من نظام الإسناد، راجع [`Type`](../aspose.gis.spatialreferencing/spatialreferencesystem/type/). علاوة على ذلك، إذا كان نوع نظام الإسناد جغرافيًا أو إسقاطيًا، يمكن أن يكون نظام الإسناد مركبًا أو فرديًا، راجع [`IsCompound`](../aspose.gis.spatialreferencing/spatialreferencesystem/iscompound/). |
| [SpatialReferenceSystemTransformation](./spatialreferencesystemtransformation/) | تحويل نظام الإسناد المكاني يحول الأشكال الهندسية من نظام الإسناد المصدر إلى نظام الإسناد الهدف. |
| [TransformationException](./transformationexception/) | يتم إلقاء استثناء التحويل عندما يحدث خطأ أثناء تحويل الإحداثيات أو أثناء إنشاء التحويل. |
| [Unit](./unit/) | يمثل وحدة القياس. |
| [VerticalDatum](./verticaldatum/) | يشير إلى الطريقة المستخدمة للقياسات الرأسية. |
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


