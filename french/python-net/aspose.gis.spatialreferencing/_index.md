---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /fr/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Classe** | **Description** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | Un axe décrit une dimension du SRS. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | Classe qui contient les paramètres de la formule Bursa-Wolf pour transformer vers un autre datum. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | Un SRS composé unit deux SRS sous-jacents, dont aucun ne peut être composé. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Ellipsoid représente un ellipsoïde, qui approxime la Terre. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | Le SRS géocentrique est un SRS cartésien à 3 dimensions avec une origine au centre de la Terre. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | Paramètres pour créer un SRS géocentrique.<br/>            Les paramètres ont des valeurs par défaut raisonnables, vous n'aurez donc à en assigner que quelques-uns.<br/>            Si vous assignez <see langword=\"null\" /> à un paramètre, une valeur par défaut sera utilisée. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | Le datum géographique relie la longitude et la latitude à un lieu particulier sur la Terre. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | Un SRS géographique est un SRS basé sur la longitude et la latitude.<br/>            Un SRS géographique peut être bidimensionnel ou tridimensionnel.<br/>            Si le SRS géographique est tridimensionnel, il s'agit en fait d'un SRS composé d'un SRS bidimensionnel et d'un SRS vertical. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Paramètres pour créer un SRS géographique.<br/>            Les paramètres ont des valeurs par défaut raisonnables, vous n'aurez donc à en assigner que quelques-uns.<br/>            Si vous assignez <see langword=\"null\" /> à un paramètre, une valeur par défaut sera utilisée. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | Représente un objet qui peut avoir un code EPSG et un nom. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | Représente un identifiant - une référence à la description externe d'un objet.<br/>            Si vous créez un SRS à partir de WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) correspond au mot-clé \"AUTHORITY\". |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | Indique la méthode utilisée pour les mesures dans le système de référence spatiale local. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | Coordonnées du SRS local liées à un objet, pas à la Terre. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | PrimeMeridian représente un méridien où la longitude est définie comme 0. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Le SRS projeté est le résultat de l'application d'une projection au SRS géographique.<br/>            Un SRS projeté peut être bidimensionnel ou tridimensionnel.<br/>            Si le SRS projeté est tridimensionnel, il s'agit en fait d'un SRS composé d'un SRS projeté bidimensionnel et d'un SRS vertical unidimensionnel. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Paramètres pour créer un SRS projeté. Certains paramètres ont des valeurs par défaut.<br/>            Certains paramètres ont des valeurs par défaut raisonnables, donc vous n'avez pas besoin de n'assigner que ceux‑ci.<br/>            Si vous assignez <see langword="null" /> à ces paramètres, une valeur par défaut sera utilisée.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) et [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) n'ont pas de valeurs par défaut -<br/>            vous devez assigner une valeur non <see langword="null" /> à ces propriétés. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | Représente une méthode de projection avec des paramètres, qui transforme (longitude, latitude) en (x, y). |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Le système de référence spatiale mappe les coordonnées aux emplacements sur la Terre.<br/>            Il existe différents types de SRS, voir [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).<br/>            De plus, si le type de SRS est [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) ou<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/), le SRS peut être composé ou simple, voir [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | La transformation du système de référence spatiale transforme les géométries du système de référence spatiale source vers le système de référence spatiale cible. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | Une exception de transformation est levée lorsqu'une erreur se produit lors de la transformation d'une coordonnée ou lors de la création de la transformation. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | Représente l'unité de mesure. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | Indique la méthode utilisée pour les mesures verticales. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Le SRS vertical est un SRS unidimensionnel qui décrit les coordonnées de hauteur. |
## **Enumerations**
| **Énumération** | **Description** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | La direction de l'axe définit la direction vers laquelle l'axe pointe. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | Représente l'ordre des axes dans le SRS géocentrique. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | Représente l'ordre des axes dans le SRS géographique. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | Détermine le type de paramètre dans [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/). |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | Représente l'ordre des axes dans le SRS géographique. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | Représente le type de système de référence spatiale. |
