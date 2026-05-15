---
title: "Classe GmlOptions"
type: docs
weight: 20
url: /fr/python-net/aspose.gis.formats.gml/gmloptions/
---

**Summary:** Driver-specific options for GML format.

**Module:** [aspose.gis.formats.gml](/psd/python-net/aspose.gis.formats.gml/)

**Full Name:** aspose.gis.formats.gml.GmlOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GmlOptions()](#GmlOptions__1) | Créer une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| application_namespace | string | r/w | Cela spécifie un espace de noms personnalisé à utiliser comme espace de noms de l'application pour générer le document gml. |
| close_linear_ring | bool | r/w | Détermine s'il faut fermer un [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) non fermé dans chaque géométrie. La valeur par défaut est <see langword=\"false\" />. |
| create_midpoints | bool | r/w | Détermine s'il faut ajouter un nouveau point au milieu de chaque segment de géométrie. La valeur par défaut est <see langword=\"false\" />. |
| delete_near_points | bool | r/w | Détermine s'il faut supprimer les points proches dans chaque géométrie. La valeur par défaut est <see langword=\"false\" />. |
| delete_near_points_distance | double | r/w | Détermine la distance pour [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Valeur par défaut <see langword="0" />. |
| linearization_tolerance | double | r/w | Une tolérance à utiliser pour linéariser les géométries de courbes. |
| load_schemas_from_internet | bool | r/w | Détermine si Aspose.GIS est autorisé à charger le schéma XML depuis Internet.<br/>            Si la valeur est <see langword="false" />, les schémas avec des URI absolus qui ne commencent pas par 'file://' ne seront pas chargés.<br/>            La valeur par défaut est <see langword="false" />. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) qui sera appliqué à la coordonnée M<br/>            lorsque les géométries sont ajoutées au [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ou lorsqu'elles sont lues depuis le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            La valeur par défaut est [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| nested_properties_separator | string | r/w | Obtient ou définit une chaîne utilisée pour séparer les composants des attributs imbriqués.<br/>            La valeur par défaut est "_". |
| restore_schema | bool | r/w | Détermine si Aspose.GIS est autorisé à analyser les attributs dans un fichier Gml dont le schéma XML est manquant ou ne peut pas être chargé.<br/>            Si la valeur est <see langword="true" />, le lecteur Aspose.GIS ne nécessite pas la présence d'un schéma XML.<br/>            La valeur par défaut est <see langword="false" />. |
| schema_location | string | r/w | Liste de paires d'URI séparées par des espaces. La première URI de chaque paire est l'URI de l'espace de noms, la seconde URI est un chemin vers le schéma XML de l'espace de noms.<br/>            Si la valeur est <see langword="null" />, [GmlDriver](/psd/python-net/aspose.gis.formats.gml/gmldriver/) tentera de lire schemaLocation depuis l'élément racine du document.<br/>            La valeur par défaut est <see langword="null" />. |
| simplify_segments | bool | r/w | Détermine si les points à supprimer se trouvent sur le même segment dans chaque géométrie. Valeur par défaut <see langword="false" />. |
| simplify_segments_distance | double | r/w | Détermine la distance pour [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Valeur par défaut <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Détermine si les géométries doivent être validées lorsqu'elles sont ajoutées à la couche.<br/>            Si la valeur est <see langword="true" />, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) est appelée pour chaque<br/>            géométrie lorsqu'elle est ajoutée à la couche, et si la validation échoue ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) est <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) est levée. |
| write_polygons_as_lines | bool | r/w | Détermine si la transformation d'un polygone ou multipolygone en ligne est autorisée. Valeur par défaut <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) qui sera appliqué aux coordonnées X et Y<br/>            lorsque les géométries sont ajoutées au [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ou lorsqu'elles sont lues depuis le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            La valeur par défaut est [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) qui sera appliqué à la coordonnée Z<br/>            lorsque les géométries sont ajoutées au [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ou lorsqu'elles sont lues depuis le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            La valeur par défaut est [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GmlOptions() {#GmlOptions__1}


```
 GmlOptions() 
```

Créer une nouvelle instance.

