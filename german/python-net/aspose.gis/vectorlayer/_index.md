---
title: "VectorLayer-Klasse"
type: docs
weight: 4060
url: /de/python-net/aspose.gis/vectorlayer/
---

**Summary:** Represents a vector layer.<br/>            A vector layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.VectorLayer

**Inheritance:** FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschreibung** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Ruft die Sammlung benutzerdefinierter Attribute für Features in diesem [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ab. |
| Anzahl | int | r | Ruft die Anzahl der Features in dieser Ebene ab. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Ruft den [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) ab, der diese Ebene instanziiert hat. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Ermittelt den Typ der Geometrie für das Layer. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Ermittelt das räumliche Referenzsystem dieser Feature‑Sequenz. |
## **Methods**
| **Name** | **Beschreibung** |
| :- | :- |
| [add(feature)](#add_feature_1) | Fügt dem Layer ein neues Feature hinzu, falls vom [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) unterstützt. |
| [add(feature, style)](#add_feature_style_2) | Fügt dem Layer ein neues Feature mit dem angegebenen Stil hinzu, falls vom [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) unterstützt. |
| [as_in_memory()](#as_in_memory__3) | Erstelle ein Layer‑Klon im InMemory-Format. |
| [construct_feature()](#construct_feature__4) | Erstellt (fügt jedoch nicht zum Layer hinzu) ein neues Feature mit Attributen, die der Attributsammlung dieses Layers entsprechen.<br/>            Wenn die Daten für das Feature festgelegt sind, verwenden Sie [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/), um das Feature zum Layer hinzuzufügen. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Konvertiert ein Layer in ein anderes Format. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Konvertiert ein Layer in ein anderes Format. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Konvertiert ein Layer in ein anderes Format. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Konvertiert ein Layer in ein anderes Format. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Kopiert Attribute eines anderen [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) in diesen. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Kopiert Attribute eines anderen [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) in diesen. |
| [create(path, driver)](#create_path_driver_11) | Erstellt das Layer und öffnet es zum Hinzufügen neuer Features. |
| [create(path, driver)](#create_path_driver_12) | Erstellt das Layer und öffnet es zum Hinzufügen neuer Features. |
| [create(path, driver, options)](#create_path_driver_options_13) | Erstellt das Layer und öffnet es zum Hinzufügen neuer Features. |
| [create(path, driver, options)](#create_path_driver_options_14) | Erstellt das Layer und öffnet es zum Hinzufügen neuer Features. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Erstellt das Layer und öffnet es zum Anhängen. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Erstellt das Layer und öffnet es zum Anhängen. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Erstellt das Layer und öffnet es zum Anhängen. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Erstellt das Layer und öffnet es zum Anhängen. |
| [get_extent()](#get_extent__19) | Ermittelt den räumlichen Umfang dieses Layers. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Schnitte einen Layer anhand der Geometrie mit dem aktuellen Layer. |
| [join(layer, options)](#join_layer_options_21) | Verknüpft einen Layer mit dem aktuellen Layer. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Verknüpft einen Layer anhand der Geometrie mit dem aktuellen Layer. |
| [nearest_to(point)](#nearest_to_point_23) | Ermittelt das dem angegebenen Punkt nächstgelegene Feature. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Ermittelt das der angegebenen Koordinate nächstgelegene Feature. |
| [open(path, driver)](#open_path_driver_25) | Öffnet das Layer zum Lesen. |
| [open(path, driver)](#open_path_driver_26) | Öffnet das Layer zum Lesen. |
| [open(path, driver, options)](#open_path_driver_options_27) | Öffnet das Layer zum Lesen. |
| [open(path, driver, options)](#open_path_driver_options_28) | Öffnet das Layer zum Lesen. |
| [remove_at(index)](#remove_at_index_29) | Entfernt das [Feature](/psd/python-net/aspose.gis/feature/) am angegebenen Index. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Ersetzt das [Feature](/psd/python-net/aspose.gis/feature/) am angegebenen Index. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Speichert die Feature‑Sequenz im Layer. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Speichert die Feature‑Sequenz im Layer. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Speichert die Feature‑Sequenz im Layer. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Speichert die Feature‑Sequenz im Layer. |
| [split_to()](#split_to__35) | Teilt Features nach Geometrietyp. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Lädt den Attributindex, um das Filtern nach Attributwerten in Filtermethoden wie Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) zu beschleunigen.<br/>            Wenn der Index nicht existiert, wird er zuerst erstellt. Verwenden Sie <paramref name="forceRebuild" /> um die Indexerstellung zu erzwingen. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Lädt den Attributindex, um das Filtern nach Attributwerten in Filtermethoden wie Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) zu beschleunigen.<br/>            Wenn der Index nicht existiert, wird er zuerst erstellt. Verwenden Sie <paramref name="forceRebuild" /> um die Indexerstellung zu erzwingen. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Lädt den räumlichen Index, um das Filtern nach Attributwerten in Filtermethoden wie Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            und Aspose.Gis.VectorLayer.NearestTo(float,float) zu beschleunigen.<br/>            Wenn der Index nicht existiert, wird er zuerst erstellt. Verwenden Sie <paramref name="forceRebuild" /> um die Indexerstellung zu erzwingen. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Lädt den räumlichen Index, um das Filtern nach Attributwerten in Filtermethoden wie Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            und Aspose.Gis.VectorLayer.NearestTo(float,float) zu beschleunigen.<br/>            Wenn der Index nicht existiert, wird er zuerst erstellt. Verwenden Sie <paramref name="forceRebuild" /> um die Indexerstellung zu erzwingen. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Wählt Features aus, deren Attributwert dem angegebenen Wert entspricht. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Wählt Features aus, deren Attributwert größer als der angegebene Wert ist. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Wählt Features aus, deren Attributwert größer oder gleich dem angegebenen Wert ist. |
| [where_intersects(extent)](#where_intersects_extent_43) | Filtert Features basierend auf der Ausdehnung. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Filtert Features basierend auf der bereitgestellten Geometrie. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Filtert Features basierend auf der Vereinigung aller Geometrien in der anderen Feature‑Sequenz. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Wählt Features aus, deren Attributwert nicht dem bereitgestellten Wert entspricht. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Wählt Features aus, deren Attribut nicht null ist. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Wählt Features aus, deren Attribut null ist. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Wählt Features aus, bei denen das Attribut gesetzt ist. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Wählt Features aus, deren Attributwert kleiner als der bereitgestellte Wert ist. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Wählt Features aus, deren Attributwert kleiner oder gleich dem bereitgestellten Wert ist. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Wählt Features aus, bei denen das angegebene Attribut nicht gesetzt ist. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Fügt dem Layer ein neues Feature hinzu, falls vom [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) unterstützt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Das hinzuzufügende Feature. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Fügt dem Layer ein neues Feature mit dem angegebenen Stil hinzu, falls vom [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) unterstützt.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Das hinzuzufügende Feature. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | Der Feature‑Stil. Verwenden Sie <see langword=\"null\" /> um einen fehlenden Stil anzuzeigen. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Erstelle ein Layer‑Klon im InMemory-Format.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Der InMemory‑Layer. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Erstellt (fügt jedoch nicht zum Layer hinzu) ein neues Feature mit Attributen, die der Attributsammlung dieses Layers entsprechen.<br/>            Wenn die Daten für das Feature festgelegt sind, verwenden Sie [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/), um das Feature zum Layer hinzuzufügen.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Ein neues Feature. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Konvertiert ein Layer in ein anderes Format.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_path | string | Pfad zur Ebene, die konvertiert wird. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Format‑Treiber für die Quell‑Ebene. |
| destination_path | string | Pfad zur Ebene, die als Ergebnis der Konvertierung erstellt wird. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Format‑Treiber für die Ziel‑Ebene. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Konvertiert ein Layer in ein anderes Format.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Ebene, die konvertiert wird. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Format‑Treiber für die Quell‑Ebene. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Ebene, die als Ergebnis der Konvertierung erstellt wird. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Format‑Treiber für die Ziel‑Ebene. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Konvertiert ein Layer in ein anderes Format.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_path | string | Pfad zur Ebene, die konvertiert wird. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Format‑Treiber für die Quell‑Ebene. |
| destination_path | string | Pfad zur Ebene, die als Ergebnis der Konvertierung erstellt wird. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Format‑Treiber für die Ziel‑Ebene. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Optionen für das Konvertierungsverfahren. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Konvertiert ein Layer in ein anderes Format.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Ebene, die konvertiert wird. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Format‑Treiber für die Quell‑Ebene. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Ebene, die als Ergebnis der Konvertierung erstellt wird. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Format‑Treiber für die Ziel‑Ebene. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Optionen für das Konvertierungsverfahren. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Kopiert Attribute eines anderen [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) in diesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Die Feature‑Sequenz, aus der Attribute kopiert werden sollen. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Kopiert Attribute eines anderen [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) in diesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Die Feature‑Sequenz, aus der Attribute kopiert werden sollen. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | Eine Instanz des benutzerdefinierten [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/), die die Attribute einzeln verarbeitet. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Erstellt das Layer und öffnet es zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine nur schreibbare Ebene. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Erstellt das Layer und öffnet es zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine nur schreibbare Ebene. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Erstellt das Layer und öffnet es zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine nur schreibbare Ebene. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Erstellt das Layer und öffnet es zum Hinzufügen neuer Features.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine nur schreibbare Ebene. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Erstellt das Layer und öffnet es zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Erstellt das Layer und öffnet es zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Erstellt das Layer und öffnet es zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Erstellt das Layer und öffnet es zum Anhängen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Räumliches Referenzsystem. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Instanz von [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Ermittelt den räumlichen Umfang dieses Layers.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ein räumlicher Ausdehnungsbereich dieser Ebene. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Schnitte einen Layer anhand der Geometrie mit dem aktuellen Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Ebene zum Überschneiden. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine neue Ebene als Ergebnis der Überschneidung zweier Ebenen. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Verknüpft einen Layer mit dem aktuellen Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Ebene zum Verbinden. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Verbindungsparameter. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine neue Ebene als Ergebnis des Verbindens zweier Ebenen. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Verknüpft einen Layer anhand der Geometrie mit dem aktuellen Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine Ebene zum Verbinden. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Verbindungsparameter. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine neue Ebene als Ergebnis des Verbindens zweier Ebenen. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Ermittelt das dem angegebenen Punkt nächstgelegene Feature.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Der Punkt. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Das nächstgelegene Feature zum angegebenen Punkt. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Ermittelt das der angegebenen Koordinate nächstgelegene Feature.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| x | double | X der Koordinate. |
| y | double | Y der Koordinate. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Das nächstgelegene Feature zur angegebenen Koordinate. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Öffnet das Layer zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine schreibgeschützte Ebene. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Öffnet das Layer zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine schreibgeschützte Ebene. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Öffnet das Layer zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | string | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine schreibgeschützte Ebene. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Öffnet das Layer zum Lesen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Datei. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Zu verwendender Treiber. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Treiber-spezifische Optionen. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Eine schreibgeschützte Ebene. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Entfernt das [Feature](/psd/python-net/aspose.gis/feature/) am angegebenen Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index des Features. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Ersetzt das [Feature](/psd/python-net/aspose.gis/feature/) am angegebenen Index.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index | int | Der Index des Features. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Das zu setzende Feature. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Speichert die Feature‑Sequenz im Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_path | string | Pfad zur Ausgabeebene. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Formattreiber für die Ausgabeebene. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Speichert die Feature‑Sequenz im Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Ausgabeebene. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Formattreiber für die Ausgabeebene. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

Speichert die Feature‑Sequenz im Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_path | string | Pfad zur Ausgabeebene. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Formattreiber für die Ausgabeebene. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Optionen für den Speicherungsprozess. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

Speichert die Feature‑Sequenz im Layer.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Ausgabeebene. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Der Formattreiber für die Ausgabeebene. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Optionen für den Speicherungsprozess. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Teilt Features nach Geometrietyp.

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Ebenen mit demselben Geometrietyp. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Lädt den Attributindex, um das Filtern nach Attributwerten in Filtermethoden wie Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) zu beschleunigen.<br/>            Wenn der Index nicht existiert, wird er zuerst erstellt. Verwenden Sie <paramref name="forceRebuild" /> um die Indexerstellung zu erzwingen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index_path | string | Pfad zur Indexdatei. |
| attribute_name | string | Name des Attributs, auf dem der Index aufgebaut werden soll. |
| force_rebuild | bool | Ob der Index neu erstellt werden soll, selbst wenn er bereits existiert. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Lädt den Attributindex, um das Filtern nach Attributwerten in Filtermethoden wie Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0) zu beschleunigen.<br/>            Wenn der Index nicht existiert, wird er zuerst erstellt. Verwenden Sie <paramref name="forceRebuild" /> um die Indexerstellung zu erzwingen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Indexdatei. |
| attribute_name | string | Name des Attributs, auf dem der Index aufgebaut werden soll. |
| force_rebuild | bool | Ob der Index neu erstellt werden soll, selbst wenn er bereits existiert. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Lädt den räumlichen Index, um das Filtern nach Attributwerten in Filtermethoden wie Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            und Aspose.Gis.VectorLayer.NearestTo(float,float) zu beschleunigen.<br/>            Wenn der Index nicht existiert, wird er zuerst erstellt. Verwenden Sie <paramref name="forceRebuild" /> um die Indexerstellung zu erzwingen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index_path | string | Pfad zur Indexdatei. |
| force_rebuild | bool | Ob der Index neu erstellt werden soll, selbst wenn er bereits existiert. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Lädt den räumlichen Index, um das Filtern nach Attributwerten in Filtermethoden wie Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            und Aspose.Gis.VectorLayer.NearestTo(float,float) zu beschleunigen.<br/>            Wenn der Index nicht existiert, wird er zuerst erstellt. Verwenden Sie <paramref name="forceRebuild" /> um die Indexerstellung zu erzwingen.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pfad zur Indexdatei. |
| force_rebuild | bool | Ob der Index neu erstellt werden soll, selbst wenn er bereits existiert. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

Wählt Features aus, deren Attributwert dem angegebenen Wert entspricht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der dem angegebenen Wert entspricht. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

Wählt Features aus, deren Attributwert größer als der angegebene Wert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der größer ist als der angegebene Wert. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

Wählt Features aus, deren Attributwert größer oder gleich dem angegebenen Wert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der größer oder gleich dem angegebenen Wert ist. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

Filtert Features basierend auf der Ausdehnung.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filterbereich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features, die mit der bereitgestellten Geometrie schneiden. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

Filtert Features basierend auf der bereitgestellten Geometrie.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filtergeometrie. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features, die mit der bereitgestellten Geometrie schneiden. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

Filtert Features basierend auf der Vereinigung aller Geometrien in der anderen Feature‑Sequenz.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Andere Feature-Sequenz. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features, die mit der Vereinigung aller Geometrien in der anderen Feature-Sequenz schneiden. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

Wählt Features aus, deren Attributwert nicht dem bereitgestellten Wert entspricht.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der nicht dem angegebenen Wert entspricht. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

Wählt Features aus, deren Attribut nicht null ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der nicht null ist. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

Wählt Features aus, deren Attribut null ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert, der null ist. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

Wählt Features aus, bei denen das Attribut gesetzt ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit gesetztem Attributwert. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

Wählt Features aus, deren Attributwert kleiner als der bereitgestellte Wert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert kleiner als der angegebene Wert. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

Wählt Features aus, deren Attributwert kleiner oder gleich dem bereitgestellten Wert ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |
| value | object | Wert zum Vergleich. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit Attributwert kleiner oder gleich dem angegebenen Wert. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

Wählt Features aus, bei denen das angegebene Attribut nicht gesetzt ist.

**Parameters:**

| Parameter | Typ | Beschreibung |
| :- | :- | :- |
| attribute_name | string | Attribut zum Filtern. |

**Returns**

| Typ | Beschreibung |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features mit nicht gesetztem Attributwert. |


