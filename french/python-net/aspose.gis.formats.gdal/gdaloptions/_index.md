---
title: "Classe GdalOptions"
type: docs
weight: 20
url: /fr/python-net/aspose.gis.formats.gdal/gdaloptions/
---

**Summary:** Driver-specific options for GDAL format.

**Module:** [aspose.gis.formats.gdal](/psd/python-net/aspose.gis.formats.gdal/)

**Full Name:** aspose.gis.formats.gdal.GdalOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [GdalOptions(temp_directory)](#GdalOptions_temp_directory_1) | Crée une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Détermine s'il faut fermer un [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) non fermé dans chaque géométrie. La valeur par défaut est <see langword=\"false\" />. |
| create_midpoints | bool | r/w | Détermine s'il faut ajouter un nouveau point au milieu de chaque segment de géométrie. La valeur par défaut est <see langword=\"false\" />. |
| delete_near_points | bool | r/w | Détermine s'il faut supprimer les points proches dans chaque géométrie. La valeur par défaut est <see langword=\"false\" />. |
| delete_near_points_distance | double | r/w | Détermine la distance pour [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Valeur par défaut <see langword="0" />. |
| file_name | string | r/w | Nom de l'application à démarrer |
| linearization_tolerance | double | r/w | Une tolérance à utiliser pour linéariser les géométries de courbes. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) qui sera appliqué à la coordonnée M<br/>            lorsque les géométries sont ajoutées au [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ou lorsqu'elles sont lues depuis le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            La valeur par défaut est [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| path_to_temp_file | string | r | Chemin vers les fichiers temporaires. |
| simplify_segments | bool | r/w | Détermine si les points à supprimer se trouvent sur le même segment dans chaque géométrie. Valeur par défaut <see langword="false" />. |
| simplify_segments_distance | double | r/w | Détermine la distance pour [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Valeur par défaut <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Détermine si les géométries doivent être validées lorsqu'elles sont ajoutées à la couche.<br/>            Si la valeur est <see langword="true" />, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) est appelée pour chaque<br/>            géométrie lorsqu'elle est ajoutée à la couche, et si la validation échoue ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) est <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) est levée. |
| write_polygons_as_lines | bool | r/w | Détermine si la transformation d'un polygone ou multipolygone en ligne est autorisée. Valeur par défaut <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) qui sera appliqué aux coordonnées X et Y<br/>            lorsque les géométries sont ajoutées au [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ou lorsqu'elles sont lues depuis le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            La valeur par défaut est [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) qui sera appliqué à la coordonnée Z<br/>            lorsque les géométries sont ajoutées au [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ou lorsqu'elles sont lues depuis le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            La valeur par défaut est [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |


### Constructor: GdalOptions(temp_directory) {#GdalOptions_temp_directory_1}


```
 GdalOptions(temp_directory) 
```

Crée une nouvelle instance.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| temp_directory | string | Chemin vers les fichiers temporaires. Dossier temporaire de l'utilisateur par défaut. |

