---
title: "فئة GeographicDatum"
type: docs
weight: 70
url: /ar/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **الوصف** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | ينشئ نسخة جديدة. |
## **Properties**
| **Name** | **Type** | **Access** | **الوصف** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid، يُستخدم في هذا المرجع لتقريب الأرض. |
| epsg_code | int | r | إذا كان معرف هذا الكائن هو معرف EPSG - أعد رمزه. وإلا - أعد -1. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | مرجع ETRS 89. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | معرف هذا الكائن القابل للتعريف. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | مرجع NAD 83. |
| الاسم | string | r | اسم هذا الكائن. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | مرجع OSGB 1936. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | BursaWolfParamters التي يمكن استخدامها لتحويل الإحداثيات في هذا المرجع إلى إحداثيات في مرجع WGS84. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | مرجع WGS 72. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | مرجع WGS 84. |
## **Methods**
| **Name** | **الوصف** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | يحدد ما إذا كان مرجعان متكافئان.<br/>            تتطابق إحداثيات المرجع المتكافئ نفسها مع نفس الموقع على الأرض.<br/>            قد تكون بعض معلمات المرجع المتكافئ مختلفة، على سبيل المثال [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | يحدد ما إذا كان مرجعان متكافئان.<br/>            تتطابق إحداثيات المرجع المتكافئ نفسها مع نفس الموقع على الأرض.<br/>            قد تكون بعض معلمات المرجع المتكافئ مختلفة، على سبيل المثال [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

ينشئ نسخة جديدة.

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| الاسم | string | اسم هذا المرجع. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Ellipsoid لهذا المرجع. لا يمكن أن يكون فارغًا. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | المعلمات التي يمكن إعطاؤها لصيغة bursa wolf لتحويل الإحداثيات في هذا المرجع إلى إحداثيات في مرجع WGS84.<br/>            إذا كان هذا المرجع قريبًا من WGS84 ولا حاجة للتحويل، مرّر معلمات bursa wolf مع تعيين جميع القيم إلى 0.<br/>            إذا كان فارغًا، سيتم تعيين ToWgs84 إلى معلمات [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/). |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | معرّف هذا المرجع. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

يحدد ما إذا كان مرجعان متكافئان.<br/>            تتطابق إحداثيات المرجع المتكافئ نفسها مع نفس الموقع على الأرض.<br/>            قد تكون بعض معلمات المرجع المتكافئ مختلفة، على سبيل المثال [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | المرجع الأول. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | المرجع الثاني. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | قيمة bool، تشير إلى ما إذا كان مرجعان متكافئان. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

يحدد ما إذا كان مرجعان متكافئان.<br/>            تتطابق إحداثيات المرجع المتكافئ نفسها مع نفس الموقع على الأرض.<br/>            قد تكون بعض معلمات المرجع المتكافئ مختلفة، على سبيل المثال [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| معامل | نوع | الوصف |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | المرجع الآخر. |

**Returns**

| نوع | الوصف |
| :- | :- |
| bool | قيمة bool، تشير إلى ما إذا كان مرجعان متكافئان. |


