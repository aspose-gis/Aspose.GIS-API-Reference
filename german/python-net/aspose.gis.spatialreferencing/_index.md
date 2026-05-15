---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /de/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Klasse** | **Beschreibung** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | Eine Achse beschreibt eine Dimension des SRS. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | Klasse, die Parameter der Bursa‑Wolf‑Formel enthält, um zu einem anderen Datum zu transformieren. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | Ein zusammengesetztes SRS vereint zwei zugrunde liegende SRS, von denen keines zusammengesetzt sein kann. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Ellipsoid stellt ein Ellipsoid dar, das die Erde annähert. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | Geozentrisches SRS ist ein dreidimensionales kartesisches SRS mit Ursprung im Erdmittelpunkt. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | Parameter zum Erstellen eines geozentrischen SRS.<br/>            Parameter haben vernünftige Standardwerte, sodass Sie nur einige davon zuweisen müssen.<br/>            Wenn Sie <see langword=\"null\" /> einem beliebigen Parameter zuweisen, wird ein Standardwert verwendet. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | Geografisches Datum verknüpft Längen- und Breitengrad mit einem bestimmten Ort auf der Erde. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | Ein geografisches SRS ist ein SRS, das auf Längen- und Breitengrad basiert.<br/>            Ein geografisches SRS kann zweidimensional oder dreidimensional sein.<br/>            Wenn ein geografisches SRS dreidimensional ist, ist es tatsächlich ein zusammengesetztes SRS aus einem zweidimensionalen SRS und einem vertikalen SRS. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Parameter zum Erstellen eines geografischen SRS.<br/>            Parameter haben vernünftige Standardwerte, sodass Sie nur einige davon zuweisen müssen.<br/>            Wenn Sie <see langword=\"null\" /> einem beliebigen Parameter zuweisen, wird ein Standardwert verwendet. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | Stellt ein Objekt dar, das einen EPSG-Code und einen Namen haben kann. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | Stellt einen Bezeichner dar – eine Referenz zur externen Beschreibung eines Objekts.<br/>            Wenn Sie ein SRS aus WKT erstellen, entspricht [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) dem Schlüsselwort \"AUTHORITY\". |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | Gibt die Methode an, die für Messungen im lokalen räumlichen Referenzsystem verwendet wird. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | Lokale SRS-bezogene Koordinaten zu einem Objekt, nicht zur Erde. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | Der PrimeMeridian stellt einen Meridian dar, bei dem die Länge als 0 definiert ist. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Ein projiziertes SRS ist das Ergebnis der Anwendung einer Projektion auf ein geografisches SRS.<br/>            Ein projiziertes SRS kann zweidimensional oder dreidimensional sein.<br/>            Wenn ein projiziertes SRS dreidimensional ist, handelt es sich tatsächlich um ein zusammengesetztes SRS aus einem zweidimensionalen projizierten SRS und einem eindimensionalen vertikalen SRS. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Parameter zum Erstellen eines projizierten SRS. Einige der Parameter haben Vorgabewerte.<br/>            Einige Parameter haben sinnvolle Vorgabewerte, sodass Sie nicht ausschließlich diese zuweisen müssen.<br/>            Wenn Sie <see langword=\"null\" /> diesen Parametern zuweisen, wird ein Standardwert verwendet.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) und [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) haben keine Vorgaben -<br/>            Sie müssen diesen Eigenschaften einen nicht <see langword=\"null\" /> Wert zuweisen. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | Stellt eine Projektionsmethode mit Parametern dar, die (Länge, Breite) in (x, y) umwandelt. |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Ein räumliches Referenzsystem ordnet Koordinaten Orten auf der Erde zu.<br/>            Es gibt verschiedene Arten von SRS, siehe [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).<br/>            Außerdem kann, wenn der Typ des SRS [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) oder<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) ist, das SRS zusammengesetzt oder einfach sein, siehe [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | Eine räumliche Referenzsystemtransformation wandelt Geometrien vom Quell‑Referenzsystem in das Ziel‑Referenzsystem um. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | Eine Transformationsausnahme wird ausgelöst, wenn ein Fehler bei der Koordinatentransformation oder bei der Erstellung der Transformation auftritt. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | Stellt die Maßeinheit dar. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | Gibt die für vertikale Messungen verwendete Methode an. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Ein vertikales SRS ist ein eindimensionales SRS, das Höhenkoordinaten beschreibt. |
## **Enumerations**
| **Aufzählung** | **Beschreibung** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | Die Achsenrichtung definiert die Richtung, in die die Achse zeigt. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | Stellt die Reihenfolge der Achsen im geozentrischen SRS dar. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | Stellt die Reihenfolge der Achsen im geografischen SRS dar. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | Bestimmt den Parametertyp in [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/). |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | Stellt die Reihenfolge der Achsen im geografischen SRS dar. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | Stellt den Typ des räumlichen Referenzsystems dar. |
