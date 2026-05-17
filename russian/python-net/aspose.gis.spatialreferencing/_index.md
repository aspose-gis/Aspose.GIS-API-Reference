---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /ru/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Класс** | **Описание** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | Ось описывает одно измерение SRS. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | Класс, содержащий параметры формулы Бурса-Вольфа для преобразования к другой датуме. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | Составной SRS объединяет два базовых SRS, ни один из которых не может быть составным. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Эллипсоид представляет собой эллипсоид, который приближенно описывает форму Земли. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | Геоцентрический SRS — это трёхмерный декартовый SRS с началом координат в центре Земли. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | Параметры для создания геоцентрического SRS.<br/>            Параметры имеют разумные значения по умолчанию, поэтому вам понадобится задать только некоторые из них.<br/>            Если вы присвоите <see langword=\"null\" /> любому параметру, будет использовано значение по умолчанию. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | Географический датум связывает долготу и широту с конкретным местом на Земле. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | Географический SRS — это SRS, основанный на долготе и широте.<br/>            Географический SRS может быть двумерным или трёхмерным.<br/>            Если географический SRS является трёхмерным, то он фактически представляет собой составной SRS, состоящий из двумерного SRS и вертикального SRS. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Параметры для создания географического SRS.<br/>            Параметры имеют разумные значения по умолчанию, поэтому вам понадобится задать только некоторые из них.<br/>            Если вы присвоите <see langword=\"null\" /> любому параметру, будет использовано значение по умолчанию. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | Представляет объект, который может иметь код EPSG и название. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | Представляет идентификатор — ссылку на внешнее описание объекта.<br/>            Если вы создаёте SRS из WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) соответствует ключевому слову \"AUTHORITY\". |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | Указывает метод, используемый для измерений в локальной системе пространственных координат. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | Локальная SRS относится к координатам некоторого объекта, а не к Земле. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | PrimeMeridian представляет меридиан, на котором долгота определяется как 0. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Projected SRS является результатом применения проекции к географической SRS.<br/>            Проецированная SRS может быть двумерной или трехмерной.<br/>            Если проецированная SRS трехмерна, то она фактически представляет собой составную SRS, состоящую из двумерной проецированной SRS и одномерной вертикальной SRS. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Параметры для создания проецированной SRS. Некоторые параметры имеют значения по умолчанию.<br/>            Некоторые параметры имеют разумные значения по умолчанию, поэтому вам не нужно присваивать только их.<br/>            Если вы присваиваете <see langword=\"null\" /> этим параметрам, будет использовано значение по умолчанию.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) и [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) не имеют значений по умолчанию -<br/>            вам необходимо присвоить этим свойствам некоторое ненулевое значение <see langword=\"null\" />. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | Представляет метод проекции с параметрами, который преобразует (долготу, широту) в (x, y). |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Система пространственных ссылок отображает координаты в места на Земле.<br/>            Существует несколько типов SRS, см. [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).<br/>            Более того, если тип SRS — [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) или<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/), SRS может быть составным или одиночным, см. [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | Преобразование системы пространственных ссылок преобразует геометрии из исходной системы пространственных ссылок в целевую систему пространственных ссылок. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | Исключение трансформации выбрасывается, когда происходит ошибка во время преобразования координаты или создания трансформации. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | Представляет единицу измерения. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | Указывает метод, используемый для вертикальных измерений. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Вертикальная SRS — это одномерная SRS, описывающая координаты высоты. |
## **Enumerations**
| **Перечисление** | **Описание** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | Направление оси определяет направление, в котором указывает ось. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | Представляет порядок осей в геоцентрической SRS. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | Представляет порядок осей в географической SRS. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | Определяет тип параметра в [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/). |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | Представляет порядок осей в географической SRS. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | Представляет тип системы пространственных ссылок. |
