---
title: "KmlLayer Sınıfı"
type: docs
weight: 140
url: /tr/python-net/aspose.gis.formats.kml/kmllayer/
---

**Summary:** Represents a Kml layer with non-destructive behavior that supports read and writing of features and attributes at one time.<br/>            A Kml layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlLayer

**Inheritance:** VectorLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Bu [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) içindeki özellikler için özel öznitelik koleksiyonunu alır. |
| sayım | int | r | Bu katmandaki özellik sayısını alır. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Bu katmanı oluşturan [KmlLayer.driver](/psd/python-net/aspose.gis.formats.kml/kmllayer/) öğesini alır. |
| features | [Feature[]](/psd/python-net/aspose.gis/feature) | r | Özellikler listesini alır. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Katman için geometrinin tipini alır. |
| ground_overlay_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlGroundOverlayInfo> | r | GroundOverlay düğümlerinden KmlGroundOverlayInfo listesi |
| network_link_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlNetworkLinkInfo> | r | NetworkLink düğümlerinden KmlNetworkLinkInfo listesi |
| region_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlRegionInfo> | r | Region düğümlerinden KmlRegionInfo listesi |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Bu katmanın uzamsal referans sistemini alır. KML için bu her zaman WGS84'tür. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(feature)](#add_feature_1) | Katmana yeni bir özellik ekler, eğer [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'nin [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) tarafından destekleniyorsa. |
| [add(feature, style)](#add_feature_style_2) | Katmana belirtilen stil ile yeni bir özellik ekler, eğer [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'nin [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) tarafından destekleniyorsa. |
| [as_in_memory()](#as_in_memory__3) | Katmanı InMemory formatında bir klon oluştur. |
| [construct_feature()](#construct_feature__4) | Katmana eklemeden (ancak katmana eklemeden) bu katmanın özellik koleksiyonuyla eşleşen niteliklere sahip yeni bir özellik oluşturur.<br/>            Özellik için veri ayarlamayı tamamladığınızda, özelliği katmana eklemek için [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) kullanın. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Bir katmanı farklı bir formata dönüştür. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Bir katmanı farklı bir formata dönüştür. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Bir katmanı farklı bir formata dönüştür. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Bir katmanı farklı bir formata dönüştür. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Diğer [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) öğesinin niteliklerini bu katmana kopyalar. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Diğer [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) öğesinin niteliklerini bu katmana kopyalar. |
| [create(path, driver)](#create_path_driver_11) | Katmanı oluşturur ve yeni özellik eklemek için açar. |
| [create(path, driver)](#create_path_driver_12) | Katmanı oluşturur ve yeni özellik eklemek için açar. |
| [create(path, driver, options)](#create_path_driver_options_13) | Katmanı oluşturur ve yeni özellik eklemek için açar. |
| [create(path, driver, options)](#create_path_driver_options_14) | Katmanı oluşturur ve yeni özellik eklemek için açar. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Katmanı oluşturur ve ekleme için açar. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Katmanı oluşturur ve ekleme için açar. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Katmanı oluşturur ve ekleme için açar. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Katmanı oluşturur ve ekleme için açar. |
| [get_extent()](#get_extent__19) | Bu katmanın uzamsal kapsamını alır. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Bir katmanı geometriye göre mevcut katmanla kesiştir. |
| [join(layer, options)](#join_layer_options_21) | Bir katmanı mevcut katmana birleştir. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Bir katmanı geometriye göre mevcut katmana birleştir. |
| [nearest_to(point)](#nearest_to_point_23) | Sağlanan noktaya en yakın özelliği alır. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Sağlanan koordinata en yakın özelliği alır. |
| [open(path, driver)](#open_path_driver_25) | Katmanı okuma için aç. |
| [open(path, driver)](#open_path_driver_26) | Katmanı okuma için aç. |
| [open(path, driver, options)](#open_path_driver_options_27) | Katmanı okuma için aç. |
| [open(path, driver, options)](#open_path_driver_options_28) | Katmanı okuma için aç. |
| [remove_at(index)](#remove_at_index_29) | Belirtilen indeksteki [Feature](/psd/python-net/aspose.gis/feature/) öğesini kaldır. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Belirtilen indeksteki [Feature](/psd/python-net/aspose.gis/feature/) öğesini değiştir. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Özellik dizisini katmana kaydeder. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Özellik dizisini katmana kaydeder. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Özellik dizisini katmana kaydeder. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Özellik dizisini katmana kaydeder. |
| [split_to()](#split_to__35) | Özellikleri geometri tipine göre böl. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Özellik değeriyle filtreleme işlemlerini hızlandırmak için nitelik indeksini yükler, Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) gibi filtre yöntemlerinde.<br/>            İndeks mevcut değilse önce oluşturur. İndeksi yeniden oluşturmak için <paramref name="forceRebuild" /> kullanın. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Özellik değeriyle filtreleme işlemlerini hızlandırmak için nitelik indeksini yükler, Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) gibi filtre yöntemlerinde.<br/>            İndeks mevcut değilse önce oluşturur. İndeksi yeniden oluşturmak için <paramref name="forceRebuild" /> kullanın. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Özellik değeriyle filtreleme işlemlerini hızlandırmak için uzamsal indeksi yükler, Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) ve Aspose.Gis.VectorLayer.NearestTo(float,float) gibi filtre yöntemlerinde.<br/>            İndeks mevcut değilse önce oluşturur. İndeksi yeniden oluşturmak için <paramref name="forceRebuild" /> kullanın. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Özellik değeriyle filtreleme işlemlerini hızlandırmak için uzamsal indeksi yükler, Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) ve Aspose.Gis.VectorLayer.NearestTo(float,float) gibi filtre yöntemlerinde.<br/>            İndeks mevcut değilse önce oluşturur. İndeksi yeniden oluşturmak için <paramref name="forceRebuild" /> kullanın. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Sağlanan değere eşit nitelik değerine sahip özellikleri seçer. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Sağlanan değerden büyük nitelik değerine sahip özellikleri seçer. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Sağlanan değere eşit veya daha büyük nitelik değerine sahip özellikleri seçer. |
| [where_intersects(extent)](#where_intersects_extent_43) | Özellikleri kapsamına göre filtreler. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Sağlanan geometriye göre özellikleri filtreler. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Diğer özellik dizisindeki tüm geometrilerin birleşimine göre özellikleri filtreler. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Sağlanan değere eşit olmayan öznitelik değerine sahip özellikleri seçer. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Öznitelik değeri null olmayan özellikleri seçer. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Öznitelik değeri null olan özellikleri seçer. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Özniteliği ayarlanmış özellikleri seçer. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Sağlanan değerden daha küçük öznitelik değerine sahip özellikleri seçer. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Sağlanan değere eşit veya daha küçük öznitelik değerine sahip özellikleri seçer. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Belirtilen öznitelik ayarlanmamış özellikleri seçer. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Katmana yeni bir özellik ekler, eğer [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'nin [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) tarafından destekleniyorsa.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Eklenecek özellik. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Katmana belirtilen stil ile yeni bir özellik ekler, eğer [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'nin [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) tarafından destekleniyorsa.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Eklenecek özellik. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | Özellik stili. Eksik stili belirtmek için <see langword=\"null\" /> kullanın. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Katmanı InMemory formatında bir klon oluştur.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | InMemory Katmanı. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Katmana eklemeden (ancak katmana eklemeden) bu katmanın özellik koleksiyonuyla eşleşen niteliklere sahip yeni bir özellik oluşturur.<br/>            Özellik için veri ayarlamayı tamamladığınızda, özelliği katmana eklemek için [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) kullanın.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Yeni bir özellik. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Bir katmanı farklı bir formata dönüştür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_path | string | Dönüştürülecek katmanın yolu. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kaynak katman için format sürücüsü. |
| destination_path | string | Dönüşüm sonucu oluşturulacak katmanın yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Hedef katman için format sürücüsü. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Bir katmanı farklı bir formata dönüştür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dönüştürülecek katmanın yolu. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kaynak katman için format sürücüsü. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dönüşüm sonucu oluşturulacak katmanın yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Hedef katman için format sürücüsü. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Bir katmanı farklı bir formata dönüştür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_path | string | Dönüştürülecek katmanın yolu. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kaynak katman için format sürücüsü. |
| destination_path | string | Dönüşüm sonucu oluşturulacak katmanın yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Hedef katman için format sürücüsü. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Dönüşüm prosedürü için seçenekler. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Bir katmanı farklı bir formata dönüştür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dönüştürülecek katmanın yolu. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kaynak katman için format sürücüsü. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dönüşüm sonucu oluşturulacak katmanın yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Hedef katman için format sürücüsü. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Dönüşüm prosedürü için seçenekler. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Diğer [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) öğesinin niteliklerini bu katmana kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Özniteliklerin kopyalanacağı özellik dizisi. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Diğer [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) öğesinin niteliklerini bu katmana kopyalar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Özniteliklerin kopyalanacağı özellik dizisi. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | Özelleştirilmiş [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) örneği, öznitelikleri tek tek işleyecek. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Katmanı oluşturur ve yeni özellik eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yalnızca yazılabilir bir katman. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Katmanı oluşturur ve yeni özellik eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yalnızca yazılabilir bir katman. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Katmanı oluşturur ve yeni özellik eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yalnızca yazılabilir bir katman. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Katmanı oluşturur ve yeni özellik eklemek için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yalnızca yazılabilir bir katman. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Katmanı oluşturur ve ekleme için açar.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Bir [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) örneği. |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Bu katmanın uzamsal kapsamını alır.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Bu katmanın uzamsal kapsamı. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Bir katmanı geometriye göre mevcut katmanla kesiştir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Kesişmek için bir katman. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | İki katmanın kesişmesi sonucu yeni bir katman. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Bir katmanı mevcut katmana birleştir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Birleştirmek için bir katman. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Birleştirme parametreleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | İki katmanın birleştirilmesi sonucu yeni bir katman. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Bir katmanı geometriye göre mevcut katmana birleştir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Birleştirmek için bir katman. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Birleştirme parametreleri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | İki katmanın birleştirilmesi sonucu yeni bir katman. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Sağlanan noktaya en yakın özelliği alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Nokta. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Sağlanan noktaya en yakın öge. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Sağlanan koordinata en yakın özelliği alır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | double | Koordinatın X'i. |
| y | double | Koordinatın Y'si. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Sağlanan koordinata en yakın öge. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Katmanı okuma için aç.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yalnızca okunabilir bir katman. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Katmanı okuma için aç.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yalnızca okunabilir bir katman. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Katmanı okuma için aç.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| yol | string | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yalnızca okunabilir bir katman. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Katmanı okuma için aç.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Dosyanın yolu. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Kullanılacak sürücü. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Sürücüye özgü seçenekler. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Yalnızca okunabilir bir katman. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Belirtilen indeksteki [Feature](/psd/python-net/aspose.gis/feature/) öğesini kaldır.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | int | Ögenin indeksi. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Belirtilen indeksteki [Feature](/psd/python-net/aspose.gis/feature/) öğesini değiştir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index | int | Ögenin indeksi. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Ayarlanacak öge. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Özellik dizisini katmana kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_path | string | Çıktı katmanının yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Çıktı katmanı için format sürücüsü. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Özellik dizisini katmana kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Çıktı katmanının yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Çıktı katmanı için format sürücüsü. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

Özellik dizisini katmana kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_path | string | Çıktı katmanının yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Çıktı katmanı için format sürücüsü. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Kaydetme prosedürü için seçenekler. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

Özellik dizisini katmana kaydeder.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Çıktı katmanının yolu. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Çıktı katmanı için format sürücüsü. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Kaydetme prosedürü için seçenekler. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Özellikleri geometri tipine göre böl.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Aynı geometri tipine sahip katmanlar. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Özellik değeriyle filtreleme işlemlerini hızlandırmak için nitelik indeksini yükler, Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) gibi filtre yöntemlerinde.<br/>            İndeks mevcut değilse önce oluşturur. İndeksi yeniden oluşturmak için <paramref name="forceRebuild" /> kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index_path | string | İndeks dosyasının yolu. |
| attribute_name | string | İndeksin oluşturulacağı öznitelik adı. |
| force_rebuild | bool | İndeks zaten mevcut olsa bile yeniden oluşturulup oluşturulmayacağı. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Özellik değeriyle filtreleme işlemlerini hızlandırmak için nitelik indeksini yükler, Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) gibi filtre yöntemlerinde.<br/>            İndeks mevcut değilse önce oluşturur. İndeksi yeniden oluşturmak için <paramref name="forceRebuild" /> kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | İndeks dosyasının yolu. |
| attribute_name | string | İndeksin oluşturulacağı öznitelik adı. |
| force_rebuild | bool | İndeks zaten mevcut olsa bile yeniden oluşturulup oluşturulmayacağı. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Özellik değeriyle filtreleme işlemlerini hızlandırmak için uzamsal indeksi yükler, Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) ve Aspose.Gis.VectorLayer.NearestTo(float,float) gibi filtre yöntemlerinde.<br/>            İndeks mevcut değilse önce oluşturur. İndeksi yeniden oluşturmak için <paramref name="forceRebuild" /> kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index_path | string | İndeks dosyasının yolu. |
| force_rebuild | bool | İndeks zaten mevcut olsa bile yeniden oluşturulup oluşturulmayacağı. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Özellik değeriyle filtreleme işlemlerini hızlandırmak için uzamsal indeksi yükler, Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry) ve Aspose.Gis.VectorLayer.NearestTo(float,float) gibi filtre yöntemlerinde.<br/>            İndeks mevcut değilse önce oluşturur. İndeksi yeniden oluşturmak için <paramref name="forceRebuild" /> kullanın.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | İndeks dosyasının yolu. |
| force_rebuild | bool | İndeks zaten mevcut olsa bile yeniden oluşturulup oluşturulmayacağı. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

Sağlanan değere eşit nitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değere eşit öznitelik değerine sahip ögeler. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

Sağlanan değerden büyük nitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değerden büyük öznitelik değerine sahip ögeler. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

Sağlanan değere eşit veya daha büyük nitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değere eşit ya da daha büyük öznitelik değerine sahip ögeler. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

Özellikleri kapsamına göre filtreler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filtreleme kapsamı. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan geometriyle kesişen özellikler. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

Sağlanan geometriye göre özellikleri filtreler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Geometriyi filtrele. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan geometriyle kesişen özellikler. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

Diğer özellik dizisindeki tüm geometrilerin birleşimine göre özellikleri filtreler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Diğer özellikler dizisi. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Diğer özellikler dizisindeki tüm geometrilerin birleşimiyle kesişen özellikler. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

Sağlanan değere eşit olmayan öznitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değere eşit olmayan öznitelik değerine sahip özellikler. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

Öznitelik değeri null olmayan özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Öznitelik değeri null olmayan özellikler. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

Öznitelik değeri null olan özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Öznitelik değeri null olan özellikler. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

Özniteliği ayarlanmış özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Ayarlanmış öznitelik değerine sahip özellikler. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

Sağlanan değerden daha küçük öznitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değerden daha küçük öznitelik değerine sahip özellikler. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

Sağlanan değere eşit veya daha küçük öznitelik değerine sahip özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |
| value | object | Karşılaştırılacak değer. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sağlanan değerden daha küçük veya eşit öznitelik değerine sahip özellikler. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

Belirtilen öznitelik ayarlanmamış özellikleri seçer.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| attribute_name | string | Filtrelenecek öznitelik. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Ayarlanmamış öznitelik değerine sahip özellikler. |


