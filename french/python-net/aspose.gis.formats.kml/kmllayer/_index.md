---
title: "Classe KmlLayer"
type: docs
weight: 140
url: /fr/python-net/aspose.gis.formats.kml/kmllayer/
---

**Summary:** Represents a Kml layer with non-destructive behavior that supports read and writing of features and attributes at one time.<br/>            A Kml layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlLayer

**Inheritance:** VectorLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Obtient la collection d'attributs personnalisés pour les entités de ce [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| nombre | int | r | Obtient le nombre d'entités dans cette couche. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Obtient le [KmlLayer.driver](/psd/python-net/aspose.gis.formats.kml/kmllayer/) qui a instancié cette couche. |
| features | [Feature[]](/psd/python-net/aspose.gis/feature) | r | Obtient la liste des features. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Obtient le type de la géométrie pour la couche. |
| ground_overlay_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlGroundOverlayInfo> | r | Liste de KmlGroundOverlayInfo provenant des nœuds GroundOverlay |
| network_link_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlNetworkLinkInfo> | r | Liste de KmlNetworkLinkInfo provenant des nœuds NetworkLink |
| region_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlRegionInfo> | r | Liste de KmlRegionInfo provenant des nœuds Region |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Obtient le système de référence spatiale de cette couche. Pour le KML, il est toujours WGS84. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(feature)](#add_feature_1) | Ajoute une nouvelle entité à la couche, si prise en charge par le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [add(feature, style)](#add_feature_style_2) | Ajoute une nouvelle entité avec le style spécifié à la couche, si prise en charge par le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [as_in_memory()](#as_in_memory__3) | Crée un clone de couche au format InMemory. |
| [construct_feature()](#construct_feature__4) | Crée (mais n’ajoute pas à la couche) une nouvelle entité avec des attributs correspondant à la collection d’attributs de cette couche.<br/>            Une fois les données de l’entité définies, utilisez [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) pour ajouter l’entité à la couche. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Convertit une couche vers un format différent. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Convertit une couche vers un format différent. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Convertit une couche vers un format différent. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Convertit une couche vers un format différent. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Copie les attributs d’un autre [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) vers celui-ci. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Copie les attributs d’un autre [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) vers celui-ci. |
| [create(path, driver)](#create_path_driver_11) | Crée la couche et l'ouvre pour ajouter de nouvelles entités. |
| [create(path, driver)](#create_path_driver_12) | Crée la couche et l'ouvre pour ajouter de nouvelles entités. |
| [create(path, driver, options)](#create_path_driver_options_13) | Crée la couche et l'ouvre pour ajouter de nouvelles entités. |
| [create(path, driver, options)](#create_path_driver_options_14) | Crée la couche et l'ouvre pour ajouter de nouvelles entités. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Crée la couche et l'ouvre en mode ajout. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Crée la couche et l'ouvre en mode ajout. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Crée la couche et l'ouvre en mode ajout. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Crée la couche et l'ouvre en mode ajout. |
| [get_extent()](#get_extent__19) | Obtient l'étendue spatiale de cette couche. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Intersecte une couche avec la couche actuelle par géométrie. |
| [join(layer, options)](#join_layer_options_21) | Joint une couche à la couche actuelle. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Joint une couche à la couche actuelle par géométrie. |
| [nearest_to(point)](#nearest_to_point_23) | Obtient l'entité la plus proche du point fourni. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Obtient l'entité la plus proche de la coordonnée fournie. |
| [open(path, driver)](#open_path_driver_25) | Ouvre la couche en lecture. |
| [open(path, driver)](#open_path_driver_26) | Ouvre la couche en lecture. |
| [open(path, driver, options)](#open_path_driver_options_27) | Ouvre la couche en lecture. |
| [open(path, driver, options)](#open_path_driver_options_28) | Ouvre la couche en lecture. |
| [remove_at(index)](#remove_at_index_29) | Supprime le [Feature](/psd/python-net/aspose.gis/feature/) à l'index spécifié. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Remplace le [Feature](/psd/python-net/aspose.gis/feature/) à l'index spécifié. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Enregistre la séquence d'entités dans la couche. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Enregistre la séquence d'entités dans la couche. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Enregistre la séquence d'entités dans la couche. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Enregistre la séquence d'entités dans la couche. |
| [split_to()](#split_to__35) | Divise les entités par type de géométrie. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Charge l'index d'attributs pour accélérer le filtrage par valeur d'attributs dans les méthodes de filtrage comme Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Si l'index n'existe pas, il le crée d'abord. Utilisez <paramref name="forceRebuild" /> pour forcer la recréation de l'index. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Charge l'index d'attributs pour accélérer le filtrage par valeur d'attributs dans les méthodes de filtrage comme Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Si l'index n'existe pas, il le crée d'abord. Utilisez <paramref name="forceRebuild" /> pour forcer la recréation de l'index. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Charge l'index spatial pour accélérer le filtrage par valeur d'attributs dans les méthodes de filtrage comme Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            et Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Si l'index n'existe pas, il le crée d'abord. Utilisez <paramref name="forceRebuild" /> pour forcer la recréation de l'index. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Charge l'index spatial pour accélérer le filtrage par valeur d'attributs dans les méthodes de filtrage comme Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            et Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Si l'index n'existe pas, il le crée d'abord. Utilisez <paramref name="forceRebuild" /> pour forcer la recréation de l'index. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Sélectionne les entités dont la valeur d'attribut est égale à la valeur fournie. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Sélectionne les entités dont la valeur d'attribut est supérieure à la valeur fournie. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Sélectionne les entités dont la valeur d'attribut est supérieure ou égale à la valeur fournie. |
| [where_intersects(extent)](#where_intersects_extent_43) | Filtre les entités en fonction de l'étendue. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Filtre les entités en fonction de la géométrie fournie. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Filtre les entités en fonction de l'union de toutes les géométries dans la séquence d'autres entités. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Sélectionne les entités dont la valeur d'attribut n'est pas égale à la valeur fournie. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Sélectionne les entités dont l'attribut n'est pas nul. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Sélectionne les entités dont l'attribut est nul. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Sélectionne les entités dont l'attribut est défini. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Sélectionne les entités dont la valeur d'attribut est inférieure à la valeur fournie. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Sélectionne les entités dont la valeur d'attribut est inférieure ou égale à la valeur fournie. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Sélectionne les entités où l'attribut spécifié n'est pas défini. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Ajoute une nouvelle entité à la couche, si prise en charge par le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | L'entité à ajouter. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Ajoute une nouvelle entité avec le style spécifié à la couche, si prise en charge par le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | L'entité à ajouter. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | Le style de l'entité. Utilisez <see langword=\"null\" /> pour indiquer un style manquant. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Crée un clone de couche au format InMemory.

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | La couche InMemory. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Crée (mais n’ajoute pas à la couche) une nouvelle entité avec des attributs correspondant à la collection d’attributs de cette couche.<br/>            Une fois les données de l’entité définies, utilisez [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) pour ajouter l’entité à la couche.

**Returns**

| Type | Description |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Une nouvelle entité. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Convertit une couche vers un format différent.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_path | string | Chemin vers la couche qui sera convertie. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche source. |
| destination_path | string | Chemin vers la couche qui sera créée à la suite de la conversion. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de destination. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Convertit une couche vers un format différent.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers la couche qui sera convertie. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche source. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers la couche qui sera créée à la suite de la conversion. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de destination. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Convertit une couche vers un format différent.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_path | string | Chemin vers la couche qui sera convertie. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche source. |
| destination_path | string | Chemin vers la couche qui sera créée à la suite de la conversion. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de destination. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Options pour la procédure de conversion. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Convertit une couche vers un format différent.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers la couche qui sera convertie. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche source. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers la couche qui sera créée à la suite de la conversion. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de destination. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Options pour la procédure de conversion. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Copie les attributs d’un autre [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) vers celui-ci.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | La séquence d'entités dont les attributs seront copiés. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Copie les attributs d’un autre [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) vers celui-ci.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | La séquence d'entités dont les attributs seront copiés. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | Une instance personnalisée de [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) qui traitera les attributs un par un. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Crée la couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche en écriture seule. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Crée la couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche en écriture seule. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Crée la couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche en écriture seule. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Crée la couche et l'ouvre pour ajouter de nouvelles entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche en écriture seule. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Crée la couche et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Crée la couche et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Crée la couche et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Crée la couche et l'ouvre en mode ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Système de référence spatiale. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une instance de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Obtient l'étendue spatiale de cette couche.

**Returns**

| Type | Description |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Une étendue spatiale de cette couche. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Intersecte une couche avec la couche actuelle par géométrie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche à intersecter. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une nouvelle couche résultant de l'intersection de deux couches. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Joint une couche à la couche actuelle.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche à joindre. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Paramètres de jointure. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une nouvelle couche résultant de la jointure de deux couches. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Joint une couche à la couche actuelle par géométrie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche à joindre. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Paramètres de jointure. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une nouvelle couche résultant de la jointure de deux couches. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Obtient l'entité la plus proche du point fourni.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Le point. |

**Returns**

| Type | Description |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | L'entité la plus proche du point fourni. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Obtient l'entité la plus proche de la coordonnée fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | double | X de la coordonnée. |
| y | double | Y de la coordonnée. |

**Returns**

| Type | Description |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | L'entité la plus proche de la coordonnée fournie. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Ouvre la couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche en lecture seule. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Ouvre la couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche en lecture seule. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Ouvre la couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | string | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche en lecture seule. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Ouvre la couche en lecture.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Pilote à utiliser. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Options spécifiques au pilote. |

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche en lecture seule. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Supprime le [Feature](/psd/python-net/aspose.gis/feature/) à l'index spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de l'entité. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Remplace le [Feature](/psd/python-net/aspose.gis/feature/) à l'index spécifié.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index | int | L'index de l'entité. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | L'entité à définir. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Enregistre la séquence d'entités dans la couche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_path | string | Chemin vers la couche de sortie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de sortie. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Enregistre la séquence d'entités dans la couche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers la couche de sortie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de sortie. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

Enregistre la séquence d'entités dans la couche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_path | string | Chemin vers la couche de sortie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de sortie. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Options pour la procédure d'enregistrement. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

Enregistre la séquence d'entités dans la couche.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers la couche de sortie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Le pilote de format pour la couche de sortie. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Options pour la procédure d'enregistrement. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Divise les entités par type de géométrie.

**Returns**

| Type | Description |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Couches avec le même type de géométrie. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Charge l'index d'attributs pour accélérer le filtrage par valeur d'attributs dans les méthodes de filtrage comme Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Si l'index n'existe pas, il le crée d'abord. Utilisez <paramref name="forceRebuild" /> pour forcer la recréation de l'index.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index_path | string | Chemin vers le fichier d'index. |
| attribute_name | string | Nom de l'attribut sur lequel construire l'index. |
| force_rebuild | bool | Indique s'il faut recréer l'index même s'il existe déjà. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Charge l'index d'attributs pour accélérer le filtrage par valeur d'attributs dans les méthodes de filtrage comme Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Si l'index n'existe pas, il le crée d'abord. Utilisez <paramref name="forceRebuild" /> pour forcer la recréation de l'index.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier d'index. |
| attribute_name | string | Nom de l'attribut sur lequel construire l'index. |
| force_rebuild | bool | Indique s'il faut recréer l'index même s'il existe déjà. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Charge l'index spatial pour accélérer le filtrage par valeur d'attributs dans les méthodes de filtrage comme Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            et Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Si l'index n'existe pas, il le crée d'abord. Utilisez <paramref name="forceRebuild" /> pour forcer la recréation de l'index.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index_path | string | Chemin vers le fichier d'index. |
| force_rebuild | bool | Indique s'il faut recréer l'index même s'il existe déjà. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Charge l'index spatial pour accélérer le filtrage par valeur d'attributs dans les méthodes de filtrage comme Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            et Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Si l'index n'existe pas, il le crée d'abord. Utilisez <paramref name="forceRebuild" /> pour forcer la recréation de l'index.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin vers le fichier d'index. |
| force_rebuild | bool | Indique s'il faut recréer l'index même s'il existe déjà. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est égale à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est égale à la valeur fournie. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est supérieure à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est supérieure à la valeur fournie. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est supérieure ou égale à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est supérieure ou égale à la valeur fournie. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

Filtre les entités en fonction de l'étendue.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filtrer l'étendue. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités qui intersectent la géométrie fournie. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

Filtre les entités en fonction de la géométrie fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filtrer la géométrie. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités qui intersectent la géométrie fournie. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

Filtre les entités en fonction de l'union de toutes les géométries dans la séquence d'autres entités.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Autre séquence d'entités. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités qui intersectent l'union de toutes les géométries de l'autre séquence d'entités. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut n'est pas égale à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut n'est pas égale à la valeur fournie. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

Sélectionne les entités dont l'attribut n'est pas nul.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut n'est pas égale à null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

Sélectionne les entités dont l'attribut est nul.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est égale à null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

Sélectionne les entités dont l'attribut est défini.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités avec une valeur d'attribut définie. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est inférieure à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est inférieure à la valeur fournie. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

Sélectionne les entités dont la valeur d'attribut est inférieure ou égale à la valeur fournie.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |
| valeur | object | Valeur à comparer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut est inférieure ou égale à la valeur fournie. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

Sélectionne les entités où l'attribut spécifié n'est pas défini.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Attribut à filtrer. |

**Returns**

| Type | Description |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Entités dont la valeur d'attribut n'est pas définie. |


