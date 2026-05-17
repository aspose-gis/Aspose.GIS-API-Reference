---
title: "GeographicDatum Sınıfı"
type: docs
weight: 70
url: /tr/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | Yeni bir örnek oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Ellipsoid, bu datumda Dünya'yı yaklaşık olarak temsil etmek için kullanılır. |
| epsg_code | int | r | Eğer bu nesnenin tanımlayıcısı EPSG tanımlayıcısıysa - kodunu döndür. Aksi takdirde -1 döndür. |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | ETRS 89 datum. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Bu tanımlanabilir nesnenin tanımlayıcısı. |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | NAD 83 datum. |
| ad | string | r | Bu nesnenin adı. |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | OSGB 1936 datum. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | Bu datumdaki koordinatları WGS84 datumundaki koordinatlara dönüştürmek için kullanılabilecek BursaWolfParamters. |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 72 datum. |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 84 datum. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | İki datumun eşit olup olmadığını belirler.<br/>            Eşit datumların aynı koordinatları Dünya üzerindeki aynı yeri gösterir.<br/>            Eşit datumların bazı parametreleri farklı olabilir, örneğin [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [is_equivalent(other)](#is_equivalent_other_2) | İki datumun eşit olup olmadığını belirler.<br/>            Eşit datumların aynı koordinatları Dünya üzerindeki aynı yeri gösterir.<br/>            Eşit datumların bazı parametreleri farklı olabilir, örneğin [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

Yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Bu datumun adı. |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Bu datumun ellipsoidi. Null olamaz. |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | Bu datumdaki koordinatları WGS84 datumundaki koordinatlara dönüştürmek için bursa wolf formülüne verilebilecek parametreler.<br/>            Bu datum WGS84'e yakınsa ve dönüşüm gerekmezse, tüm değerleri 0 olarak ayarlanmış bursa wolf parametrelerini geçin.<br/>            Null ise, ToWgs84 [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) parametrelerine ayarlanacaktır. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Bu datumun tanımlayıcısı. |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

İki datumun eşit olup olmadığını belirler.<br/>            Eşit datumların aynı koordinatları Dünya üzerindeki aynı yeri gösterir.<br/>            Eşit datumların bazı parametreleri farklı olabilir, örneğin [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | İlk datum. |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | İkinci datum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | İki datumun eşit olup olmadığını gösteren bool değeri. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

İki datumun eşit olup olmadığını belirler.<br/>            Eşit datumların aynı koordinatları Dünya üzerindeki aynı yeri gösterir.<br/>            Eşit datumların bazı parametreleri farklı olabilir, örneğin [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | Diğer datum. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | İki datumun eşit olup olmadığını gösteren bool değeri. |


