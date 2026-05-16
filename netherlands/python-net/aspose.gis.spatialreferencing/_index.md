---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /nl/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Klasse** | **Beschrijving** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | Een as beschrijft één dimensie van SRS. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | Klasse die parameters van de Bursa-Wolf-formule bevat om naar een ander datum te transformeren. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | Compound SRS verenigt twee onderliggende SRS, waarvan geen samengesteld kan zijn. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Ellipsoid vertegenwoordigt een ellipsoïde, die de aarde benadert. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | Geocentrische SRS is een 3-dimensionale cartesiaanse SRS met oorsprong in het middelpunt van de aarde. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | Parameters om een geocentrische SRS te maken.<br/>            Parameters hebben redelijke standaardwaarden, dus u hoeft slechts enkele toe te wijzen.<br/>            Als u <see langword="null" /> toewijst aan een parameter, wordt een standaardwaarde gebruikt. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | Geografisch datum koppelt lengte- en breedtegraad aan een specifieke plaats op aarde. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | Een Geografische SRS is een SRS die gebaseerd is op lengte- en breedtegraad.<br/>            Een Geografische SRS kan twee- of driedimensionaal zijn.<br/>            Als een geografische SRS driedimensionaal is, dan is het eigenlijk een samengestelde SRS van een tweedimensionale SRS en een verticale SRS. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Parameters om een geografische SRS te maken.<br/>            Parameters hebben redelijke standaardwaarden, dus u hoeft slechts enkele toe te wijzen.<br/>            Als u <see langword="null" /> toewijst aan een parameter, wordt een standaardwaarde gebruikt. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | Vertegenwoordigt een object dat een EPSG-code en naam kan hebben. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | Vertegenwoordigt een identifier - een verwijzing naar een externe beschrijving van een object.<br/>            Als u een SRS maakt vanuit WKT, correspondeert [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) met het sleutelwoord "AUTHORITY". |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | Geeft de methode aan die wordt gebruikt voor metingen in het lokale ruimtelijk referentiesysteem. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | Lokale SRS-gerelateerde coördinaten ten opzichte van een object, niet van de aarde. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | PrimeMeridian vertegenwoordigt een meridiaan waarbij de lengtegraad is gedefinieerd als 0. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Geprojecteerde SRS is het resultaat van het toepassen van een projectie op een geografisch SRS.<br/>            Een geprojecteerde SRS kan tweedimensionaal of driedimensionaal zijn.<br/>            Als een geprojecteerde SRS driedimensionaal is, dan is het eigenlijk een samengesteld SRS van een tweedimensionale geprojecteerde SRS en een eendimensionale verticale SRS. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Parameters om een geprojecteerde SRS te maken. Sommige parameters hebben standaardwaarden.<br/>            Sommige parameters hebben redelijke standaardwaarden, zodat u ze niet alleen hoeft toe te wijzen.<br/>            Als u <see langword=\"null\" /> toewijst aan die parameters, wordt een standaardwaarde gebruikt.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) en [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) hebben geen standaardwaarden -<br/>            u moet een niet-<see langword=\"null\" /> waarde toewijzen aan deze eigenschappen. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | Stelt een projectiemethode met parameters voor, die (longitude, latitude) naar (x, y) transformeert. |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Het ruimtelijk referentiesysteem brengt coördinaten in kaart naar locaties op de aarde.<br/>            Er zijn verschillende typen SRS, zie [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).<br/>            Bovendien, als het type SRS [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) of<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) is, kan SRS samengesteld of enkel zijn, zie [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | De transformatie van het ruimtelijk referentiesysteem transformeert geometrieën van het bron-ruimtelijk referentiesysteem naar het doel-ruimtelijk referentiesysteem. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | Een transformatie-exceptie wordt gegooid wanneer er een fout optreedt tijdens de transformatie van een coördinaat of tijdens het maken van een transformatie. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | Stelt een meeteenheid voor. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | Geeft de methode aan die wordt gebruikt voor verticale metingen. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Verticale SRS is een eendimensionaal SRS dat hoogtacoördinaten beschrijft. |
## **Enumerations**
| **Enumeratie** | **Beschrijving** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | De asrichting definieert de richting waarin de as wijst. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | Stelt de volgorde van assen in een geocentrisch SRS voor. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | Stelt de volgorde van assen in een geografisch SRS voor. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | Bepaalt het type parameter in [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/). |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | Stelt de volgorde van assen in een geografisch SRS voor. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | Stelt het type van een ruimtelijk referentiesysteem voor. |
