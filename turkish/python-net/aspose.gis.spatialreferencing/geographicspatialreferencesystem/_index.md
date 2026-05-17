---
title: "GeographicSpatialReferenceSystem Sınıfı"
type: docs
weight: 80
url: /tr/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/
---

**Summary:** A Geographic SRS is an SRS that is based on longitude and latitude.<br/>            A Geographic SRS can be two dimensional or three dimensional.<br/>            If geographic SRS is three dimensional, then it is actually a compound SRS of two dimensional SRS and vertical SRS.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.GeographicSpatialReferenceSystem

**Inheritance:** SpatialReferenceSystem

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| angular_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | Bu SRS'de açısal boyutlar için kullanılan birim. |
| as_compound | [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | r | Bu SRS'yi [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/)&#39;e dönüştürülmüş olarak döndürür.<br/>            Dönüşümün mümkün olup olmadığını öğrenmek için [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) kullanın. |
| as_geocentric | [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | r | Bu SRS'yi [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/)&#39;e dönüştürülmüş olarak döndürür.<br/>            Dönüşümün mümkün olup olmadığını öğrenmek için [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) kullanın. |
| as_geographic | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | Bunu döndürür. |
| as_local | [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | r | Bu SRS'yi [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) olarak dönüştürür.<br/>            Dönüşümün mümkün olup olmadığını öğrenmek için [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) kullanın. |
| as_projected | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Bu SRS'yi [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) olarak dönüştürür.<br/>            Dönüşümün mümkün olup olmadığını öğrenmek için [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) kullanın. |
| as_vertical | [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | r | Bu SRS'yi [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) olarak dönüştürür.<br/>            Dönüşümün mümkün olup olmadığını öğrenmek için [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) kullanın. |
| axises_order | [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder) | r | Bu SRS'deki eksen sırası.<br/>            Eğer bu SRS geçerli değil ve eksen yönleri yanlışsa, [GeographicAxisesOrder.INVALID](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) döndürülür. |
| dimensions_count | int | r | Bu SRS'deki boyut sayısını döndürür. Coğrafi SRS için bu şu olabilir:<br/>            iki - eğer tek bir coğrafi SRS ise.<br/>            üç - eğer bu bir bileşik SRS ise, tek bir iki boyutlu coğrafi SRS ve üçüncü boyutu ekleyen dikey SRS'den oluşur. |
| epsg_code | int | r | Eğer bu nesnenin tanımlayıcısı EPSG tanımlayıcısıysa - kodunu döndür. Aksi takdirde -1 döndür. |
| etrs89 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | ETRS 89 (EPSG:4258) mekânsal referans sistemi. |
| etrs_89_lambert_azimuthal_equal_area [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / ETRS Lambert Azimut Eşit Alan (EPSG:3035) mekânsal referans sistemi. |
| etrs_89_lambert_conformal_conic [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | ETRS 89 / Lambert Konformal Konik (EPSG:3034) mekânsal referans sistemi. |
| geographic_datum | [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum) | r | Bu SRS'nin coğrafi datumunu döndürür. |
| has_geographic_datum | bool | r | Coğrafi SRS her zaman baş meridyeni içerdiği için <see langword=\"true\" /> döndürür. |
| has_prime_meridian | bool | r | Coğrafi SRS her zaman baş meridyeni içerdiği için <see langword=\"true\" /> döndürür. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Bu tanımlanabilir nesnenin tanımlayıcısı. |
| is_compound | bool | r | Bu SRS'nin birleşik (iki SRS'nin birleşimi) olup olmadığını döndürür.<br/>            Birleşik SRS'de aşağıdaki SRS kombinasyonları geçerli kabul edilir:<br/>            Coğrafi SRS + Dikey SRS, bu durumda birleşik SRS'nin türü [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) olacaktır.<br/>            Projeksiyonlu SRS + Dikey SRS, bu durumda birleşik SRS'nin türü [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) olacaktır.<br/>            Eğer SRS kombinasyonu farklıysa, birleşik SRS'nin türü [SpatialReferenceSystemType.UNKNOWN](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) olacaktır. |
| is_single | bool | r | Bu SRS'nin tek olup olmadığını döndürür (iki SRS'nin birleşimi değil). |
| is_valid | bool | r | Aynı <see cref="M:Aspose.Gis.SpatialReferencing.SpatialReferenceSystem.Validate(string@)" />, ancak hata mesajı döndürmez. |
| nad83 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | NAD 83 (EPSG:4269) mekânsal referans sistemi. |
| ad | string | r | Bu nesnenin adı. |
| osgb36 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | OSGB 36 (EPSG:4277) mekânsal referans sistemi. |
| osgb_36_british_national_grid [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | OSGB 36 / Britanya Ulusal Izgara (EPSG:27700) mekânsal referans sistemi. |
| prime_meridian | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | Bu SRS'nin baş meridyenini döndürür. |
| type | [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype) | r | [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) döndürür. |
| web_mercator [static] | [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | r | Web Mercator (EPSG:3857) uzamsal referans sistemi. |
| wgs72 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 72 (EPSG:4322) uzamsal referans sistemi. |
| wgs84 [static] | [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | r | WGS 84 (EPSG:4326) uzamsal referans sistemi. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_compound(name, head, tail, identifier)](#create_compound_name_head_tail_identifier_1) | Bileşik SRS oluştur. |
| [create_from_epsg(epsg)](#create_from_epsg_epsg_2) | Belirtilen EPSG koduna dayalı bir uzamsal referans sistemi oluştur. |
| [create_from_wkt(wkt)](#create_from_wkt_wkt_3) | WKT (Well-Known Text) dizesine dayalı yeni bir <c>SpatialReferenceSystem</c> oluşturur. |
| [create_geocentric(parameters, identifier)](#create_geocentric_parameters_identifier_4) | Özel parametrelerden jeosantrik SRS oluştur. |
| [create_geographic(parameters, identifier)](#create_geographic_parameters_identifier_5) | Özel parametrelerden coğrafi SRS oluştur. |
| [create_local(name, datum, unit, axises, identifier)](#create_local_name_datum_unit_axises_identifier_6) | Yerel Uzamsal Referans Sistemi oluştur. |
| [create_projected(parameters, identifier)](#create_projected_parameters_identifier_7) | Özel parametrelerden projeksiyonlu SRS oluştur. |
| [create_transformation_to(target_srs)](#create_transformation_to_target_srs_8) | Bu <c>SpatialReferenceSystem</c>'den başka bir <c>SpatialReferenceSystem</c>'e dönüşüm oluşturur. |
| [create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)](#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9) | Dikey SRS oluştur. |
| [export_to_wkt()](#export_to_wkt__10) | Bu SRS'nin WKT dizesi olarak temsilini döndürür.<br/>            Sonuç WKT dizesi OGC 01-009 spesifikasyonuna uygun olacaktır, genellikle "WKT1" olarak adlandırılır. |
| [get_axis(dimension)](#get_axis_dimension_11) | Boyutu tanımlayan [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) alın. |
| [get_unit(dimension)](#get_unit_dimension_12) | Boyutun [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) değerini alın. |
| [is_equivalent(other)](#is_equivalent_other_13) | Bu SRS'nin diğer SRS ile eşdeğer olup olmadığını algılar. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [is_equivalent(srs1, srs2)](#is_equivalent_srs1_srs2_14) | İki SRS'nin eşdeğer olup olmadığını belirler.<br/>            Eşdeğer SRS'lerin aynı koordinatları Dünya üzerindeki aynı yeri gösterir.<br/>            Eşdeğer SRS'lerin bazı parametreleri farklı olabilir, örneğin [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/). |
| [try_create_from_epsg(epsg, value)](#try_create_from_epsg_epsg_value_15) | Belirtilen EPSG koduna dayalı bir uzamsal referans sistemi oluştur. |
| [try_create_from_wkt(wkt, value)](#try_create_from_wkt_wkt_value_16) | WKT (Well-Known Text) dizesine dayalı yeni bir <c>SpatialReferenceSystem</c> oluşturur. |
| [try_create_transformation_to(target_srs, value)](#try_create_transformation_to_target_srs_value_17) | Bu <c>SpatialReferenceSystem</c>'den başka bir <c>SpatialReferenceSystem</c>'e dönüşüm oluşturur. |
| [validate(error_message)](#validate_error_message_18) | Bu SRS'nin geçerli olup olmadığını belirle. |


### Method: create_compound(name, head, tail, identifier)  [static] {#create_compound_name_head_tail_identifier_1}


```
 create_compound(name, head, tail, identifier) 
```

Bileşik SRS oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Yeni SRS'nin adı. |
| head | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Yeni SRS'nin baş SRS'si. |
| tail | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Yeni SRS'nin kuyruk SRS'si. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS'ye eklenecek tanımlayıcı. Bir tanımlayıcı eklemek diğer SRS parametrelerini değiştirmez.<br/>            Tanımlayıcı ile SRS parametrelerinin tutarlılığını sağlamak sizin sorumluluğunuzdadır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem) | Yeni Bileşik SRS. |


### Method: create_from_epsg(epsg)  [static] {#create_from_epsg_epsg_2}


```
 create_from_epsg(epsg) 
```

Belirtilen EPSG koduna dayalı bir uzamsal referans sistemi oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| epsg | int | Coğrafi referans sisteminin EPSG kodu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Belirtilen EPSG koduyla yeni bir coğrafi referans sistemi. |


### Method: create_from_wkt(wkt)  [static] {#create_from_wkt_wkt_3}


```
 create_from_wkt(wkt) 
```

WKT (Well-Known Text) dizesine dayalı yeni bir <c>SpatialReferenceSystem</c> oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| wkt | string | WKT dizesi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Yeni <c>SpatialReferenceSystem</c>. |


### Method: create_geocentric(parameters, identifier)  [static] {#create_geocentric_parameters_identifier_4}


```
 create_geocentric(parameters, identifier) 
```

Özel parametrelerden jeosantrik SRS oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| parameters | [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters) | Oluşturulacak parametreler. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS'ye eklenecek tanımlayıcı. Bir tanımlayıcı eklemek diğer SRS parametrelerini değiştirmez.<br/>            Tanımlayıcı ile SRS parametrelerinin tutarlılığını sağlamak sizin sorumluluğunuzdadır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem) | Yeni Geocentric SRS. |


### Method: create_geographic(parameters, identifier)  [static] {#create_geographic_parameters_identifier_5}


```
 create_geographic(parameters, identifier) 
```

Özel parametrelerden coğrafi SRS oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| parameters | [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters) | Oluşturulacak parametreler. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS'ye eklenecek tanımlayıcı. Bir tanımlayıcı eklemek diğer SRS parametrelerini değiştirmez.<br/>            Tanımlayıcı ile SRS parametrelerinin tutarlılığını sağlamak sizin sorumluluğunuzdadır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem) | Yeni Geographic SRS. |


### Method: create_local(name, datum, unit, axises, identifier)  [static] {#create_local_name_datum_unit_axises_identifier_6}


```
 create_local(name, datum, unit, axises, identifier) 
```

Yerel Uzamsal Referans Sistemi oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Coğrafi Referans Sisteminin adı. |
| datum | [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum) | SRS içinde kullanılacak datum. |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS içinde kullanılacak birim. |
| eksenler | System.Collections.Generic.ICollection<Axis> | SRS içinde kullanılacak eksenler. Boş olmamalıdır. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS'ye eklenecek tanımlayıcı. Bir tanımlayıcı eklemek diğer SRS parametrelerini değiştirmez.<br/>            Tanımlayıcı ile SRS parametrelerinin tutarlılığını sağlamak sizin sorumluluğunuzdadır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem) | Yeni Yerel Coğrafi Referans Sistemi. |


### Method: create_projected(parameters, identifier)  [static] {#create_projected_parameters_identifier_7}


```
 create_projected(parameters, identifier) 
```

Özel parametrelerden projeksiyonlu SRS oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| parameters | [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters) | Oluşturulacak parametreler. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS'ye eklenecek tanımlayıcı. Bir tanımlayıcı eklemek diğer SRS parametrelerini değiştirmez.<br/>            Tanımlayıcı ile SRS parametrelerinin tutarlılığını sağlamak sizin sorumluluğunuzdadır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem) | Yeni Projected SRS. |


### Method: create_transformation_to(target_srs) {#create_transformation_to_target_srs_8}


```
 create_transformation_to(target_srs) 
```

Bu <c>SpatialReferenceSystem</c>'den başka bir <c>SpatialReferenceSystem</c>'e dönüşüm oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Başka bir <c>SpatialReferenceSystem</c>. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Bu <c>SpatialReferenceSystem</c>'den başka bir <c>SpatialReferenceSystem</c>'e dönüşüm. |


### Method: create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier)  [static] {#create_vertical_name_vertical_datum_vertical_unit_vertical_axis_identifier_9}


```
 create_vertical(name, vertical_datum, vertical_unit, vertical_axis, identifier) 
```

Dikey SRS oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | SRS'nin adı. Eğer <see langword="null" />. |
| vertical_datum | [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum) | SRS içinde kullanılacak datum. |
| vertical_unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | SRS içinde kullanılacak birim. Eğer <see langword="null" /> ise, [Unit.meter](/psd/python-net/aspose.gis.spatialreferencing/unit/) kullanılacaktır. |
| vertical_axis | [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | SRS içinde kullanılacak "up" veya "down" yönlü eksen. Eğer <see langword="null" /> ise, up yönlü eksen kullanılacaktır. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | SRS'ye eklenecek tanımlayıcı. Bir tanımlayıcı eklemek diğer SRS parametrelerini değiştirmez.<br/>            Tanımlayıcı ile SRS parametrelerinin tutarlılığını sağlamak sizin sorumluluğunuzdadır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem) | Yeni Dikey SRS. |


### Method: export_to_wkt() {#export_to_wkt__10}


```
 export_to_wkt() 
```

Bu SRS'nin WKT dizesi olarak temsilini döndürür.<br/>            Sonuç WKT dizesi OGC 01-009 spesifikasyonuna uygun olacaktır, genellikle "WKT1" olarak adlandırılır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| string | Bu SRS'nin WKT temsili. |


### Method: get_axis(dimension) {#get_axis_dimension_11}


```
 get_axis(dimension) 
```

Boyutu tanımlayan [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) alın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| boyut | int | Boyut sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis) | Boyutu tanımlayan eksen. |


### Method: get_unit(dimension) {#get_unit_dimension_12}


```
 get_unit(dimension) 
```

Boyutun [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) değerini alın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| boyut | int | Boyut sayısı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | Boyut birimi. |


### Method: is_equivalent(other) {#is_equivalent_other_13}


```
 is_equivalent(other) 
```

Bu SRS'nin diğer SRS ile eşdeğer olup olmadığını algılar. [SpatialReferenceSystem.is_equivalent(srs1, srs2)](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Diğer SRS. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | bool değeri, bu SRS'nin diğer SRS'ye eşit olup olmadığını gösterir. |


### Method: is_equivalent(srs1, srs2)  [static] {#is_equivalent_srs1_srs2_14}


```
 is_equivalent(srs1, srs2) 
```

İki SRS'nin eşdeğer olup olmadığını belirler.<br/>            Eşdeğer SRS'lerin aynı koordinatları Dünya üzerindeki aynı yeri gösterir.<br/>            Eşdeğer SRS'lerin bazı parametreleri farklı olabilir, örneğin [IdentifiableObject.name](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/).

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| srs1 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | İlk SRS. |
| srs2 | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | İkinci SRS. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | bool değeri, iki SRS'nin eşit olup olmadığını gösterir. |


### Method: try_create_from_epsg(epsg, value)  [static] {#try_create_from_epsg_epsg_value_15}


```
 try_create_from_epsg(epsg, value) 
```

Belirtilen EPSG koduna dayalı bir uzamsal referans sistemi oluştur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| epsg | int | Coğrafi referans sisteminin EPSG kodu. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Bu yöntem <see langword=\"true\" /> döndürdüğünde, belirtilen EPSG koduna sahip bir SRS içerir; aksi takdirde, <see langword=\"null\" /> içerir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> belirtilen EPSG kodu biliniyorsa ve SRS oluşturulduysa; aksi takdirde <see langword=\"false\" />. |


### Method: try_create_from_wkt(wkt, value)  [static] {#try_create_from_wkt_wkt_value_16}


```
 try_create_from_wkt(wkt, value) 
```

WKT (Well-Known Text) dizesine dayalı yeni bir <c>SpatialReferenceSystem</c> oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| wkt | string | WKT dizesi. |
| value | [SpatialReferenceSystem[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Bu yöntem <see langword=\"true\" /> döndürdüğünde, WKT'den oluşturulmuş bir SRS içerir; aksi takdirde, <see langword=\"null\" /> içerir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> SRS başarıyla oluşturulduysa; aksi takdirde <see langword=\"false\" />. |


### Method: try_create_transformation_to(target_srs, value) {#try_create_transformation_to_target_srs_value_17}


```
 try_create_transformation_to(target_srs, value) 
```

Bu <c>SpatialReferenceSystem</c>'den başka bir <c>SpatialReferenceSystem</c>'e dönüşüm oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem) | Başka bir <c>SpatialReferenceSystem</c>. |
| value | [SpatialReferenceSystemTransformation[]](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation) | Bu yöntem <see langword=\"true\" /> döndürdüğünde, bir dönüşüm içerir; aksi takdirde <see langword=\"null\" /> içerir. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu <c>SpatialReferenceSystem</c>'den başka bir <c>SpatialReferenceSystem</c>'e dönüşüm. |


### Method: validate(error_message) {#validate_error_message_18}


```
 validate(error_message) 
```

Bu SRS'nin geçerli olup olmadığını belirle.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| error_message | Dize | Metod <see langword=\"false\" /> döndürürse, bu geçersizlik açıklamasıdır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | <see langword=\"true\" /> SRS geçerliyse, aksi takdirde <see langword=\"false\" />. |


