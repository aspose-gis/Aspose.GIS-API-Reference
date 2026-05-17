---
title: "KmlLayer-klass"
type: docs
weight: 140
url: /sv/python-net/aspose.gis.formats.kml/kmllayer/
---

**Summary:** Represents a Kml layer with non-destructive behavior that supports read and writing of features and attributes at one time.<br/>            A Kml layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis.formats.kml](/psd/python-net/aspose.gis.formats.kml/)

**Full Name:** aspose.gis.formats.kml.KmlLayer

**Inheritance:** VectorLayer

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Beskrivning** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Hämtar samlingen av anpassade attribut för funktioner i denna [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| antal | int | r | Hämtar antalet funktioner i detta lager. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Hämtar [KmlLayer.driver](/psd/python-net/aspose.gis.formats.kml/kmllayer/) som skapade detta lager. |
| features | [Feature[]](/psd/python-net/aspose.gis/feature) | r | Hämtar listan med funktioner. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Hämtar geometrins typ för lagret. |
| ground_overlay_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlGroundOverlayInfo> | r | Lista med KmlGroundOverlayInfo från GroundOverlay-noder |
| network_link_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlNetworkLinkInfo> | r | Lista med KmlNetworkLinkInfo från NetworkLink-noder |
| region_list | System.Collections.Generic.List<Aspose.Gis.Formats.Kml.SpecificFields.KmlRegionInfo> | r | Lista med KmlRegionInfo från Region-noder |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Hämta det rumsliga referenssystemet för detta lager. För KML är detta alltid WGS84. |
## **Methods**
| **Name** | **Beskrivning** |
| :- | :- |
| [add(feature)](#add_feature_1) | Lägger till ett nytt objekt i lagret, om det stöds av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [add(feature, style)](#add_feature_style_2) | Lägger till ett nytt objekt med den angivna stilen i lagret, om det stöds av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [as_in_memory()](#as_in_memory__3) | Skapa en lagerklon i InMemory-formatet. |
| [construct_feature()](#construct_feature__4) | Skapar (men lägger inte till i lagret) ett nytt objekt med attribut som matchar samlingen av attribut i detta lager.<br/>            När du är klar med att ange data för objektet, använd [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) för att lägga till objektet i lagret. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Konvertera ett lager till ett annat format. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Konvertera ett lager till ett annat format. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Konvertera ett lager till ett annat format. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Konvertera ett lager till ett annat format. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Kopierar attribut från en annan [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) till denna. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Kopierar attribut från en annan [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) till denna. |
| [create(path, driver)](#create_path_driver_11) | Skapar lagret och öppnar det för att lägga till nya objekt. |
| [create(path, driver)](#create_path_driver_12) | Skapar lagret och öppnar det för att lägga till nya objekt. |
| [create(path, driver, options)](#create_path_driver_options_13) | Skapar lagret och öppnar det för att lägga till nya objekt. |
| [create(path, driver, options)](#create_path_driver_options_14) | Skapar lagret och öppnar det för att lägga till nya objekt. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Skapar lagret och öppnar det för tillägg. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Skapar lagret och öppnar det för tillägg. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Skapar lagret och öppnar det för tillägg. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Skapar lagret och öppnar det för tillägg. |
| [get_extent()](#get_extent__19) | Hämtar ett rumsligt omfång för detta lager. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Skär ett lager mot det aktuella lagret med geometri. |
| [join(layer, options)](#join_layer_options_21) | Kopplar ett lager till det aktuella lagret. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Kopplar ett lager till det aktuella lagret med geometri. |
| [nearest_to(point)](#nearest_to_point_23) | Hämtar det närmaste objektet till den angivna punkten. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Hämtar det närmaste objektet till den angivna koordinaten. |
| [open(path, driver)](#open_path_driver_25) | Öppna lagret för läsning. |
| [open(path, driver)](#open_path_driver_26) | Öppna lagret för läsning. |
| [open(path, driver, options)](#open_path_driver_options_27) | Öppna lagret för läsning. |
| [open(path, driver, options)](#open_path_driver_options_28) | Öppna lagret för läsning. |
| [remove_at(index)](#remove_at_index_29) | Ta bort [Feature](/psd/python-net/aspose.gis/feature/) på det angivna indexet. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Ersätt [Feature](/psd/python-net/aspose.gis/feature/) på det angivna indexet. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Sparar objektssekvensen till lagret. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Sparar objektssekvensen till lagret. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Sparar objektssekvensen till lagret. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Sparar objektssekvensen till lagret. |
| [split_to()](#split_to__35) | Dela upp objekt efter geometrityp. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Laddar attributindex för att snabba upp filtrering efter attributvärde i filtermetoder som Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Om indexet inte finns skapas det först. Använd <paramref name="forceRebuild" /> för att tvinga ombyggnad av indexet. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Laddar attributindex för att snabba upp filtrering efter attributvärde i filtermetoder som Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Om indexet inte finns skapas det först. Använd <paramref name="forceRebuild" /> för att tvinga ombyggnad av indexet. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Laddar spatialt index för att snabba upp filtrering efter attributvärde i filtermetoder som Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            och Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Om indexet inte finns skapas det först. Använd <paramref name="forceRebuild" /> för att tvinga ombyggnad av indexet. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Laddar spatialt index för att snabba upp filtrering efter attributvärde i filtermetoder som Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            och Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Om indexet inte finns skapas det först. Använd <paramref name="forceRebuild" /> för att tvinga ombyggnad av indexet. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Väljer objekt med attributvärde lika med det angivna värdet. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Väljer objekt med attributvärde större än det angivna värdet. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Väljer objekt med attributvärde större än eller lika med det angivna värdet. |
| [where_intersects(extent)](#where_intersects_extent_43) | Filtrerar funktioner baserat på omfånget. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Filtrerar funktioner baserat på den angivna geometrin. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Filtrerar funktioner baserat på unionen av alla geometrier i den andra funktionssekvensen. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Väljer funktioner med attributvärde som inte är lika med det angivna värdet. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Väljer funktioner med attribut som inte är null. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Väljer funktioner med attribut lika med null. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Väljer funktioner med attribut satt. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Väljer funktioner med attributvärde mindre än det angivna värdet. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Väljer funktioner med attributvärde mindre än eller lika med det angivna värdet. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Väljer funktioner där specificerat attribut inte är satt. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Lägger till ett nytt objekt i lagret, om det stöds av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Funktionen att lägga till. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Lägger till ett nytt objekt med den angivna stilen i lagret, om det stöds av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/)'s [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Funktionen att lägga till. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | Funktionens stil. Använd <see langword=\"null\" /> för att ange saknad stil. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Skapa en lagerklon i InMemory-formatet.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | InMemory-lagret. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Skapar (men lägger inte till i lagret) ett nytt objekt med attribut som matchar samlingen av attribut i detta lager.<br/>            När du är klar med att ange data för objektet, använd [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) för att lägga till objektet i lagret.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | En ny funktion. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Konvertera ett lager till ett annat format.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_path | string | Sökväg till lagret som kommer att konverteras. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för källagret. |
| destination_path | string | Sökväg till lagret som kommer att skapas som ett resultat av konverteringen. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för destinationslagret. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Konvertera ett lager till ett annat format.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till lagret som kommer att konverteras. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för källagret. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till lagret som kommer att skapas som ett resultat av konverteringen. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för destinationslagret. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Konvertera ett lager till ett annat format.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_path | string | Sökväg till lagret som kommer att konverteras. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för källagret. |
| destination_path | string | Sökväg till lagret som kommer att skapas som ett resultat av konverteringen. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för destinationslagret. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Alternativ för konverteringsproceduren. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Konvertera ett lager till ett annat format.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till lagret som kommer att konverteras. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för källagret. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till lagret som kommer att skapas som ett resultat av konverteringen. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för destinationslagret. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Alternativ för konverteringsproceduren. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Kopierar attribut från en annan [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) till denna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktionssekvensen att kopiera attribut från. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Kopierar attribut från en annan [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) till denna.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktionssekvensen att kopiera attribut från. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | En instans av anpassad [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) som kommer att bearbeta attributen ett i taget. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Skapar lagret och öppnar det för att lägga till nya objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett skrivskyddat lager. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Skapar lagret och öppnar det för att lägga till nya objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett skrivskyddat lager. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Skapar lagret och öppnar det för att lägga till nya objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett skrivskyddat lager. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Skapar lagret och öppnar det för att lägga till nya objekt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett skrivskyddat lager. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Skapar lagret och öppnar det för tillägg.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | En instans av [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Hämtar ett rumsligt omfång för detta lager.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Ett rumsligt omfång för detta lager. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Skär ett lager mot det aktuella lagret med geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett lager att skära av. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett nytt lager som resultat av att skära två lager. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Kopplar ett lager till det aktuella lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett lager att slå ihop. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Parametrar för sammanslagning. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett nytt lager som resultat av att slå ihop två lager. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Kopplar ett lager till det aktuella lagret med geometri.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett lager att slå ihop. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Parametrar för sammanslagning. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett nytt lager som resultat av att slå ihop två lager. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Hämtar det närmaste objektet till den angivna punkten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Punkten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Det närmaste objektet till den angivna punkten. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Hämtar det närmaste objektet till den angivna koordinaten.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| x | double | X för koordinaten. |
| y | double | Y för koordinaten. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Det närmaste objektet till den angivna koordinaten. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Öppna lagret för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett skrivskyddat lager. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Öppna lagret för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett skrivskyddat lager. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Öppna lagret för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | string | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett skrivskyddat lager. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Öppna lagret för läsning.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till filen. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Drivrutin att använda. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Drivrutinsspecifika alternativ. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Ett skrivskyddat lager. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Ta bort [Feature](/psd/python-net/aspose.gis/feature/) på det angivna indexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Indexet för objektet. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Ersätt [Feature](/psd/python-net/aspose.gis/feature/) på det angivna indexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index | int | Indexet för objektet. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | Objektet att sätta. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Sparar objektssekvensen till lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_path | string | Sökväg till utdatalagret. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för utdatalagret. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Sparar objektssekvensen till lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till utdatalagret. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för utdatalagret. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

Sparar objektssekvensen till lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_path | string | Sökväg till utdatalagret. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för utdatalagret. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Alternativ för sparningsproceduren. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

Sparar objektssekvensen till lagret.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till utdatalagret. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Formatdrivrutinen för utdatalagret. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Alternativ för sparningsproceduren. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Dela upp objekt efter geometrityp.

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Lager med samma geometrityp. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Laddar attributindex för att snabba upp filtrering efter attributvärde i filtermetoder som Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Om indexet inte finns skapas det först. Använd <paramref name="forceRebuild" /> för att tvinga ombyggnad av indexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index_path | string | Sökväg till indexfilen. |
| attribute_name | string | Namn på attributet att bygga index på. |
| force_rebuild | bool | Om indexet ska återskapas även om det redan finns. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Laddar attributindex för att snabba upp filtrering efter attributvärde i filtermetoder som Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Om indexet inte finns skapas det först. Använd <paramref name="forceRebuild" /> för att tvinga ombyggnad av indexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till indexfilen. |
| attribute_name | string | Namn på attributet att bygga index på. |
| force_rebuild | bool | Om indexet ska återskapas även om det redan finns. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Laddar spatialt index för att snabba upp filtrering efter attributvärde i filtermetoder som Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            och Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Om indexet inte finns skapas det först. Använd <paramref name="forceRebuild" /> för att tvinga ombyggnad av indexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index_path | string | Sökväg till indexfilen. |
| force_rebuild | bool | Om indexet ska återskapas även om det redan finns. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Laddar spatialt index för att snabba upp filtrering efter attributvärde i filtermetoder som Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            och Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Om indexet inte finns skapas det först. Använd <paramref name="forceRebuild" /> för att tvinga ombyggnad av indexet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Sökväg till indexfilen. |
| force_rebuild | bool | Om indexet ska återskapas även om det redan finns. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

Väljer objekt med attributvärde lika med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objekt med attributvärde lika med det angivna värdet. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

Väljer objekt med attributvärde större än det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objekt med attributvärde större än det angivna värdet. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

Väljer objekt med attributvärde större än eller lika med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Objekt med attributvärde större än eller lika med det angivna värdet. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

Filtrerar funktioner baserat på omfånget.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filtrera omfång. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner som skär med den angivna geometrin. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

Filtrerar funktioner baserat på den angivna geometrin.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filtrera geometri. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner som skär med den angivna geometrin. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

Filtrerar funktioner baserat på unionen av alla geometrier i den andra funktionssekvensen.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sekvens för andra funktioner. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner som skär med unionen av alla geometrier i den andra funktionernas sekvens. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

Väljer funktioner med attributvärde som inte är lika med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde som inte är lika med det angivna värdet. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

Väljer funktioner med attribut som inte är null.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde som inte är lika med null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

Väljer funktioner med attribut lika med null.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde lika med null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

Väljer funktioner med attribut satt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med satt attributvärde. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

Väljer funktioner med attributvärde mindre än det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde mindre än det angivna värdet. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

Väljer funktioner med attributvärde mindre än eller lika med det angivna värdet.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |
| value | objekt | Värde att jämföra med. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med attributvärde mindre än eller lika med det angivna värdet. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

Väljer funktioner där specificerat attribut inte är satt.

**Parameters:**

| Parameter | Typ | Beskrivning |
| :- | :- | :- |
| attribute_name | string | Attribut att filtrera på. |

**Returns**

| Typ | Beskrivning |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Funktioner med odefinierat attributvärde. |


