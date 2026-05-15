---
title: "Classe FileGdbOptions"
type: docs
weight: 30
url: /fr/python-net/aspose.gis.formats.filegdb/filegdboptions/
---

**Summary:** Driver-specific options for FileGDB format.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbOptions

**Inheritance:** DriverOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbOptions()](#FileGdbOptions__1) | Créer une nouvelle instance. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| close_linear_ring | bool | r/w | Détermine s'il faut fermer un [GeometryType.LINEAR_RING](/psd/python-net/aspose.gis.geometries/geometrytype/) non fermé dans chaque géométrie. La valeur par défaut est <see langword=\"false\" />. |
| coordinate_precision_grid | [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | r/w | Une grille de précision de coordonnées à utiliser dans la nouvelle couche. |
| create_midpoints | bool | r/w | Détermine s'il faut ajouter un nouveau point au milieu de chaque segment de géométrie. La valeur par défaut est <see langword=\"false\" />. |
| delete_near_points | bool | r/w | Détermine s'il faut supprimer les points proches dans chaque géométrie. La valeur par défaut est <see langword=\"false\" />. |
| delete_near_points_distance | double | r/w | Détermine la distance pour [DriverOptions.delete_near_points](/psd/python-net/aspose.gis/driveroptions/). Valeur par défaut <see langword="0" />. |
| ensure_valid_coordinates_range | bool | r/w | Indique si les coordonnées doivent être dans une plage valide. |
| expected_geometry_type | Nullable<Aspose.Gis.Geometries.GeometryType> | r/w | Type de géométrie attendu pour la couche. Si cette option est définie, nous n'autorisons l'ajout que des géométries de ce type. |
| geometry_field_name | string | r/w | Nom du champ géométrie. |
| has_m | bool | r/w | Les géométries de la couche peuvent avoir une coordonnée 'm'. Par défaut, c'est vrai. |
| has_z | bool | r/w | Les géométries de la couche peuvent avoir une coordonnée 'z'. Par défaut, c'est vrai. |
| linearization_tolerance | double | r/w | Une tolérance à utiliser pour linéariser les géométries de courbes. |
| m_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) qui sera appliqué à la coordonnée M<br/>            lorsque les géométries sont ajoutées au [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ou lorsqu'elles sont lues depuis le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            La valeur par défaut est [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| m_tolerance | Nullable<double> | r/w | Tolérance d'accrochage M. |
| object_id_field_name | string | r/w | Nom du champ d'ID d'objet. |
| simplify_segments | bool | r/w | Détermine si les points à supprimer se trouvent sur le même segment dans chaque géométrie. Valeur par défaut <see langword="false" />. |
| simplify_segments_distance | double | r/w | Détermine la distance pour [DriverOptions.simplify_segments](/psd/python-net/aspose.gis/driveroptions/). Valeur par défaut <see langword="0" />. |
| validate_geometries_on_write | bool | r/w | Détermine si les géométries doivent être validées lorsqu'elles sont ajoutées à la couche.<br/>            Si la valeur est <see langword="true" />, [Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) est appelée pour chaque<br/>            géométrie lorsqu'elle est ajoutée à la couche, et si la validation échoue ([Geometry.is_valid](/psd/python-net/aspose.gis.geometries/geometry/) est <see langword="false" />), [GisException](/psd/python-net/aspose.gis/gisexception/) est levée. |
| write_polygons_as_lines | bool | r/w | Détermine si la transformation d'un polygone ou multipolygone en ligne est autorisée. Valeur par défaut <see langword="false" />. |
| xy_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) qui sera appliqué aux coordonnées X et Y<br/>            lorsque les géométries sont ajoutées au [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ou lorsqu'elles sont lues depuis le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            La valeur par défaut est [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| xy_tolerance | Nullable<double> | r/w | Tolérance d'accrochage X et Y. |
| z_precision_model | [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel) | r/w | Un [PrecisionModel](/psd/python-net/aspose.gis/precisionmodel/) qui sera appliqué à la coordonnée Z<br/>            lorsque les géométries sont ajoutées au [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/) ou lorsqu'elles sont lues depuis le [VectorLayer](/psd/python-net/aspose.gis/vectorlayer/).<br/>            La valeur par défaut est [PrecisionModel.exact](/psd/python-net/aspose.gis/precisionmodel/). |
| z_tolerance | Nullable<double> | r/w | Tolérance d'accrochage Z. |


### Constructor: FileGdbOptions() {#FileGdbOptions__1}


```
 FileGdbOptions() 
```

Créer une nouvelle instance.

