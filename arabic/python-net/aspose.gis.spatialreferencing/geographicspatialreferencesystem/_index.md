---
title: "فئة GeographicSpatialReferenceSystem"
type: docs
weight: 80
url: /ar/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/
---

**Summary:** A Geographic SRS is an SRS that is based on longitude and latitude.<br/>            A Geographic SRS can be two dimensional or three dimensional.<br/>            If geographic SRS is three dimensional, then it is actually a compound SRS of two dimensional SRS and vertical SRS.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | الوحدة المستخدمة للأبعاد الزاوية في هذا SRS. |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | يعيد هذا الـ SRS محولًا إلى [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/).<br/>            استخدم [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) لمعرفة ما إذا كان التحويل ممكنًا. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | يعيد هذا الـ SRS محولًا إلى [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/).<br/>            استخدم [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) لمعرفة ما إذا كان التحويل ممكنًا. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | يرجع هذا. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | يعيد هذا الـ SRS محولًا إلى [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/).<br/>            استخدم [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) لمعرفة ما إذا كان التحويل ممكنًا. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | يعيد هذا SRS محولًا إلى [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/).<br/>            استخدم [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) لمعرفة ما إذا كان التحويل ممكنًا. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | يعيد هذا الـ SRS محولًا إلى [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/).<br/>            استخدم [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) لمعرفة ما إذا كان التحويل ممكنًا. |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r | ترتيب المحاور في هذا SRS.<br/> إذا لم يكن هذا SRS صالحًا ويحتوي على اتجاهات محاور خاطئة، يتم إرجاع [GeographicAxisesOrder.INVALID](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/). |
| dimensions_count | int | r | يرجع عدد الأبعاد في هذا SRS. بالنسبة إلى SRS الجغرافي يمكن أن يكون:<br/> اثنان - إذا كان هذا SRS جغرافيًا واحدًا.<br/> ثلاثة - إذا كان هذا SRS مركبًا، يتكون من SRS جغرافي أحادي البعد ثنائي الأبعاد و SRS عمودي يضيف البعد الثالث. |
| epsg_code | int | r | إذا كان معرف هذا الكائن هو معرف EPSG - يتم إرجاع رمزه. وإلا - يتم إرجاع -1. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | نظام الإسناد المكاني ETRS 89 (EPSG:4258). |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | نظام الإسناد المكاني ETRS 89 / ETRS Lambert Azimuthal Equal Area (EPSG:3035). |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | نظام الإسناد المكاني ETRS 89 / Lambert Conformal Conic (EPSG:3034). |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | يعيد المرجع الجغرافي لهذا الـ SRS. |
| has_geographic_datum | bool | r | يرجع <see langword="true" />، لأن SRS الجغرافي دائمًا ما يحتوي على خط الزوال الأساسي. |
| has_prime_meridian | bool | r | يرجع <see langword="true" />، لأن SRS الجغرافي دائمًا ما يحتوي على خط الزوال الأساسي. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | معرف هذا الكائن القابل للتعريف. |
| is_compound | bool | r | يعيد ما إذا كان هذا الـ SRS مركبًا (اتحاد لاثنين من الـ SRS).<br/>            تُعتبر التركيبات التالية للـ SRS في الـ SRS المركب صالحة:<br/>            Geographic SRS + Vertical SRS، في هذه الحالة سيكون نوع الـ SRS المركب هو [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            Projected SRS + Vertical SRS، في هذه الحالة سيكون نوع الـ SRS المركب هو [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/).<br/>            إذا اختلفت تركيبة الـ SRSs، سيكون نوع الـ SRS المركب هو [SpatialReferenceSystemType.UNKNOWN](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| is_single | bool | r | يعيد ما إذا كان هذا الـ SRS منفردًا (ليس اتحادًا لاثنين من الـ SRS). |
| is_valid | bool | r | نفس <see cref=\"M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)\" />، لكن لا تُعيد رسالة الخطأ. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | نظام الإسناد المكاني NAD 83 (EPSG:4269). |
| الاسم | string | r | اسم هذا الكائن. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | نظام الإسناد المكاني OSGB 36 (EPSG:4277). |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | نظام الإسناد المكاني OSGB 36 / British National Grid (EPSG:27700). |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | يعيد خط الزوال الرئيسي لهذا الـ SRS. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | يرجع [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/). |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | نظام الإحداثيات المكاني Web Mercator (EPSG:3857). |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | نظام الإحداثيات المكاني WGS 72 (EPSG:4322). |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | نظام الإحداثيات المكاني WGS 84 (EPSG:4326). |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | إنشاء SRS مركب. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | إنشاء نظام إحداثيات مكاني بناءً على رمز EPSG المحدد. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | ينشئ <c>SpatialReferenceSystem</c> جديدًا بناءً على سلسلة WKT (نص معروف جيدًا). |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | إنشاء SRS جيوسنترية من معلمات مخصصة. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | إنشاء SRS جغرافية من معلمات مخصصة. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | إنشاء نظام إحداثيات مكاني محلي. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | إنشاء SRS إسقاطية من معلمات مخصصة. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | ينشئ تحويلًا من هذا <c>SpatialReferenceSystem</c> إلى <c>SpatialReferenceSystem</c> آخر. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | إنشاء SRS عمودية. |
| [export_to_wkt()](#export_to_wkt__10) | يعيد تمثيل هذا SRS كسلسلة WKT.<br/>            سلسلة WKT الناتجة ستطابق مواصفة OGC 01-009، عادةً ما تُسمى "WKT1". |
| [get_axis(dimension)](#get_axis_dimension_11) | احصل على [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) الذي يصف البُعد. |
| [get_unit(dimension)](#get_unit_dimension_12) | احصل على [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) للبُعد. |
| [is_equivalent(other)](#is_equivalent_other_13) | يكشف ما إذا كان هذا SRS مكافئًا لـ SRS آخر. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | يحدد ما إذا كان نظاما SRS مكافئين.<br/>            إحداثيات SRS المكافئ نفسها تتطابق مع نفس الموقع على الأرض.<br/>            بعض معلمات SRS المكافئ يمكن أن تكون مختلفة، على سبيل المثال [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | إنشاء نظام إحداثيات مكاني بناءً على رمز EPSG المحدد. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | ينشئ <c>SpatialReferenceSystem</c> جديدًا بناءً على سلسلة WKT (نص معروف جيدًا). |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | ينشئ تحويلًا من هذا <c>SpatialReferenceSystem</c> إلى <c>SpatialReferenceSystem</c> آخر. |
| [validate(error_message)](#validate_error_message_18) | تحديد ما إذا كان هذا SRS صالحًا. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

إنشاء SRS مركب.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم SRS الجديد. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS الرأس لـ SRS الجديد. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | SRS الذيل لـ SRS الجديد. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | المعرّف الذي سيُرفق بـ SRS. إرفاق معرّف لن يغيّر معلمات SRS الأخرى.<br/>            الأمر متروك لك لضمان اتساق المعرف ومعلمات SRS. |

**Returns**

| نوع | وصف |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | SRS مركب جديد. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

إنشاء نظام إحداثيات مكاني بناءً على رمز EPSG المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| epsg | int | رمز EPSG لنظام الإسناد المكاني. |

**Returns**

| نوع | وصف |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | نظام إسناد مكاني جديد مع رمز EPSG المحدد. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

ينشئ <c>SpatialReferenceSystem</c> جديدًا بناءً على سلسلة WKT (نص معروف جيدًا).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| wkt | string | سلسلة WKT. |

**Returns**

| نوع | وصف |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | جديد <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

إنشاء SRS جيوسنترية من معلمات مخصصة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | المعلمات لإنشاء منه. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | المعرّف الذي سيُرفق بـ SRS. إرفاق معرّف لن يغيّر معلمات SRS الأخرى.<br/>            الأمر متروك لك لضمان اتساق المعرف ومعلمات SRS. |

**Returns**

| نوع | وصف |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | نظام إسناد جغرافي مركزي جديد. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

إنشاء SRS جغرافية من معلمات مخصصة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | المعلمات لإنشاء منه. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | المعرّف الذي سيُرفق بـ SRS. إرفاق معرّف لن يغيّر معلمات SRS الأخرى.<br/>            الأمر متروك لك لضمان اتساق المعرف ومعلمات SRS. |

**Returns**

| نوع | وصف |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | نظام إسناد جغرافي جديد. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

إنشاء نظام إحداثيات مكاني محلي.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم نظام الإسناد المكاني. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | المرجع (Datum) المستخدم في نظام الإسناد. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | الوحدة المستخدمة في نظام الإسناد. |
| المحاور | System.Collections.Generic.ICollection<Axis> | المحاور المستخدمة في نظام الإسناد. يجب ألا تكون فارغة. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | المعرّف الذي سيُرفق بـ SRS. إرفاق معرّف لن يغيّر معلمات SRS الأخرى.<br/>            الأمر متروك لك لضمان اتساق المعرف ومعلمات SRS. |

**Returns**

| نوع | وصف |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | نظام إسناد مكاني محلي جديد. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

إنشاء SRS إسقاطية من معلمات مخصصة.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | المعلمات لإنشاء منه. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | المعرّف الذي سيُرفق بـ SRS. إرفاق معرّف لن يغيّر معلمات SRS الأخرى.<br/>            الأمر متروك لك لضمان اتساق المعرف ومعلمات SRS. |

**Returns**

| نوع | وصف |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | نظام إسناد إسقاطي جديد. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

ينشئ تحويلًا من هذا <c>SpatialReferenceSystem</c> إلى <c>SpatialReferenceSystem</c> آخر.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | آخر <c>SpatialReferenceSystem</c>. |

**Returns**

| نوع | وصف |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | تحويل من هذا <c>SpatialReferenceSystem</c> إلى آخر <c>SpatialReferenceSystem</c>. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

إنشاء SRS عمودية.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| الاسم | string | اسم نظام الإسناد. إذا كان <see langword=\"null\" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | المرجع (Datum) المستخدم في نظام الإسناد. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | الوحدة المستخدمة في نظام الإسناد. إذا كان <see langword=\"null\" />, سيتم استخدام [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/). |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | محور باتجاه \"أعلى\" أو \"أسفل\"، يُستخدم في نظام الإسناد. إذا كان <see langword=\"null\" />, سيتم استخدام محور باتجاه الأعلى. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | المعرّف الذي سيُرفق بـ SRS. إرفاق معرّف لن يغيّر معلمات SRS الأخرى.<br/>            الأمر متروك لك لضمان اتساق المعرف ومعلمات SRS. |

**Returns**

| نوع | وصف |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | نظام إسناد عمودي جديد. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

يعيد تمثيل هذا SRS كسلسلة WKT.<br/>            سلسلة WKT الناتجة ستطابق مواصفة OGC 01-009، عادةً ما تُسمى "WKT1".

**Returns**

| نوع | وصف |
| :- | :- |
| string | تمثيل WKT لهذا نظام الإسناد. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

احصل على [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) الذي يصف البُعد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| البُعد | int | عدد الأبعاد. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | محور يصف البُعد. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

احصل على [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) للبُعد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| البُعد | int | عدد الأبعاد. |

**Returns**

| نوع | وصف |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | وحدة البُعد. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

يكشف ما إذا كان هذا SRS مكافئًا لـ SRS آخر. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | نظام إسناد مكاني آخر. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | قيمة منطقية، تشير إلى ما إذا كان هذا SRS مكافئًا لـ SRS آخر. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

يحدد ما إذا كان نظاما SRS مكافئين.<br/>            إحداثيات SRS المكافئ نفسها تتطابق مع نفس الموقع على الأرض.<br/>            بعض معلمات SRS المكافئ يمكن أن تكون مختلفة، على سبيل المثال [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | نظام إسناد مكاني أول. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | نظام إسناد مكاني ثانٍ. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | قيمة منطقية، تشير إلى ما إذا كان نظاما إسناد مكاني اثنان مكافئان. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

إنشاء نظام إحداثيات مكاني بناءً على رمز EPSG المحدد.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| epsg | int | رمز EPSG لنظام الإسناد المكاني. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | عند إرجاع هذه الطريقة <see langword=\"true\" />، تحتوي على SRS بالرمز EPSG المحدد؛ وإلا،<br/>            تحتوي على <see langword=\"null\" />. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان رمز EPSG المحدد معروفًا وتم إنشاء SRS؛ <see langword=\"false\" /> وإلا. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

ينشئ <c>SpatialReferenceSystem</c> جديدًا بناءً على سلسلة WKT (نص معروف جيدًا).

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| wkt | string | سلسلة WKT. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | عند إرجاع هذه الطريقة <see langword=\"true\" />، تحتوي على SRS تم إنشاؤه من WKT؛ وإلا،<br/>            تحتوي على <see langword=\"null\" />. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا تم إنشاء SRS بنجاح؛ <see langword=\"false\" /> وإلا. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

ينشئ تحويلًا من هذا <c>SpatialReferenceSystem</c> إلى <c>SpatialReferenceSystem</c> آخر.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | آخر <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | عند إرجاع هذه الطريقة <see langword=\"true\" />، تحتوي على تحويل؛ وإلا، تحتوي على <see langword=\"null\" />. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | تحويل من هذا <c>SpatialReferenceSystem</c> إلى آخر <c>SpatialReferenceSystem</c>. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

تحديد ما إذا كان هذا SRS صالحًا.

**Parameters:**

| معامل | نوع | وصف |
| :- | :- | :- |
| error_message | سلسلة | إذا أعادت الطريقة <see langword=\"false\" />، فإن هذا هو وصف عدم الصلاحية. |

**Returns**

| نوع | وصف |
| :- | :- |
| bool | <see langword=\"true\" /> إذا كان SRS صالحًا، <see langword=\"false\" /> وإلا. |


