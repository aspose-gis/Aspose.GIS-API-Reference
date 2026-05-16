---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /it/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Classe** | **Descrizione** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | Un asse descrive una dimensione del SRS. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | Classe che contiene i parametri della formula Bursa-Wolf per trasformare a un altro datum. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | Il SRS composto unisce due SRS sottostanti, nessuno dei quali può essere composto. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Ellipsoid rappresenta un ellissoide, che approssima la Terra. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | Il SRS geocentrico è un SRS cartesiano tridimensionale con origine al centro della Terra. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | Parametri per creare un SRS geocentrico.<br/>            I parametri hanno valori predefiniti ragionevoli, quindi dovrai assegnarne solo alcuni.<br/>            Se assegni <see langword=\"null\" /> a qualsiasi parametro, verrà utilizzato un valore predefinito. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | Il datum geografico collega longitudine e latitudine a un luogo particolare sulla Terra. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | Un SRS geografico è un SRS basato su longitudine e latitudine.<br/>            Un SRS geografico può essere bidimensionale o tridimensionale.<br/>            Se il SRS geografico è tridimensionale, allora è in realtà un SRS composto da un SRS bidimensionale e un SRS verticale. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Parametri per creare un SRS geografico.<br/>            I parametri hanno valori predefiniti ragionevoli, quindi dovrai assegnarne solo alcuni.<br/>            Se assegni <see langword=\"null\" /> a qualsiasi parametro, verrà utilizzato un valore predefinito. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | Rappresenta un oggetto che può avere un codice EPSG e un nome. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | Rappresenta un identificatore - un riferimento a una descrizione esterna di un oggetto.<br/>            Se crei un SRS da WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corrisponde alla parola chiave \"AUTHORITY\". |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | Indica il metodo utilizzato per le misurazioni nel sistema di riferimento spaziale locale. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | Coordinate del SRS locale relative a qualche oggetto, non alla Terra. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | Il PrimeMeridian rappresenta un meridiano al quale la longitudine è definita pari a 0. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Il SRS proiettato è il risultato dell'applicazione di una proiezione al SRS geografico.<br/>            Un SRS proiettato può essere bidimensionale o tridimensionale.<br/>            Se il SRS proiettato è tridimensionale, allora è in realtà un SRS composto da un SRS proiettato bidimensionale e un SRS verticale unidimensionale. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Parametri per creare un SRS proiettato. Alcuni dei parametri hanno valori predefiniti.<br/>            Alcuni parametri hanno valori predefiniti ragionevoli, quindi non è necessario assegnare solo quelli.<br/>            Se assegni <see langword=\"null\" /> a tali parametri, verrà utilizzato un valore predefinito.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) e [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) non hanno valori predefiniti -<br/>            devi assegnare un valore non <see langword=\"null\" /> a queste proprietà. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | Rappresenta un metodo di proiezione con parametri, che trasforma (longitudine, latitudine) in (x, y). |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Il sistema di riferimento spaziale mappa le coordinate sui luoghi della Terra.<br/>            Esistono diversi tipi di SRS, vedi [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).<br/>            Inoltre, se il tipo di SRS è [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) o<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/), l'SRS può essere composto o singolo, vedi [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | La trasformazione del sistema di riferimento spaziale trasforma le geometrie dal sistema di riferimento spaziale di origine a quello di destinazione. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | Viene generata un'eccezione di trasformazione quando si verifica un errore durante la trasformazione di una coordinata o durante la creazione della trasformazione. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | Rappresenta l'unità di misura. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | Indica il metodo utilizzato per le misurazioni verticali. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Il SRS verticale è un SRS unidimensionale che descrive le coordinate di altezza. |
## **Enumerations**
| **Enumerazione** | **Descrizione** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | La direzione dell'asse definisce la direzione verso cui l'asse è orientato. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | Rappresenta l'ordine degli assi nel SRS geocentrico. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | Rappresenta l'ordine degli assi nel SRS geografico. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | Determina il tipo di parametro in [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/). |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | Rappresenta l'ordine degli assi nel SRS geografico. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | Rappresenta il tipo di sistema di riferimento spaziale. |
