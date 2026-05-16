---
title: "GeographicSpatialReferenceSystem クラス"
type: docs
weight: 80
url: /ja/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/
---

**Summary:** A Geographic SRS is an SRS that is based on longitude and latitude.<br/>            A Geographic SRS can be two dimensional or three dimensional.<br/>            If geographic SRS is three dimensional, then it is actually a compound SRS of two dimensional SRS and vertical SRS.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | この SRS で角度次元に使用される単位です。 |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | このSRSを [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) に変換して返します。<br/>            変換が可能かどうかは [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) を使用して確認してください。 |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | このSRSを [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) に変換して返します。<br/>            変換が可能かどうかは [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) を使用して確認してください。 |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | このオブジェクトを返します。 |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | この SRS を [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) に変換して返します。<br/>            変換が可能かどうかを確認するには、[SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) を使用してください。 |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | この SRS を [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) に変換して返します。<br/>            変換が可能かどうかを確認するには、[SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) を使用してください。 |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | この SRS を [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) に変換して返します。<br/>            変換が可能かどうかを確認するには、[SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) を使用してください。 |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r | この SRS の軸順序です。<br/>            この SRS が有効でなく、軸方向が間違っている場合は、[GeographicAxisesOrder.INVALID](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) が返されます。 |
| dimensions_count | int | r | この SRS の次元数を返します。地理的 SRS の場合、次のいずれかになります：<br/>            2 つ - この SRS が単一の地理的 SRS の場合。<br/>            3 つ - この SRS が単一の 2 次元地理的 SRS と垂直 SRS から構成され、3 次元を追加する複合 SRS の場合。 |
| epsg_code | int | r | このオブジェクトの識別子が EPSG 識別子の場合はそのコードを返します。そうでない場合は -1 を返します。 |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) 空間参照系。 |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS ランバート方位等積 (EPSG:3035) 空間参照系。 |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ランバート正角円錐 (EPSG:3034) 空間参照系。 |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | この SRS の地理データムを返します。 |
| has_geographic_datum | bool | r | 地理的 SRS は常に本初子午線を持つため、<see langword="true" /> を返します。 |
| has_prime_meridian | bool | r | 地理的 SRS は常に本初子午線を持つため、<see langword="true" /> を返します。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | この識別可能オブジェクトの識別子。 |
| is_compound | bool | r | この SRS が複合かどうか（2 つの SRS の合成）を返します。<br/>            複合 SRS で有効とみなされる SRS の組み合わせは次のとおりです：<br/>            地理的 SRS + 垂直 SRS の場合、複合 SRS のタイプは [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) になります。<br/>            投影 SRS + 垂直 SRS の場合、複合 SRS のタイプは [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) になります。<br/>            組み合わせが異なる場合、複合 SRS のタイプは [SpatialReferenceSystemType.UNKNOWN](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) になります。 |
| is_single | bool | r | この SRS が単一かどうか（2 つの SRS の合成でないか）を返します。 |
| is_valid | bool | r | 次と同じです <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" />, ただしエラーメッセージは返しません。 |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) 空間参照系。 |
| 名前 | string | r | このオブジェクトの名前。 |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) 空間参照系。 |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / ブリティッシュ・ナショナル・グリッド (EPSG:27700) 空間参照系。 |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | この SRS の本初子午線を返します。 |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) を返します。 |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Web Mercator (EPSG:3857) 空間参照系。 |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 72 (EPSG:4322) 空間参照系。 |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 84 (EPSG:4326) 空間参照系。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | 複合 SRS を作成します。 |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | 指定された EPSG コードに基づく空間参照系を作成します。 |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | WKT (Well-Known Text) 文字列に基づいて新しい <c>SpatialReferenceSystem</c> を作成します。 |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | カスタムパラメータからジオセントリック SRS を作成します。 |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | カスタムパラメータから地理的 SRS を作成します。 |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | ローカル空間参照系を作成します。 |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | カスタムパラメータから投影 SRS を作成します。 |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | この <c>SpatialReferenceSystem</c> から別の <c>SpatialReferenceSystem</c> への変換を作成します。 |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | 垂直 SRS を作成します。 |
| [export_to_wkt()](#export_to_wkt__10) | この SRS の表現を WKT 文字列として返します。<br/>            結果の WKT 文字列は OGC 01-009 仕様に一致し、通常は "WKT1" と呼ばれます。 |
| [get_axis(dimension)](#get_axis_dimension_11) | 次元を記述する [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) を取得します。 |
| [get_unit(dimension)](#get_unit_dimension_12) | 次元の [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) を取得します。 |
| [is_equivalent(other)](#is_equivalent_other_13) | この SRS が他の SRS と等価かどうかを検出します。 [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)。 |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | 二つの SRS が等価かどうかを判定します。<br/>            等価な SRS の同じ座標は地球上の同じ場所に対応します。<br/>            等価な SRS のパラメータの一部は異なる場合があります。例として [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) があります。 |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | 指定された EPSG コードに基づく空間参照系を作成します。 |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | WKT (Well-Known Text) 文字列に基づいて新しい <c>SpatialReferenceSystem</c> を作成します。 |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | この <c>SpatialReferenceSystem</c> から別の <c>SpatialReferenceSystem</c> への変換を作成します。 |
| [validate(error_message)](#validate_error_message_18) | この SRS が有効かどうかを判定します。 |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

複合 SRS を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 新しい SRS の名前。 |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 新しい SRS のヘッド SRS。 |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 新しい SRS のテイル SRS。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS に付与される識別子。識別子を付与しても他の SRS パラメータは変更されません。<br/>            識別子と SRS パラメータの整合性を確保するかどうかはユーザー次第です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | 新しい複合 SRS。 |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

指定された EPSG コードに基づく空間参照系を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| epsg | int | 空間参照系の EPSG コード。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 指定された EPSG コードを持つ新しい空間参照系。 |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

WKT (Well-Known Text) 文字列に基づいて新しい <c>SpatialReferenceSystem</c> を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| wkt | string | WKT 文字列。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 新しい <c>SpatialReferenceSystem</c>。 |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

カスタムパラメータからジオセントリック SRS を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | 作成元のパラメータ。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS に付与される識別子。識別子を付与しても他の SRS パラメータは変更されません。<br/>            識別子と SRS パラメータの整合性を確保するかどうかはユーザー次第です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | 新しいジオセントリック SRS。 |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

カスタムパラメータから地理的 SRS を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | 作成元のパラメータ。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS に付与される識別子。識別子を付与しても他の SRS パラメータは変更されません。<br/>            識別子と SRS パラメータの整合性を確保するかどうかはユーザー次第です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | 新しいジオグラフィック SRS。 |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

ローカル空間参照系を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | 空間参照系の名前。 |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | SRS で使用される測地系。 |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS で使用される単位。 |
| 軸 | System.Collections.Generic.ICollection<Axis> | SRS で使用される軸。空であってはなりません |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS に付与される識別子。識別子を付与しても他の SRS パラメータは変更されません。<br/>            識別子と SRS パラメータの整合性を確保するかどうかはユーザー次第です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | 新しいローカル空間参照系。 |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

カスタムパラメータから投影 SRS を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | 作成元のパラメータ。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS に付与される識別子。識別子を付与しても他の SRS パラメータは変更されません。<br/>            識別子と SRS パラメータの整合性を確保するかどうかはユーザー次第です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | 新しい投影 SRS。 |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

この <c>SpatialReferenceSystem</c> から別の <c>SpatialReferenceSystem</c> への変換を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 別の <c>SpatialReferenceSystem</c>。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | この <c>SpatialReferenceSystem</c> から別の <c>SpatialReferenceSystem</c> への変換。 |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

垂直 SRS を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | SRS の名前。<see langword="null" /> の場合。 |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | SRS で使用される測地系。 |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS で使用される単位。<see langword="null" /> の場合、[Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) が使用されます。 |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | 「up」または「down」方向を持つ軸で、SRS で使用されます。<see langword="null" /> の場合、up 方向の軸が使用されます。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS に付与される識別子。識別子を付与しても他の SRS パラメータは変更されません。<br/>            識別子と SRS パラメータの整合性を確保するかどうかはユーザー次第です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | 新しい垂直 SRS。 |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

この SRS の表現を WKT 文字列として返します。<br/>            結果の WKT 文字列は OGC 01-009 仕様に一致し、通常は "WKT1" と呼ばれます。

**Returns**

| 型 | 説明 |
| :- | :- |
| string | この SRS の WKT 表現。 |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

次元を記述する [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) を取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 次元 | int | 次元の数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | 次元を表す軸。 |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

次元の [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) を取得します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 次元 | int | 次元の数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | 次元の単位。 |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

この SRS が他の SRS と等価かどうかを検出します。 [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/)。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 他の SRS。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | この SRS が他の SRS と等価かどうかを示す bool 値。 |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

二つの SRS が等価かどうかを判定します。<br/>            等価な SRS の同じ座標は地球上の同じ場所に対応します。<br/>            等価な SRS のパラメータの一部は異なる場合があります。例として [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) があります。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 最初の SRS。 |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 2 番目の SRS。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 2 つの SRS が等価かどうかを示す bool 値。 |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

指定された EPSG コードに基づく空間参照系を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| epsg | int | 空間参照系の EPSG コード。 |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | このメソッドが <see langword=\"true\" /> を返す場合、指定された EPSG コードを持つ SRS が含まれます。そうでない場合、<br/>            <see langword=\"null\" /> が含まれます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 指定された EPSG コードが既知で SRS が作成された場合は <see langword=\"true\" />、それ以外の場合は <see langword=\"false\" />。 |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

WKT (Well-Known Text) 文字列に基づいて新しい <c>SpatialReferenceSystem</c> を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| wkt | string | WKT 文字列。 |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | このメソッドが <see langword=\"true\" /> を返す場合、WKT から作成された SRS が含まれます。そうでない場合、<br/>            <see langword=\"null\" /> が含まれます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | SRS が正常に作成された場合は <see langword=\"true\" />、それ以外の場合は <see langword=\"false\" />。 |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

この <c>SpatialReferenceSystem</c> から別の <c>SpatialReferenceSystem</c> への変換を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | 別の <c>SpatialReferenceSystem</c>。 |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | このメソッドが <see langword=\"true\" /> を返す場合、変換が含まれます。そうでない場合、<see langword=\"null\" /> が含まれます。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | この <c>SpatialReferenceSystem</c> から別の <c>SpatialReferenceSystem</c> への変換。 |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

この SRS が有効かどうかを判定します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| error_message | 文字列 | メソッドが <see langword=\"false\" /> を返す場合、これは無効性の説明です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | SRS が有効な場合は <see langword=\"true\" />、それ以外の場合は <see langword=\"false\" />。 |


