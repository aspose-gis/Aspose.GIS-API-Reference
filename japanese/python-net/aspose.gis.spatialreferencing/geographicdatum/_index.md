---
title: "GeographicDatum クラス"
type: docs
weight: 70
url: /ja/python-net/aspose.gis.spatialreferencing/geographicdatum/
---

**Summary:** Geographic datum relates longitude and latitude to particular place on earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier)](#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | この測地系で地球を近似するために使用される楕円体。 |
| epsg_code | int | r | このオブジェクトの識別子が EPSG 識別子の場合はそのコードを返します。そうでない場合は -1 を返します。 |
| etrs89 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | ETRS 89 測地系。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | この識別可能オブジェクトの識別子。 |
| nad83 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | NAD 83 測地系。 |
| 名前 | string | r | このオブジェクトの名前。 |
| osgb36 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | OSGB 1936 測地系。 |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | r | この測地系の座標を WGS84 測地系の座標に変換するために使用できる BursaWolfParamters。 |
| wgs72 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 72 測地系。 |
| wgs84 [static] | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | WGS 84 測地系。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [is_equivalent(datum1, datum2)](#is_equivalent_datum1_datum2_1) | 二つの測地系が等価かどうかを判定します。<br/>            等価な測地系の同じ座標は地球上の同じ場所に対応します。<br/>            等価な測地系のいくつかのパラメータは異なる場合があります。例として [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) を参照してください。 |
| [is_equivalent(other)](#is_equivalent_other_2) | 二つの測地系が等価かどうかを判定します。<br/>            等価な測地系の同じ座標は地球上の同じ場所に対応します。<br/>            等価な測地系のいくつかのパラメータは異なる場合があります。例として [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) を参照してください。 |


### Constructor: GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) {#GeographicDatum_name_ellipsoid_to_wgs_84_parameters_identifier_1}


```
 GeographicDatum(name, ellipsoid, to_wgs_84_parameters, identifier) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | この測地系の名前。 |
| ellipsoid | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | この測地系の楕円体。null にできません。 |
| to_wgs_84_parameters | [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters) | この測地系の座標を WGS84 測地系の座標に変換するために、bursa wolf 公式に与えることができるパラメータ。<br/>            この測地系が WGS84 に近く変換が不要な場合は、すべての値を 0 に設定した bursa wolf パラメータを渡してください。<br/>            null の場合、ToWgs84 は [BursaWolfParameters.is_null](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) パラメータに設定されます。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | この測地系の識別子。 |

### Method: is_equivalent(datum1, datum2)  [static] {#is_equivalent_datum1_datum2_1}


```
 is_equivalent(datum1, datum2) 
```

二つの測地系が等価かどうかを判定します。<br/>            等価な測地系の同じ座標は地球上の同じ場所に対応します。<br/>            等価な測地系のいくつかのパラメータは異なる場合があります。例として [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) を参照してください。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| datum1 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | 最初の測地系。 |
| datum2 | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | 第二の測地系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 二つの測地系が等価かどうかを示す bool 値。 |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

二つの測地系が等価かどうかを判定します。<br/>            等価な測地系の同じ座標は地球上の同じ場所に対応します。<br/>            等価な測地系のいくつかのパラメータは異なる場合があります。例として [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) を参照してください。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | 他の測地系。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 二つの測地系が等価かどうかを示す bool 値。 |


