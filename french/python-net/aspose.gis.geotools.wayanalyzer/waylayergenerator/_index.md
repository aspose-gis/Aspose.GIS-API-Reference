---
title: "Classe WayLayerGenerator"
type: docs
weight: 10
url: /fr/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/
---

**Summary:** Way layers generator

**Module:** [aspose.gis.geotools.wayanalyzer](/psd/python-net/aspose.gis.geotools.wayanalyzer/)

**Full Name:** aspose.gis.geotools.wayanalyzer.WayLayerGenerator

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [WayLayerGenerator(options)](#WayLayerGenerator_options_1) | Créer une instance de [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/) |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [add_block(x, y, size_x, size_y, velocity)](#add_block_x_y_size_x_size_y_velocity_1) | Ajouter le bloc à la cellule |
| [add_road(start_point, end_point, velocity)](#add_road_start_point_end_point_velocity_2) | Ajouter la route à la cellule |
| [find_the_way(start_point, goal_point, radius)](#find_the_way_start_point_goal_point_radius_3) | Trouver le chemin du point de départ à l'objectif |


### Constructor: WayLayerGenerator(options) {#WayLayerGenerator_options_1}


```
 WayLayerGenerator(options) 
```

Créer une instance de [WayLayerGenerator](/psd/python-net/aspose.gis.geotools.wayanalyzer/waylayergenerator/)

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| options | [WayOptions](/psd/python-net/aspose.gis.geotools.wayanalyzer/wayoptions) | les options du générateur. |

### Method: add_block(x, y, size_x, size_y, velocity) {#add_block_x_y_size_x_size_y_velocity_1}


```
 add_block(x, y, size_x, size_y, velocity) 
```

Ajouter le bloc à la cellule

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| x | int | le x du bloc |
| y | int | le y du bloc |
| size_x | int | la sizeX du bloc |
| size_y | int | la sizeY du bloc |
| vitesse | double | la vitesse du bloc |

### Method: add_road(start_point, end_point, velocity) {#add_road_start_point_end_point_velocity_2}


```
 add_road(start_point, end_point, velocity) 
```

Ajouter la route à la cellule

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | le point de départ. |
| end_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | le point d'arrivée. |
| vitesse | double | la vitesse. |

### Method: find_the_way(start_point, goal_point, radius) {#find_the_way_start_point_goal_point_radius_3}


```
 find_the_way(start_point, goal_point, radius) 
```

Trouver le chemin du point de départ à l'objectif

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| start_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | le Point de départ |
| goal_point | [Point](/psd/python-net/aspose.gis.geometries/point/) | le Point d'objectif |
| rayon | double | le rayon à rechercher |

**Returns**

| Type | Description |
| :- | :- |
| [LineString](/psd/python-net/aspose.gis.geometries/linestring/) | Le Chemin Trouvé. |


