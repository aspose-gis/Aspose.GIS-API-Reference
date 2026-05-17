---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /es/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Clase** | **Descripción** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | Un eje describe una dimensión del SRS. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | Clase que contiene los parámetros de la fórmula Bursa-Wolf para transformar a otro datum. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | Un SRS compuesto une dos SRS subyacentes, ninguno de los cuales puede ser compuesto. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Ellipsoid representa un elipsoide, que aproxima la tierra. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | Geocentric SRS es un SRS cartesiano tridimensional con origen en el centro de la tierra. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | Parámetros para crear un geocentric SRS.<br/>            Los parámetros tienen valores predeterminados razonables, por lo que solo tendrás que asignar algunos de ellos.<br/>            Si asignas <see langword=\"null\" /> a cualquier parámetro, se usará un valor predeterminado. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | El datum geográfico relaciona la longitud y latitud con un lugar particular en la tierra. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | Un Geographic SRS es un SRS que se basa en longitud y latitud.<br/>            Un Geographic SRS puede ser bidimensional o tridimensional.<br/>            Si el Geographic SRS es tridimensional, entonces en realidad es un SRS compuesto de un SRS bidimensional y un SRS vertical. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Parámetros para crear un geographic SRS.<br/>            Los parámetros tienen valores predeterminados razonables, por lo que solo tendrás que asignar algunos de ellos.<br/>            Si asignas <see langword=\"null\" /> a cualquier parámetro, se usará un valor predeterminado. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | Representa un objeto que puede tener un código EPSG y un nombre. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | Representa un identificador - una referencia a la descripción externa de un objeto.<br/>            Si creas un SRS a partir de WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) corresponde a la palabra clave \"AUTHORITY\". |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | Indica el método utilizado para mediciones en el sistema de referencia espacial local. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | Coordenadas del SRS local relacionadas con algún objeto, no con la Tierra. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | PrimeMeridian representa un meridiano en el que la longitud se define como 0. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Projected SRS es el resultado de aplicar una proyección al SRS geográfico.<br/>            Un SRS proyectado puede ser bidimensional o tridimensional.<br/>            Si el SRS proyectado es tridimensional, entonces en realidad es un SRS compuesto de un SRS proyectado bidimensional y un SRS vertical unidimensional. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Parámetros para crear un SRS proyectado. Algunos de los parámetros tienen valores predeterminados.<br/>            Algunos parámetros tienen valores predeterminados razonables, por lo que no tienes que asignar solo esos.<br/>            Si asignas <see langword="null" /> a esos parámetros, se utilizará un valor predeterminado.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) y [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) no tienen valores predeterminados -<br/>            debes asignar algún valor no <see langword="null" /> a estas propiedades. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | Representa un método de proyección con parámetros, que transforma (longitud, latitud) a (x, y). |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | El sistema de referencia espacial asigna coordenadas a lugares en la Tierra.<br/>            Existen diferentes tipos de SRS, consulte [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).<br/>            Además, si el tipo de SRS es [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) o<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/), el SRS puede ser compuesto o simple, consulte [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | La transformación del sistema de referencia espacial transforma geometrías del sistema de referencia espacial de origen al sistema de referencia espacial de destino. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | Se lanza una excepción de transformación cuando ocurre un error durante la transformación de una coordenada o durante la creación de la transformación. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | Representa la unidad de medida. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | Indica el método utilizado para mediciones verticales. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Vertical SRS es un SRS unidimensional que describe coordenadas de altura. |
## **Enumerations**
| **Enumeración** | **Descripción** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | La dirección del eje define la dirección hacia la que apunta el eje. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | Representa el orden de los ejes en el SRS geocéntrico. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | Representa el orden de los ejes en el SRS geográfico. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | Determina el tipo de parámetro en [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/). |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | Representa el orden de los ejes en el SRS geográfico. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | Representa el tipo de sistema de referencia espacial. |
