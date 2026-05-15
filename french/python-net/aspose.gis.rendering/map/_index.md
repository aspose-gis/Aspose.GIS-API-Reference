---
title: "Classe Map"
type: docs
weight: 100
url: /fr/python-net/aspose.gis.rendering/map/
---

**Summary:** Map is a collection of layers that can be rendered on top of each other via [Renderer](/psd/python-net/aspose.gis.rendering/renderer/).

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Map

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Map()](#Map__1) | Crée une nouvelle instance de la classe <c>Map</c>. |
| [Map(width, height)](#Map_width_height_2) | Crée une nouvelle instance de la classe <c>Map</c>. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| background_color | System.Drawing.Color | r/w | Couleur d'arrière-plan de la carte. Par défaut à . |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | r/w | Spécifie les limites de la carte à rendre.<br/>            Si défini à <see langword=\"null\" />, l'étendue est calculée pendant le rendu pour inclure toutes les géométries dans toutes les couches. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Hauteur visuelle de la carte. |
| padding | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Spécifie le remplissage à ajouter à l'étendue. |
| resolution | double | r/w | Résolution à utiliser pour rendre cette carte et pour convertir entre [Measurement](/psd/python-net/aspose.gis.rendering/measurement/). Par défaut à 96. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [Map.spatial_reference_system](/psd/python-net/aspose.gis.rendering/map/) de la carte. |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r/w | Largeur visuelle de la carte. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add(features_sequence)](#add_features_sequence_1) | Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout. |
| [add(features_sequence, symbolizer)](#add_features_sequence_symbolizer_2) | Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout. |
| [add(features_sequence, symbolizer, labeling)](#add_features_sequence_symbolizer_labeling_3) | Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout. |
| [add(layer, colorizer, keep_open)](#add_layer_colorizer_keep_open_4) | Crée un [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) avec le coloriseur par défaut et l'ajoute à la carte. |
| [add(layer, keep_open)](#add_layer_keep_open_5) | Crée un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) avec le symboliseur par défaut et l'ajoute à la carte. Les couches sont rendues dans l'ordre d'ajout. |
| [add(layer, symbolizer, keep_open)](#add_layer_symbolizer_keep_open_6) | Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout. |
| [add(layer, symbolizer, labeling, default_reference_system, keep_open)](#add_layer_symbolizer_labeling_default_reference_system_keep_open_7) | Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout. |
| [add(layer, symbolizer, labeling, keep_open)](#add_layer_symbolizer_labeling_keep_open_8) | Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout. |
| [add(map_layer)](#add_map_layer_9) | Ajoute une couche à la carte. Les couches sont rendues dans l'ordre d'ajout. |
| [render(output_path, renderer)](#render_output_path_renderer_10) | Rend la carte dans un fichier. |
| [render(output_path, renderer)](#render_output_path_renderer_11) | Rend la carte dans un fichier. |


### Constructor: Map() {#Map__1}


```
 Map() 
```

Crée une nouvelle instance de la classe <c>Map</c>.

### Constructor: Map(width, height) {#Map_width_height_2}


```
 Map(width, height) 
```

Crée une nouvelle instance de la classe <c>Map</c>.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| width | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Largeur de la carte. |
| height | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | Hauteur de la carte. |

### Method: add(features_sequence) {#add_features_sequence_1}


```
 add(features_sequence) 
```

Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Une séquence de fonctionnalités à représenter par [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |

### Method: add(features_sequence, symbolizer) {#add_features_sequence_symbolizer_2}


```
 add(features_sequence, symbolizer) 
```

Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Une séquence de fonctionnalités à représenter par [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un symboliseur à utiliser pour le rendu. Si <see langword=\"null\" />, le symboliseur par défaut est utilisé. |

### Method: add(features_sequence, symbolizer, labeling) {#add_features_sequence_symbolizer_labeling_3}


```
 add(features_sequence, symbolizer, labeling) 
```

Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| features_sequence | [FeaturesSequence](/psd/python-net/aspose.gis/featuressequence) | Une séquence de fonctionnalités à représenter par [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un symboliseur à utiliser pour le rendu. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Étiquetage à utiliser pour étiqueter les fonctionnalités de la couche. Si <see langword=\"null\" />, [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) sera utilisé. |

### Method: add(layer, colorizer, keep_open) {#add_layer_colorizer_keep_open_4}


```
 add(layer, colorizer, keep_open) 
```

Crée un [RasterMapLayer](/psd/python-net/aspose.gis.rendering/rastermaplayer/) avec le coloriseur par défaut et l'ajoute à la carte.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/) | Une couche vectorielle à représenter par [RasterLayer](/psd/python-net/aspose.gis.raster/rasterlayer/). |
| colorizer | [RasterColorizer](/psd/python-net/aspose.gis.rendering.colorizers/rastercolorizer/) | Un coloriseur à utiliser pour le rendu. Si <see langword=\"null\" />, le coloriseur par défaut est utilisé. |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche raster ouverte après que l'objet [Map](/psd/python-net/aspose.gis.rendering/map/) soit libéré;<br/>            <see langword=\"false\" /> pour libérer la couche. |

### Method: add(layer, keep_open) {#add_layer_keep_open_5}


```
 add(layer, keep_open) 
```

Crée un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) avec le symboliseur par défaut et l'ajoute à la carte. Les couches sont rendues dans l'ordre d'ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche vectorielle à représenter par [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche vectorielle ouverte après que l'objet [Map](/psd/python-net/aspose.gis.rendering/map/) soit libéré;<br/>            <see langword=\"false\" /> pour libérer la couche. |

### Method: add(layer, symbolizer, keep_open) {#add_layer_symbolizer_keep_open_6}


```
 add(layer, symbolizer, keep_open) 
```

Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche vectorielle à représenter par [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un symboliseur à utiliser pour le rendu. Si <see langword=\"null\" />, le symboliseur par défaut est utilisé. |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche vectorielle ouverte après que l'objet [Map](/psd/python-net/aspose.gis.rendering/map/) soit libéré;<br/>            <see langword=\"false\" /> pour libérer la couche. |

### Method: add(layer, symbolizer, labeling, default_reference_system, keep_open) {#add_layer_symbolizer_labeling_default_reference_system_keep_open_7}


```
 add(layer, symbolizer, labeling, default_reference_system, keep_open) 
```

Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche vectorielle à représenter par [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un symboliseur à utiliser pour le rendu. Si <see langword=\"null\" />, le symboliseur par défaut est utilisé. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Étiquetage à utiliser pour étiqueter les fonctionnalités de la couche. Si <see langword=\"null\" />, le [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) par défaut sera utilisé. |
| default_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Spécifie une valeur pour une référence spatiale source (couche\\séquence) si elle est manquante. La valeur null par défaut sera utilisée. |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche ouverte après que l'objet [Map](/psd/python-net/aspose.gis.rendering/map/) soit libéré ; sinon, <see langword=\"false\" />. |

### Method: add(layer, symbolizer, labeling, keep_open) {#add_layer_symbolizer_labeling_keep_open_8}


```
 add(layer, symbolizer, labeling, keep_open) 
```

Crée et ajoute un [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/) à la carte. Les couches sont rendues dans l'ordre d'ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| layer | [VectorLayer](/psd/python-net/aspose.gis/vectorlayer) | Une couche vectorielle à représenter par [VectorMapLayer](/psd/python-net/aspose.gis.rendering/vectormaplayer/). |
| symbolizer | [VectorSymbolizer](/psd/python-net/aspose.gis.rendering.symbolizers/vectorsymbolizer/) | Un symboliseur à utiliser pour le rendu. Si <see langword=\"null\" />, le symboliseur par défaut est utilisé. |
| labeling | [Labeling](/psd/python-net/aspose.gis.rendering.labelings/labeling/) | Étiquetage à utiliser pour étiqueter les fonctionnalités de la couche. Si <see langword=\"null\" />, le [NullLabeling](/psd/python-net/aspose.gis.rendering.labelings/nulllabeling/) par défaut sera utilisé. |
| keep_open | bool | <see langword=\"true\" /> pour laisser la couche ouverte après que l'objet [Map](/psd/python-net/aspose.gis.rendering/map/) soit libéré ; sinon, <see langword=\"false\" />. |

### Method: add(map_layer) {#add_map_layer_9}


```
 add(map_layer) 
```

Ajoute une couche à la carte. Les couches sont rendues dans l'ordre d'ajout.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| map_layer | [MapLayer](/psd/python-net/aspose.gis.rendering/maplayer) | La couche à ajouter. |

### Method: render(output_path, renderer) {#render_output_path_renderer_10}


```
 render(output_path, renderer) 
```

Rend la carte dans un fichier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| output_path | string | Chemin du fichier de sortie. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Moteur de rendu à utiliser. |

### Method: render(output_path, renderer) {#render_output_path_renderer_11}


```
 render(output_path, renderer) 
```

Rend la carte dans un fichier.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| output_path | [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | Chemin du fichier de sortie. |
| renderer | [Renderer](/psd/python-net/aspose.gis.rendering/renderer) | Moteur de rendu à utiliser. |

