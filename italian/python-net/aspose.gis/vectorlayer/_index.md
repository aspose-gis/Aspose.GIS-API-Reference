---
title: "Classe VectorLayer"
type: docs
weight: 4060
url: /it/python-net/aspose.gis/vectorlayer/
---

**Summary:** Represents a vector layer.<br/>            A vector layer is a collection of geographic features, stored in a file.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.VectorLayer

**Inheritance:** FeaturesSequence

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Descrizione** |
| :- | :- | :- | :- |
| attributes | [BaseFeatureAttributeCollection](/psd/python-net/aspose.gis/basefeatureattributecollection) | r | Ottiene la collezione di attributi personalizzati per le feature in questo [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |
| conteggio | int | r | Ottiene il numero di feature in questo layer. |
| driver | [Driver](/psd/python-net/aspose.gis/driver) | r | Ottiene il [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/) che ha istanziato questo layer. |
| geometry_type | [GeometryType](/psd/python-net/aspose.gis.geometries/geometrytype/) | r | Restituisce il tipo di geometria per il layer. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r | Restituisce il sistema di riferimento spaziale di questa sequenza di feature. |
## **Methods**
| **Name** | **Descrizione** |
| :- | :- |
| [add(feature)](#add_feature_1) | Aggiunge una nuova feature al layer, se supportato dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) del [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [add(feature, style)](#add_feature_style_2) | Aggiunge una nuova feature con lo stile specificato al layer, se supportato dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) del [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/). |
| [as_in_memory()](#as_in_memory__3) | Crea un clone di layer nel formato InMemory. |
| [construct_feature()](#construct_feature__4) | Crea (ma non aggiunge al layer) una nuova feature con attributi corrispondenti alla collezione di attributi di questo layer.<br/>            Quando hai terminato di impostare i dati per la feature, usa [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) per aggiungere la feature al layer. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_5) | Converti un layer in un formato diverso. |
| [convert(source_path, source_driver, destination_path, destination_driver)](#convert_source_path_source_driver_destination_path_destination_driver_6) | Converti un layer in un formato diverso. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_7) | Converti un layer in un formato diverso. |
| [convert(source_path, source_driver, destination_path, destination_driver, options)](#convert_source_path_source_driver_destination_path_destination_driver_options_8) | Converti un layer in un formato diverso. |
| [copy_attributes(features_sequence)](#copy_attributes_features_sequence_9) | Copia gli attributi di un altro [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) in questo. |
| [copy_attributes(features_sequence, converter)](#copy_attributes_features_sequence_converter_10) | Copia gli attributi di un altro [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) in questo. |
| [create(path, driver)](#create_path_driver_11) | Crea il layer e lo apre per aggiungere nuove feature. |
| [create(path, driver)](#create_path_driver_12) | Crea il layer e lo apre per aggiungere nuove feature. |
| [create(path, driver, options)](#create_path_driver_options_13) | Crea il layer e lo apre per aggiungere nuove feature. |
| [create(path, driver, options)](#create_path_driver_options_14) | Crea il layer e lo apre per aggiungere nuove feature. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_15) | Crea il livello e lo apre per l'aggiunta. |
| [create(path, driver, options, spatial_reference_system)](#create_path_driver_options_spatial_reference_system_16) | Crea il livello e lo apre per l'aggiunta. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_17) | Crea il livello e lo apre per l'aggiunta. |
| [create(path, driver, spatial_reference_system)](#create_path_driver_spatial_reference_system_18) | Crea il livello e lo apre per l'aggiunta. |
| [get_extent()](#get_extent__19) | Restituisce l'estensione spaziale di questo layer. |
| [intersection_by_geometry(layer)](#intersection_by_geometry_layer_20) | Interseca un layer con il layer corrente tramite geometria. |
| [join(layer, options)](#join_layer_options_21) | Unisce un layer al layer corrente. |
| [join_by_geometry(layer, options)](#join_by_geometry_layer_options_22) | Unisce un layer al layer corrente tramite geometria. |
| [nearest_to(point)](#nearest_to_point_23) | Restituisce la feature più vicina al punto fornito. |
| [nearest_to(x, y)](#nearest_to_x_y_24) | Restituisce la feature più vicina alla coordinata fornita. |
| [open(path, driver)](#open_path_driver_25) | Apri il layer in lettura. |
| [open(path, driver)](#open_path_driver_26) | Apri il layer in lettura. |
| [open(path, driver, options)](#open_path_driver_options_27) | Apri il layer in lettura. |
| [open(path, driver, options)](#open_path_driver_options_28) | Apri il layer in lettura. |
| [remove_at(index)](#remove_at_index_29) | Rimuove la [Feature](/psd/python-net/aspose.gis/feature/) all'indice specificato. |
| [replace_at(index, feature)](#replace_at_index_feature_30) | Sostituisce la [Feature](/psd/python-net/aspose.gis/feature/) all'indice specificato. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_31) | Salva la sequenza di feature nel layer. |
| [save_to(destination_path, destination_driver)](#save_to_destination_path_destination_driver_32) | Salva la sequenza di feature nel layer. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_33) | Salva la sequenza di feature nel layer. |
| [save_to(destination_path, destination_driver, options)](#save_to_destination_path_destination_driver_options_34) | Salva la sequenza di feature nel layer. |
| [split_to()](#split_to__35) | Dividi le feature per tipo di geometria. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_36) | Carica l'indice degli attributi per velocizzare il filtraggio per valore degli attributi nei metodi di filtro come Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Se l'indice non esiste lo crea prima. Usa <paramref name=\"forceRebuild\" /> per forzare la ricreazione dell'indice. |
| [use_attributes_index(index_path, attribute_name, force_rebuild)](#use_attributes_index_index_path_attribute_name_force_rebuild_37) | Carica l'indice degli attributi per velocizzare il filtraggio per valore degli attributi nei metodi di filtro come Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Se l'indice non esiste lo crea prima. Usa <paramref name=\"forceRebuild\" /> per forzare la ricreazione dell'indice. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_38) | Carica l'indice spaziale per velocizzare il filtraggio per valore degli attributi nei metodi di filtro come Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            e Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Se l'indice non esiste lo crea prima. Usa <paramref name=\"forceRebuild\" /> per forzare la ricreazione dell'indice. |
| [use_spatial_index(index_path, force_rebuild)](#use_spatial_index_index_path_force_rebuild_39) | Carica l'indice spaziale per velocizzare il filtraggio per valore degli attributi nei metodi di filtro come Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            e Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Se l'indice non esiste lo crea prima. Usa <paramref name=\"forceRebuild\" /> per forzare la ricreazione dell'indice. |
| [where_equal(attribute_name, value)](#where_equal_attribute_name_value_40) | Seleziona le feature con valore dell'attributo uguale al valore fornito. |
| [where_greater(attribute_name, value)](#where_greater_attribute_name_value_41) | Seleziona le feature con valore dell'attributo maggiore del valore fornito. |
| [where_greater_or_equal(attribute_name, value)](#where_greater_or_equal_attribute_name_value_42) | Seleziona le feature con valore dell'attributo maggiore o uguale al valore fornito. |
| [where_intersects(extent)](#where_intersects_extent_43) | Filtra le feature in base all'estensione. |
| [where_intersects(geometry)](#where_intersects_geometry_44) | Filtra le feature in base alla geometria fornita. |
| [where_intersects(sequence)](#where_intersects_sequence_45) | Filtra le feature in base all'unione di tutte le geometrie nella sequenza di altre feature. |
| [where_not_equal(attribute_name, value)](#where_not_equal_attribute_name_value_46) | Seleziona le feature il cui valore dell'attributo non è uguale al valore fornito. |
| [where_not_null(attribute_name)](#where_not_null_attribute_name_47) | Seleziona le feature il cui attributo non è uguale a null. |
| [where_null(attribute_name)](#where_null_attribute_name_48) | Seleziona le feature il cui attributo è uguale a null. |
| [where_set(attribute_name)](#where_set_attribute_name_49) | Seleziona le feature con attributo impostato. |
| [where_smaller(attribute_name, value)](#where_smaller_attribute_name_value_50) | Seleziona le feature il cui valore dell'attributo è inferiore al valore fornito. |
| [where_smaller_or_equal(attribute_name, value)](#where_smaller_or_equal_attribute_name_value_51) | Seleziona le feature il cui valore dell'attributo è inferiore o uguale al valore fornito. |
| [where_unset(attribute_name)](#where_unset_attribute_name_52) | Seleziona le feature dove l'attributo specificato non è impostato. |


### Method: add(feature) {#add_feature_1}


```
 add(feature) 
```

Aggiunge una nuova feature al layer, se supportato dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) del [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | La feature da aggiungere. |

### Method: add(feature, style) {#add_feature_style_2}


```
 add(feature, style) 
```

Aggiunge una nuova feature con lo stile specificato al layer, se supportato dal [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) del [VectorLayer.driver](/psd/python-net/aspose.gis/vectorlayer/).

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | La feature da aggiungere. |
| style | [IFeatureStyle](/psd/python-net/aspose.gis/ifeaturestyle) | Lo stile della feature. Usa <see langword="null" /> per indicare uno stile mancante. |

### Method: as_in_memory() {#as_in_memory__3}


```
 as_in_memory() 
```

Crea un clone di layer nel formato InMemory.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Il layer InMemory. |


### Method: construct_feature() {#construct_feature__4}


```
 construct_feature() 
```

Crea (ma non aggiunge al layer) una nuova feature con attributi corrispondenti alla collezione di attributi di questo layer.<br/>            Quando hai terminato di impostare i dati per la feature, usa [VectorLayer.add(feature)](/psd/python-net/aspose.gis/vectorlayer/) per aggiungere la feature al layer.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | Una nuova feature. |


### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_5}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Converti un layer in un formato diverso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_path | string | Percorso del layer che sarà convertito. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il layer di origine. |
| destination_path | string | Percorso del layer che sarà creato come risultato della conversione. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il layer di destinazione. |

### Method: convert(source_path, source_driver, destination_path, destination_driver)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_6}


```
 convert(source_path, source_driver, destination_path, destination_driver) 
```

Converti un layer in un formato diverso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del layer che sarà convertito. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il layer di origine. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del layer che sarà creato come risultato della conversione. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il layer di destinazione. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_7}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Converti un layer in un formato diverso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_path | string | Percorso del layer che sarà convertito. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il layer di origine. |
| destination_path | string | Percorso del layer che sarà creato come risultato della conversione. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il layer di destinazione. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Opzioni per la procedura di conversione. |

### Method: convert(source_path, source_driver, destination_path, destination_driver, options)  [static] {#convert_source_path_source_driver_destination_path_destination_driver_options_8}


```
 convert(source_path, source_driver, destination_path, destination_driver, options) 
```

Converti un layer in un formato diverso.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| source_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del layer che sarà convertito. |
| source_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il layer di origine. |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del layer che sarà creato come risultato della conversione. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il layer di destinazione. |
| options | [ConversionOptions](/psd/python-net/aspose.gis/conversionoptions) | Opzioni per la procedura di conversione. |

### Method: copy_attributes(features_sequence) {#copy_attributes_features_sequence_9}


```
 copy_attributes(features_sequence) 
```

Copia gli attributi di un altro [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) in questo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | La sequenza di feature da cui copiare gli attributi. |

### Method: copy_attributes(features_sequence, converter) {#copy_attributes_features_sequence_converter_10}


```
 copy_attributes(features_sequence, converter) 
```

Copia gli attributi di un altro [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) in questo.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | La sequenza di feature da cui copiare gli attributi. |
| converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | Un'istanza personalizzata di [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter/) che elaborerà gli attributi uno per uno. |

### Method: create(path, driver)  [static] {#create_path_driver_11}


```
 create(path, driver) 
```

Crea il layer e lo apre per aggiungere nuove feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un layer di sola scrittura. |


### Method: create(path, driver)  [static] {#create_path_driver_12}


```
 create(path, driver) 
```

Crea il layer e lo apre per aggiungere nuove feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un layer di sola scrittura. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_13}


```
 create(path, driver, options) 
```

Crea il layer e lo apre per aggiungere nuove feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un layer di sola scrittura. |


### Method: create(path, driver, options)  [static] {#create_path_driver_options_14}


```
 create(path, driver, options) 
```

Crea il layer e lo apre per aggiungere nuove feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un layer di sola scrittura. |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_15}


```
 create(path, driver, options, spatial_reference_system) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, options, spatial_reference_system)  [static] {#create_path_driver_options_spatial_reference_system_16}


```
 create(path, driver, options, spatial_reference_system) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_17}


```
 create(path, driver, spatial_reference_system) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: create(path, driver, spatial_reference_system)  [static] {#create_path_driver_spatial_reference_system_18}


```
 create(path, driver, spatial_reference_system) 
```

Crea il livello e lo apre per l'aggiunta.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistema di riferimento spaziale. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un'istanza di [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/). |


### Method: get_extent() {#get_extent__19}


```
 get_extent() 
```

Restituisce l'estensione spaziale di questo layer.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Un'estensione spaziale di questo layer. |


### Method: intersection_by_geometry(layer) {#intersection_by_geometry_layer_20}


```
 intersection_by_geometry(layer) 
```

Interseca un layer con il layer corrente tramite geometria.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello da intersecare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un nuovo livello come risultato dell'intersezione di due livelli. |


### Method: join(layer, options) {#join_layer_options_21}


```
 join(layer, options) 
```

Unisce un layer al layer corrente.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello da unire. |
| options | [JoinOptions](/psd/python-net/aspose.gis.relationship.joins/joinoptions/) | Parametri di unione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un nuovo livello come risultato dell'unione di due livelli. |


### Method: join_by_geometry(layer, options) {#join_by_geometry_layer_options_22}


```
 join_by_geometry(layer, options) 
```

Unisce un layer al layer corrente tramite geometria.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello da unire. |
| options | [JoinByGeometryOptions](/psd/python-net/aspose.gis.relationship.joins/joinbygeometryoptions/) | Parametri di unione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un nuovo livello come risultato dell'unione di due livelli. |


### Method: nearest_to(point) {#nearest_to_point_23}


```
 nearest_to(point) 
```

Restituisce la feature più vicina al punto fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| point | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Il punto. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | La caratteristica più vicina al punto fornito. |


### Method: nearest_to(x, y) {#nearest_to_x_y_24}


```
 nearest_to(x, y) 
```

Restituisce la feature più vicina alla coordinata fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| x | double | X della coordinata. |
| y | double | Y della coordinata. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [Feature](/psd/python-net/aspose.gis/feature) | La caratteristica più vicina alla coordinata fornita. |


### Method: open(path, driver)  [static] {#open_path_driver_25}


```
 open(path, driver) 
```

Apri il layer in lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello di sola lettura. |


### Method: open(path, driver)  [static] {#open_path_driver_26}


```
 open(path, driver) 
```

Apri il layer in lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello di sola lettura. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_27}


```
 open(path, driver, options) 
```

Apri il layer in lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | string | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello di sola lettura. |


### Method: open(path, driver, options)  [static] {#open_path_driver_options_28}


```
 open(path, driver, options) 
```

Apri il layer in lettura.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file. |
| driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Driver da utilizzare. |
| options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | Opzioni specifiche del driver. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Un livello di sola lettura. |


### Method: remove_at(index) {#remove_at_index_29}


```
 remove_at(index) 
```

Rimuove la [Feature](/psd/python-net/aspose.gis/feature/) all'indice specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice della caratteristica. |

### Method: replace_at(index, feature) {#replace_at_index_feature_30}


```
 replace_at(index, feature) 
```

Sostituisce la [Feature](/psd/python-net/aspose.gis/feature/) all'indice specificato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index | int | L'indice della caratteristica. |
| feature | [Feature](/psd/python-net/aspose.gis/feature) | La caratteristica da impostare. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_31}


```
 save_to(destination_path, destination_driver) 
```

Salva la sequenza di feature nel layer.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_path | string | Percorso del livello di output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il livello di output. |

### Method: save_to(destination_path, destination_driver) {#save_to_destination_path_destination_driver_32}


```
 save_to(destination_path, destination_driver) 
```

Salva la sequenza di feature nel layer.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del livello di output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il livello di output. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_33}


```
 save_to(destination_path, destination_driver, options) 
```

Salva la sequenza di feature nel layer.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_path | string | Percorso del livello di output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il livello di output. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opzioni per la procedura di salvataggio. |

### Method: save_to(destination_path, destination_driver, options) {#save_to_destination_path_destination_driver_options_34}


```
 save_to(destination_path, destination_driver, options) 
```

Salva la sequenza di feature nel layer.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| destination_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del livello di output. |
| destination_driver | [FileDriver](/psd/python-net/aspose.gis/filedriver) | Il driver di formato per il livello di output. |
| options | [SavingOptions](/psd/python-net/aspose.gis/savingoptions) | Opzioni per la procedura di salvataggio. |

### Method: split_to() {#split_to__35}


```
 split_to() 
```

Dividi le feature per tipo di geometria.

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [VectorLayer[]](/psd/python-net/aspose.gis/vectorlayer) | Livelli con lo stesso tipo di geometria. |


### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_36}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Carica l'indice degli attributi per velocizzare il filtraggio per valore degli attributi nei metodi di filtro come Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Se l'indice non esiste lo crea prima. Usa <paramref name=\"forceRebuild\" /> per forzare la ricreazione dell'indice.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index_path | string | Percorso del file di indice. |
| attribute_name | string | Nome dell'attributo su cui costruire l'indice. |
| force_rebuild | bool | Se ricreare l'indice anche se esiste già. |

### Method: use_attributes_index(index_path, attribute_name, force_rebuild) {#use_attributes_index_index_path_attribute_name_force_rebuild_37}


```
 use_attributes_index(index_path, attribute_name, force_rebuild) 
```

Carica l'indice degli attributi per velocizzare il filtraggio per valore degli attributi nei metodi di filtro come Aspose.Gis.FeaturesSequence.WhereGreater``1(string,``0).<br/>            Se l'indice non esiste lo crea prima. Usa <paramref name=\"forceRebuild\" /> per forzare la ricreazione dell'indice.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file di indice. |
| attribute_name | string | Nome dell'attributo su cui costruire l'indice. |
| force_rebuild | bool | Se ricreare l'indice anche se esiste già. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_38}


```
 use_spatial_index(index_path, force_rebuild) 
```

Carica l'indice spaziale per velocizzare il filtraggio per valore degli attributi nei metodi di filtro come Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            e Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Se l'indice non esiste lo crea prima. Usa <paramref name=\"forceRebuild\" /> per forzare la ricreazione dell'indice.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index_path | string | Percorso del file di indice. |
| force_rebuild | bool | Se ricreare l'indice anche se esiste già. |

### Method: use_spatial_index(index_path, force_rebuild) {#use_spatial_index_index_path_force_rebuild_39}


```
 use_spatial_index(index_path, force_rebuild) 
```

Carica l'indice spaziale per velocizzare il filtraggio per valore degli attributi nei metodi di filtro come Aspose.Gis.FeaturesSequence.WhereIntersects(Aspose.Gis.Geometries.IGeometry)<br/>            e Aspose.Gis.VectorLayer.NearestTo(float,float).<br/>            Se l'indice non esiste lo crea prima. Usa <paramref name=\"forceRebuild\" /> per forzare la ricreazione dell'indice.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| index_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Percorso del file di indice. |
| force_rebuild | bool | Se ricreare l'indice anche se esiste già. |

### Method: where_equal(attribute_name, value) {#where_equal_attribute_name_value_40}


```
 where_equal(attribute_name, value) 
```

Seleziona le feature con valore dell'attributo uguale al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Caratteristiche con valore dell'attributo uguale al valore fornito. |


### Method: where_greater(attribute_name, value) {#where_greater_attribute_name_value_41}


```
 where_greater(attribute_name, value) 
```

Seleziona le feature con valore dell'attributo maggiore del valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Caratteristiche con valore dell'attributo maggiore del valore fornito. |


### Method: where_greater_or_equal(attribute_name, value) {#where_greater_or_equal_attribute_name_value_42}


```
 where_greater_or_equal(attribute_name, value) 
```

Seleziona le feature con valore dell'attributo maggiore o uguale al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Caratteristiche con valore dell'attributo maggiore o uguale al valore fornito. |


### Method: where_intersects(extent) {#where_intersects_extent_43}


```
 where_intersects(extent) 
```

Filtra le feature in base all'estensione.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Filtra l'estensione. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features che si intersecano con la geometria fornita. |


### Method: where_intersects(geometry) {#where_intersects_geometry_44}


```
 where_intersects(geometry) 
```

Filtra le feature in base alla geometria fornita.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Filtra la geometria. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Features che si intersecano con la geometria fornita. |


### Method: where_intersects(sequence) {#where_intersects_sequence_45}


```
 where_intersects(sequence) 
```

Filtra le feature in base all'unione di tutte le geometrie nella sequenza di altre feature.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Sequenza di altre feature. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature che si intersecano con l'unione di tutte le geometrie nella sequenza di altre feature. |


### Method: where_not_equal(attribute_name, value) {#where_not_equal_attribute_name_value_46}


```
 where_not_equal(attribute_name, value) 
```

Seleziona le feature il cui valore dell'attributo non è uguale al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo diverso dal valore fornito. |


### Method: where_not_null(attribute_name) {#where_not_null_attribute_name_47}


```
 where_not_null(attribute_name) 
```

Seleziona le feature il cui attributo non è uguale a null.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo diverso da null. |


### Method: where_null(attribute_name) {#where_null_attribute_name_48}


```
 where_null(attribute_name) 
```

Seleziona le feature il cui attributo è uguale a null.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo uguale a null. |


### Method: where_set(attribute_name) {#where_set_attribute_name_49}


```
 where_set(attribute_name) 
```

Seleziona le feature con attributo impostato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo impostato. |


### Method: where_smaller(attribute_name, value) {#where_smaller_attribute_name_value_50}


```
 where_smaller(attribute_name, value) 
```

Seleziona le feature il cui valore dell'attributo è inferiore al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo inferiore al valore fornito. |


### Method: where_smaller_or_equal(attribute_name, value) {#where_smaller_or_equal_attribute_name_value_51}


```
 where_smaller_or_equal(attribute_name, value) 
```

Seleziona le feature il cui valore dell'attributo è inferiore o uguale al valore fornito.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |
| valore | object | Valore da confrontare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo inferiore o uguale al valore fornito. |


### Method: where_unset(attribute_name) {#where_unset_attribute_name_52}


```
 where_unset(attribute_name) 
```

Seleziona le feature dove l'attributo specificato non è impostato.

**Parameters:**

| Parametro | Tipo | Descrizione |
| :- | :- | :- |
| attribute_name | string | Attributo per filtrare. |

**Returns**

| Tipo | Descrizione |
| :- | :- |
| [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Feature con valore dell'attributo non impostato. |


