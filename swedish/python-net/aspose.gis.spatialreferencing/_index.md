---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /sv/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Klass** | **Beskrivning** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | En axel beskriver en dimension av SRS. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | Klass som innehåller parametrar för Bursa-Wolf-formeln för att transformera till ett annat datum. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | Sammansatt SRS förenar två underliggande SRS, där ingen av dem kan vara sammansatt. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Ellipsoid representerar en ellipsoid som approximera jorden. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | Geocentrisk SRS är en tredimensionell kartesisk SRS med ursprung i jordens centrum. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | Parametrar för att skapa geocentrisk SRS.<br/>            Parametrar har rimliga standardvärden, så du behöver bara tilldela några av dem.<br/>            Om du tilldelar <see langword=\"null\" /> till någon parameter, kommer ett standardvärde att användas. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | Geografiskt datum relaterar longitud och latitud till en specifik plats på jorden. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | Ett geografiskt SRS är ett SRS som är baserat på longitud och latitud.<br/>            Ett geografiskt SRS kan vara tvådimensionellt eller tredimensionellt.<br/>            Om ett geografiskt SRS är tredimensionellt, är det i själva verket ett sammansatt SRS av ett tvådimensionellt SRS och ett vertikalt SRS. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Parametrar för att skapa geografiskt SRS.<br/>            Parametrar har rimliga standardvärden, så du behöver bara tilldela några av dem.<br/>            Om du tilldelar <see langword=\"null\" /> till någon parameter, kommer ett standardvärde att användas. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | Representerar ett objekt som kan ha EPSG-kod och namn. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | Representerar en identifierare – en referens till extern beskrivning av ett objekt.<br/>            Om du skapar ett SRS från WKT, motsvarar [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) nyckelordet \"AUTHORITY\". |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | Indikerar metod som används för mätningar i lokalt rumsligt referenssystem. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | Lokala SRS-relaterade koordinater till ett objekt, inte jorden. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | PrimeMeridian representerar en meridian där longitud definieras till 0. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Projected SRS är ett resultat av att applicera en projektion på ett geografiskt SRS.<br/>            Ett projicerat SRS kan vara tvådimensionellt eller tredimensionellt.<br/>            Om det projicerade SRS är tredimensionellt, är det i själva verket ett sammansatt SRS av ett tvådimensionellt projicerat SRS och ett endimensionellt vertikalt SRS. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Parametrar för att skapa ett projicerat SRS. Vissa parametrar har standardvärden.<br/>            Vissa parametrar har rimliga standardvärden, så du behöver inte bara tilldela dem.<br/>            Om du tilldelar <see langword="null" /> till dessa parametrar, kommer ett standardvärde att användas.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) och [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) har inga standardvärden -<br/>            du måste tilldela ett icke <see langword="null" /> värde till dessa egenskaper. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | Representerar en projektionmetod med parametrar som omvandlar (longitud, latitud) till (x, y). |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Rumsligt referenssystem kartlägger koordinater till platser på jorden.<br/>            Det finns olika typer av SRS, se [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).<br/>            Dessutom, om typen av SRS är [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) eller<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/), kan SRS vara sammansatt eller enkel, se [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | Transformation av rumsligt referenssystem omvandlar geometrier från källans rumsliga referenssystem till målens rumsliga referenssystem. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | Transformationsundantag kastas när ett fel uppstår under omvandling av en koordinat eller under skapandet av en transformation. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | Representerar en måttenhet. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | Indikerar metod som används för vertikala mätningar. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Vertikalt SRS är ett endimensionellt SRS som beskriver höjdkordinater. |
## **Enumerations**
| **Enumeration** | **Beskrivning** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | Axelriktning definierar den riktning som axeln pekar mot. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | Representerar ordning av axlar i geocentriskt SRS. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | Representerar ordning av axlar i geografiskt SRS. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | Bestämmer typ av parameter i [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/). |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | Representerar ordning av axlar i geografiskt SRS. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | Representerar typ av rumsligt referenssystem. |
