---
title: "DatabaseQueryDataSourceBuilder Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/
---

**Summary:** Provides the ability to configure a query to database to to extract geospatial information.

**Module:** [aspose.gis.formats.database](/psd/python-net/aspose.gis.formats.database/)

**Full Name:** aspose.gis.formats.database.DatabaseQueryDataSourceBuilder

**Aspose.PSD Version:** 25.9.0

## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_attribute(name, type)](#add_attribute_name_type_1) | Özellik özniteliği için bilgi içerecek alanın adını yapılandırır. |
| [as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func)](#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2) | Ortaya çıkan katmanı değişiklikleri izlemek için yapılandırın ve yapılan değişiklikleri senkronize etmek için bir veri kaynağı oluşturun. |
| [build()](#build__3) | Yöntem, [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) uygulamasını alır. |
| [geometry_field(name)](#geometry_field_name_4) | Geometrinin çıkarılacağı alanın adını yapılandırır. |
| [srid_field(name)](#srid_field_name_5) | Mekansal referans sistemi tanımlayıcısını (srid) içerecek sorgu alanının adını yapılandırma. |
| [use_external_srs_from_query(srs_query)](#use_external_srs_from_query_srs_query_6) | Veri kaynağını, Aspose.GIS kütüphanesinde önceden yüklü verileri atlayarak üçüncü taraf mekansal referans sistemi verilerini kullanacak şekilde yapılandırmanıza olanak tanır. |


### Method: add_attribute(name, type) {#add_attribute_name_type_1}


```
 add_attribute(name, type) 
```

Özellik özniteliği için bilgi içerecek alanın adını yapılandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Özellik için sorgu alanının adı. |
| type | [AttributeDataType](/psd/python-net/aspose.gis/attributedatatype) | Veritabanından gelen verilerin dönüştürülmesi gereken veri tipi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) {#as_trackable_for_changes_table_name_identity_attribute_overwrite_same_key_db_func_2}


```
 as_trackable_for_changes(table_name, identity_attribute, overwrite_same_key, db_func) 
```

Ortaya çıkan katmanı değişiklikleri izlemek için yapılandırın ve yapılan değişiklikleri senkronize etmek için bir veri kaynağı oluşturun.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| table_name | string | Değişikliklerin yapılacağı tablonun adı. |
| identity_attribute | string | Bir özelliğin benzersiz olarak tanımlanmasını sağlayacak bir öznitelik. |
| overwrite_same_key | bool | Bu bayrak true olarak ayarlanırsa, katmanda zaten bulunan aynı benzersiz tanımlayıcıya sahip yeni eklenen öznitelikler mevcut olanla üzerine yazılır ve fark bulunursa veri güncellenmiş olarak okunur. |
| db_func | string | Mevcut veritabanının coğrafi veri temsiline ikili veriyi dönüştürmek için SQL sorgusuna sağlanacak işlev. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) | [DatabaseEditableDataSourceBuilder](/psd/python-net/aspose.gis.formats.database.dataediting/databaseeditabledatasourcebuilder/) |


### Method: build() {#build__3}


```
 build() 
```

Yöntem, [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) uygulamasını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource) | [IDatabaseDataSource](/psd/python-net/aspose.gis.formats.database/idatabasedatasource/) uygulaması |


### Method: geometry_field(name) {#geometry_field_name_4}


```
 geometry_field(name) 
```

Geometrinin çıkarılacağı alanın adını yapılandırır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Geometri alanının adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: srid_field(name) {#srid_field_name_5}


```
 srid_field(name) 
```

Mekansal referans sistemi tanımlayıcısını (srid) içerecek sorgu alanının adını yapılandırma.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Mekansal referans sistemi tanımlayıcısını içeren sorgu alanının adı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder) | [DatabaseQueryDataSourceBuilder](/psd/python-net/aspose.gis.formats.database/databasequerydatasourcebuilder/) |


### Method: use_external_srs_from_query(srs_query) {#use_external_srs_from_query_srs_query_6}


```
 use_external_srs_from_query(srs_query) 
```

Veri kaynağını, Aspose.GIS kütüphanesinde önceden yüklü verileri atlayarak üçüncü taraf mekansal referans sistemi verilerini kullanacak şekilde yapılandırmanıza olanak tanır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| srs_query | string | Ana sorguda özellikleri almak için kullanılan ek uzamsal koordinat sistemleri hakkında bilgi almak için sorgu. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder) | [DatabaseExternalSrsSettingsBuilder](/psd/python-net/aspose.gis.formats.database/databaseexternalsrssettingsbuilder/) |


