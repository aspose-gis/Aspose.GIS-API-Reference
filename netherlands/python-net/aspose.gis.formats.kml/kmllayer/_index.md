---
title: "KmlLayer Klasse"
type: docs
weight: 140
url: /nl/python-net/aspose.gis.formats.kml/kmllayer/
---

**Summary:** Represents a Kml layer with non-destructive behavior that supports read and writing of features and attributes at one time.<br/>            A Kml layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlLayer

**Inheritance:** VectorLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beschrijving** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Haalt de collectie van aangepaste attributen op voor objecten in deze [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| aantal | int | r | Haalt het aantal objecten in deze laag op. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Haalt de [KmlLayer.driver](/psd/python-net/aspose.gis.formats.kml/kmllayer/) op die deze laag heeft geïnstantiëerd. |
| features | [Feature[]](/psd/python-net/aspose.gis/feature) | r | Haalt de lijst met features op. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Haalt het type van de geometrie voor de laag op. |
| ground_overlay_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlGroundOverlayInfo> | r | Lijst van KmlGroundOverlayInfo van GroundOverlay-knooppunten |
| network_link_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlNetworkLinkInfo> | r | Lijst van KmlNetworkLinkInfo van NetworkLink-knooppunten |
| region_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlRegionInfo> | r | Lijst van KmlRegionInfo van Region-knooppunten |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Haal het ruimtelijke referentiesysteem van deze laag op. Voor KML is dit altijd WGS84. |
## **Methods**
| **Name** | **Beschrijving** |
| :- | :- |
| [add(feature)](#add_feature_1) | Voegt een nieuw kenmerk toe aan de laag, indien ondersteund door de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [add(feature, style)](#add_feature_style_2) | Voegt een nieuw kenmerk toe met de opgegeven stijl aan de laag, indien ondersteund door de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [as_in_memory()](#as_in_memory__3) | Maak een laagclone aan in het InMemory-formaat. |
| [construct_feature()](#construct_feature__4) | Maakt (maar voegt niet toe aan de laag) een nieuw kenmerk met attributen die overeenkomen met de verzameling attributen van deze laag.<br/>            Wanneer de gegevens voor het kenmerk zijn ingesteld, gebruik [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) om het kenmerk aan de laag toe te voegen. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Converteer een laag naar een ander formaat. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Converteer een laag naar een ander formaat. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Converteer een laag naar een ander formaat. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Converteer een laag naar een ander formaat. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Kopieert attributen van een andere [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) naar deze. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Kopieert attributen van een andere [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) naar deze. |
| [create(path, driver)](#create_path_driver_11) | Maakt de laag aan en opent deze voor het toevoegen van nieuwe kenmerken. |
| [create(path, driver)](#create_path_driver_12) | Maakt de laag aan en opent deze voor het toevoegen van nieuwe kenmerken. |
| [create(path, driver, options)](#create_path_driver_options_13) | Maakt de laag aan en opent deze voor het toevoegen van nieuwe kenmerken. |
| [create(path, driver, options)](#create_path_driver_options_14) | Maakt de laag aan en opent deze voor het toevoegen van nieuwe kenmerken. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Maakt de laag aan en opent deze voor toevoegen. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Maakt de laag aan en opent deze voor toevoegen. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Maakt de laag aan en opent deze voor toevoegen. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Maakt de laag aan en opent deze voor toevoegen. |
| [get_extent()](#get_extent__19) | Haalt de ruimtelijke omvang van deze laag op. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Snijd een laag met de huidige laag op basis van geometrie. |
| [join(layer, options)](#join_layer_options_21) | Voegt een laag samen met de huidige laag. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Voegt een laag samen met de huidige laag op basis van geometrie. |
| [nearest_to(point)](#nearest_to_point_23) | Haalt het dichtstbijzijnde kenmerk op ten opzichte van het opgegeven punt. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Haalt het dichtstbijzijnde kenmerk op ten opzichte van de opgegeven coördinaat. |
| [open(path, driver)](#open_path_driver_25) | Open de laag voor lezen. |
| [open(path, driver)](#open_path_driver_26) | Open de laag voor lezen. |
| [open(path, driver, options)](#open_path_driver_options_27) | Open de laag voor lezen. |
| [open(path, driver, options)](#open_path_driver_options_28) | Open de laag voor lezen. |
| [remove_at(index)](#remove_at_index_29) | Verwijder de [Feature](/psd/python-net/aspose.gis/feature/) op de opgegeven index. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Vervang de [Feature](/psd/python-net/aspose.gis/feature/) op de opgegeven index. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Slaat de kenmerkenreeks op in de laag. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Slaat de kenmerkenreeks op in de laag. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Slaat de kenmerkenreeks op in de laag. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Slaat de kenmerkenreeks op in de laag. |
| [split_to()](#split_to__35) | Splits kenmerken op type geometrie. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Laadt attribuutindex om het filteren op attribuutwaarde te versnellen in filtermethoden zoals Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Als het index niet bestaat, wordt deze eerst aangemaakt. Gebruik <paramref name="forceRebuild" /> om het opnieuw opbouwen van de index af te dwingen. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Laadt attribuutindex om het filteren op attribuutwaarde te versnellen in filtermethoden zoals Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Als het index niet bestaat, wordt deze eerst aangemaakt. Gebruik <paramref name="forceRebuild" /> om het opnieuw opbouwen van de index af te dwingen. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Laadt ruimtelijke index om het filteren op attribuutwaarde te versnellen in filtermethoden zoals Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            en Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Als het index niet bestaat, wordt deze eerst aangemaakt. Gebruik <paramref name="forceRebuild" /> om het opnieuw opbouwen van de index af te dwingen. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Laadt ruimtelijke index om het filteren op attribuutwaarde te versnellen in filtermethoden zoals Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            en Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Als het index niet bestaat, wordt deze eerst aangemaakt. Gebruik <paramref name="forceRebuild" /> om het opnieuw opbouwen van de index af te dwingen. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Selecteert kenmerken met een attribuutwaarde gelijk aan de opgegeven waarde. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Selecteert kenmerken met een attribuutwaarde groter dan de opgegeven waarde. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Selecteert kenmerken met een attribuutwaarde groter dan of gelijk aan de opgegeven waarde. |
| [where_intersects(extent)](#where_intersects_extent_43) | Filtert features op basis van de omvang. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Filtert features op basis van de opgegeven geometrie. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Filtert features op basis van de unie van alle geometrieën in de andere features-reeks. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Selecteert features met een attribuutwaarde die niet gelijk is aan de opgegeven waarde. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Selecteert features met een attribuut dat niet gelijk is aan null. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Selecteert features met een attribuut dat gelijk is aan null. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Selecteert features met een ingesteld attribuut. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Selecteert features met een attribuutwaarde kleiner dan de opgegeven waarde. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Selecteert features met een attribuutwaarde kleiner dan of gelijk aan de opgegeven waarde. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Selecteert features waarbij het opgegeven attribuut niet is ingesteld. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Voegt een nieuw kenmerk toe aan de laag, indien ondersteund door de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | De toe te voegen feature. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Voegt een nieuw kenmerk toe met de opgegeven stijl aan de laag, indien ondersteund door de [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | De toe te voegen feature. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | De feature-stijl. Gebruik <see langword="null" /> om een ontbrekende stijl aan te geven. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Maak een laagclone aan in het InMemory-formaat.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | De InMemory-laag. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Maakt (maar voegt niet toe aan de laag) een nieuw kenmerk met attributen die overeenkomen met de verzameling attributen van deze laag.<br/>            Wanneer de gegevens voor het kenmerk zijn ingesteld, gebruik [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) om het kenmerk aan de laag toe te voegen.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Een nieuwe feature. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Converteer een laag naar een ander formaat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_path | string | Pad naar de laag die zal worden geconverteerd. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De format-driver voor de bronlaag. |
| destination_path | string | Pad naar de laag die zal worden aangemaakt als resultaat van de conversie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De format-driver voor de doelllaag. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Converteer een laag naar een ander formaat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de laag die zal worden geconverteerd. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De format-driver voor de bronlaag. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de laag die zal worden aangemaakt als resultaat van de conversie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De format-driver voor de doelllaag. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Converteer een laag naar een ander formaat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_path | string | Pad naar de laag die zal worden geconverteerd. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De format-driver voor de bronlaag. |
| destination_path | string | Pad naar de laag die zal worden aangemaakt als resultaat van de conversie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De format-driver voor de doelllaag. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Opties voor de conversieprocedure. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Converteer een laag naar een ander formaat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de laag die zal worden geconverteerd. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De format-driver voor de bronlaag. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de laag die zal worden aangemaakt als resultaat van de conversie. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De format-driver voor de doelllaag. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Opties voor de conversieprocedure. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Kopieert attributen van een andere [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) naar deze.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | De features-reeks waaruit attributen gekopieerd moeten worden. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Kopieert attributen van een andere [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) naar deze.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | De features-reeks waaruit attributen gekopieerd moeten worden. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | Een instantie van een aangepaste [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) die de attributen één voor één zal verwerken. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Maakt de laag aan en opent deze voor het toevoegen van nieuwe kenmerken.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een alleen-schrijflag. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Maakt de laag aan en opent deze voor het toevoegen van nieuwe kenmerken.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een alleen-schrijflag. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Maakt de laag aan en opent deze voor het toevoegen van nieuwe kenmerken.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een alleen-schrijflag. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Maakt de laag aan en opent deze voor het toevoegen van nieuwe kenmerken.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een alleen-schrijflag. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Maakt de laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Maakt de laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Maakt de laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Maakt de laag aan en opent deze voor toevoegen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ruimtelijk referentiesysteem. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een exemplaar van [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Haalt de ruimtelijke omvang van deze laag op.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Een ruimtelijke omvang van deze laag. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Snijd een laag met de huidige laag op basis van geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een laag om te kruisen. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een nieuwe laag als resultaat van het kruisen van twee lagen. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Voegt een laag samen met de huidige laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een laag om te koppelen. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Koppelingsparameters. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een nieuwe laag als resultaat van het koppelen van twee lagen. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Voegt een laag samen met de huidige laag op basis van geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een laag om te koppelen. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Koppelingsparameters. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een nieuwe laag als resultaat van het koppelen van twee lagen. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Haalt het dichtstbijzijnde kenmerk op ten opzichte van het opgegeven punt.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Het punt. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Het dichtstbijzijnde object bij het opgegeven punt. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Haalt het dichtstbijzijnde kenmerk op ten opzichte van de opgegeven coördinaat.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| x | double | X van de coördinaat. |
| y | double | Y van de coördinaat. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Het dichtstbijzijnde object bij de opgegeven coördinaat. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Open de laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een alleen-lezen laag. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Open de laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een alleen-lezen laag. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Open de laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| pad | string | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een alleen-lezen laag. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Open de laag voor lezen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het bestand. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Te gebruiken driver. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Driver-specifieke opties. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Een alleen-lezen laag. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Verwijder de [Feature](/psd/python-net/aspose.gis/feature/) op de opgegeven index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | De index van het object. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Vervang de [Feature](/psd/python-net/aspose.gis/feature/) op de opgegeven index.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index | int | De index van het object. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Het object om in te stellen. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Slaat de kenmerkenreeks op in de laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_path | string | Pad naar de uitvoerlaag. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De formatdriver voor de uitvoerlaag. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Slaat de kenmerkenreeks op in de laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de uitvoerlaag. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De formatdriver voor de uitvoerlaag. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

Slaat de kenmerkenreeks op in de laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_path | string | Pad naar de uitvoerlaag. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De formatdriver voor de uitvoerlaag. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opties voor de opslaanprocedure. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

Slaat de kenmerkenreeks op in de laag.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar de uitvoerlaag. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | De formatdriver voor de uitvoerlaag. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opties voor de opslaanprocedure. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Splits kenmerken op type geometrie.

**Returns**

| Type | Beschrijving |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Lagen met hetzelfde type geometrie. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Laadt attribuutindex om het filteren op attribuutwaarde te versnellen in filtermethoden zoals Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Als het index niet bestaat, wordt deze eerst aangemaakt. Gebruik <paramref name="forceRebuild" /> om het opnieuw opbouwen van de index af te dwingen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index_path | string | Pad naar het indexbestand. |
| attribute_name | string | Naam van het attribuut waarop de index wordt gebouwd. |
| force_rebuild | bool | Of de index opnieuw moet worden aangemaakt, zelfs als deze al bestaat. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Laadt attribuutindex om het filteren op attribuutwaarde te versnellen in filtermethoden zoals Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Als het index niet bestaat, wordt deze eerst aangemaakt. Gebruik <paramref name="forceRebuild" /> om het opnieuw opbouwen van de index af te dwingen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het indexbestand. |
| attribute_name | string | Naam van het attribuut waarop de index wordt gebouwd. |
| force_rebuild | bool | Of de index opnieuw moet worden aangemaakt, zelfs als deze al bestaat. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Laadt ruimtelijke index om het filteren op attribuutwaarde te versnellen in filtermethoden zoals Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            en Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Als het index niet bestaat, wordt deze eerst aangemaakt. Gebruik <paramref name="forceRebuild" /> om het opnieuw opbouwen van de index af te dwingen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index_path | string | Pad naar het indexbestand. |
| force_rebuild | bool | Of de index opnieuw moet worden aangemaakt, zelfs als deze al bestaat. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Laadt ruimtelijke index om het filteren op attribuutwaarde te versnellen in filtermethoden zoals Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            en Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Als het index niet bestaat, wordt deze eerst aangemaakt. Gebruik <paramref name="forceRebuild" /> om het opnieuw opbouwen van de index af te dwingen.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Pad naar het indexbestand. |
| force_rebuild | bool | Of de index opnieuw moet worden aangemaakt, zelfs als deze al bestaat. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

Selecteert kenmerken met een attribuutwaarde gelijk aan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objecten met attribuutwaarde gelijk aan de opgegeven waarde. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

Selecteert kenmerken met een attribuutwaarde groter dan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objecten met attribuutwaarde groter dan de opgegeven waarde. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

Selecteert kenmerken met een attribuutwaarde groter dan of gelijk aan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objecten met attribuutwaarde groter of gelijk aan de opgegeven waarde. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

Filtert features op basis van de omvang.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filterbereik. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features die snijden met de opgegeven geometrie. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

Filtert features op basis van de opgegeven geometrie.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filter geometrie. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features die snijden met de opgegeven geometrie. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

Filtert features op basis van de unie van alle geometrieën in de andere features-reeks.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Andere featuresreeks. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features die snijden met de unie van alle geometrieën in de andere featuresreeks. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

Selecteert features met een attribuutwaarde die niet gelijk is aan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde die niet gelijk is aan de opgegeven waarde. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

Selecteert features met een attribuut dat niet gelijk is aan null.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde die niet gelijk is aan null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

Selecteert features met een attribuut dat gelijk is aan null.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde gelijk aan null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

Selecteert features met een ingesteld attribuut.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met ingestelde attribuutwaarde. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

Selecteert features met een attribuutwaarde kleiner dan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde kleiner dan de opgegeven waarde. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

Selecteert features met een attribuutwaarde kleiner dan of gelijk aan de opgegeven waarde.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |
| waarde | object | Waarde om mee te vergelijken. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met attribuutwaarde kleiner dan of gelijk aan de opgegeven waarde. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

Selecteert features waarbij het opgegeven attribuut niet is ingesteld.

**Parameters:**

| Parameter | Type | Beschrijving |
| :- | :- | :- |
| attribute_name | string | Attribuut om op te filteren. |

**Returns**

| Type | Beschrijving |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features met niet-ingestelde attribuutwaarde. |


