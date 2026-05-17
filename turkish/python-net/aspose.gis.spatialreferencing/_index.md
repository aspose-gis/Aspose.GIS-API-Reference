---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /tr/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Class** | **Description** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | Bir eksen, SRS'nin bir boyutunu tanımlar. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | Başka bir datum'a dönüştürmek için Bursa-Wolf formülünün parametrelerini içeren sınıf. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | Bileşik SRS, iki temel SRS'yi birleştirir; bunların hiçbiri bileşik olamaz. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Elipsoit, dünyayı yaklaşık olarak temsil eden bir elipsoidi temsil eder. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | Geocentric SRS, dünya merkezinde bir orijine sahip 3 boyutlu Kartezyen SRS'dir. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | Geocentric SRS oluşturmak için parametreler.<br/>            Parametrelerin makul varsayılanları vardır, bu yüzden yalnızca bir kısmını atamanız gerekir.<br/>            Herhangi bir parametreye <see langword="null" /> atarsanız, varsayılan bir değer kullanılacaktır. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | Coğrafi datum, uzunluk ve enlemi dünya üzerindeki belirli bir konuma bağlar. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | Coğrafi SRS, uzunluk ve enlem temelli bir SRS'dir.<br/>            Coğrafi SRS iki boyutlu veya üç boyutlu olabilir.<br/>            Coğrafi SRS üç boyutlu ise, aslında iki boyutlu SRS ve dikey SRS'nin bir bileşik SRS'sidir. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Coğrafi SRS oluşturmak için parametreler.<br/>            Parametrelerin makul varsayılanları vardır, bu yüzden yalnızca bir kısmını atamanız gerekir.<br/>            Herhangi bir parametreye <see langword="null" /> atarsanız, varsayılan bir değer kullanılacaktır. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | EPSG kodu ve adı olabilecek bir nesneyi temsil eder. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | Bir tanımlayıcıyı temsil eder - bir nesnenin dış tanımına referans.<br/>            WKT'den bir SRS oluşturursanız, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) "AUTHORITY" anahtar kelimesine karşılık gelir. |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | Yerel uzamsal referans sisteminde ölçümler için kullanılan yöntemi gösterir. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | Yerel SRS, bazı nesneye ait koordinatları, dünya değil. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | PrimeMeridian, uzunluğun 0 olarak tanımlandığı meridyeni temsil eder. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Projected SRS, coğrafi SRS'ye bir projeksiyon uygulanmasının sonucudur.<br/>            Projeksiyonlu bir SRS iki boyutlu veya üç boyutlu olabilir.<br/>            Eğer projeksiyonlu SRS üç boyutluysa, o zaman aslında iki boyutlu projeksiyonlu SRS ve bir boyutlu dikey SRS'in birleşik bir SRS'idir. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Projeksiyonlu SRS oluşturmak için parametreler. Bazı parametrelerin varsayılanları vardır.<br/>            Bazı parametrelerin makul varsayılanları vardır, bu yüzden yalnızca onlara atama yapmanız gerekmez.<br/>            Bu parametrelere <see langword=\"null\" /> atarsanız, varsayılan bir değer kullanılacaktır.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) ve [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) varsayılan değere sahip değildir -<br/>            bu özelliklere null olmayan bir değer atamanız gerekir. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | Koordinatları (boylam, enlem) (x, y)'ye dönüştüren parametreli bir projeksiyon yöntemini temsil eder. |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Uzamsal referans sistemi, koordinatları Dünya üzerindeki yerlere eşler.<br/>            Farklı SRS türleri vardır, bakınız [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).<br/>            Ayrıca, SRS türü [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) veya<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) ise, SRS birleşik veya tek olabilir, bakınız [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | Uzamsal referans sistemi dönüşümü, geometrileri kaynak uzamsal referans sisteminden hedef uzamsal referans sistemine dönüştürür. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | Dönüşüm sırasında koordinatın dönüştürülmesi veya dönüşüm oluşturulması sırasında bir hata oluştuğunda dönüşüm istisnası fırlatılır. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | Ölçüm birimini temsil eder. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | Dikey ölçümler için kullanılan yöntemi gösterir. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Dikey SRS, yükseklik koordinatlarını tanımlayan tek boyutlu bir SRS'dir. |
## **Enumerations**
| **Enumeration** | **Description** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | Eksen yönü, eksenin işaret ettiği yönü tanımlar. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | Geosentrik SRS'deki eksenlerin sırasını temsil eder. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | Coğrafi SRS'deki eksenlerin sırasını temsil eder. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) içindeki parametrenin türünü belirler. |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | Coğrafi SRS'deki eksenlerin sırasını temsil eder. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | Uzamsal referans sisteminin türünü temsil eder. |
