---
title: "aspose.gis.spatialreferencing"
type: docs
weight: 790
url: /id/python-net/aspose.gis.spatialreferencing/
---




## **Classes**
| **Kelas** | **Deskripsi** |
| :- | :- |
| [Axis](/psd/python-net/aspose.gis.spatialreferencing/axis/) | Sebuah sumbu menggambarkan satu dimensi dari SRS. |
| [BursaWolfParameters](/psd/python-net/aspose.gis.spatialreferencing/bursawolfparameters/) | Kelas yang berisi parameter formula Bursa-Wolf untuk mentransformasi ke datum lain. |
| [CompoundSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/compoundspatialreferencesystem/) | SRS gabungan menggabungkan dua SRS dasar, yang tidak dapat menjadi gabungan. |
| [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid/) | Ellipsoid mewakili sebuah ellipsoid, yang mendekati bentuk bumi. |
| [GeocentricSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystem/) | SRS geosentrik adalah SRS kartesian tiga dimensi dengan asal di pusat bumi. |
| [GeocentricSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geocentricspatialreferencesystemparameters/) | Parameter untuk membuat SRS geosentrik.<br/>            Parameter memiliki nilai default yang wajar, sehingga Anda hanya perlu menetapkan sebagian saja.<br/>            Jika Anda menetapkan <see langword=\"null\" /> ke parameter apa pun, nilai default akan digunakan. |
| [GeographicDatum](/psd/python-net/aspose.gis.spatialreferencing/geographicdatum/) | Datum geografis menghubungkan bujur dan lintang ke tempat tertentu di bumi. |
| [GeographicSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystem/) | SRS Geografis adalah SRS yang didasarkan pada bujur dan lintang.<br/>            SRS Geografis dapat berupa dua dimensi atau tiga dimensi.<br/>            Jika SRS geografis tiga dimensi, maka sebenarnya itu adalah SRS gabungan dari SRS dua dimensi dan SRS vertikal. |
| [GeographicSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/geographicspatialreferencesystemparameters/) | Parameter untuk membuat SRS geografis.<br/>            Parameter memiliki nilai default yang wajar, sehingga Anda hanya perlu menetapkan sebagian saja.<br/>            Jika Anda menetapkan <see langword=\"null\" /> ke parameter apa pun, nilai default akan digunakan. |
| [IdentifiableObject](/psd/python-net/aspose.gis.spatialreferencing/identifiableobject/) | Mewakili objek yang mungkin memiliki kode dan nama EPSG. |
| [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) | Mewakili sebuah identifier - referensi ke deskripsi eksternal dari sebuah objek.<br/>            Jika Anda membuat SRS dari WKT, [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier/) sesuai dengan kata kunci \"AUTHORITY\". |
| [LocalDatum](/psd/python-net/aspose.gis.spatialreferencing/localdatum/) | Menunjukkan metode yang digunakan untuk pengukuran dalam sistem referensi spasial lokal. |
| [LocalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/localspatialreferencesystem/) | Koordinat SRS lokal terkait dengan suatu objek, bukan bumi. |
| [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian/) | PrimeMeridian mewakili meridian di mana bujur didefinisikan sebagai 0. |
| [ProjectedSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystem/) | Projected SRS adalah hasil penerapan proyeksi pada geographic SRS.<br/>            Projected SRS dapat berupa dua dimensi atau tiga dimensi.<br/>            Jika projected SRS tiga dimensi, maka sebenarnya itu adalah compound SRS dari dua dimensi projected SRS dan satu dimensi vertical SRS. |
| [ProjectedSpatialReferenceSystemParameters](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) | Parameter untuk membuat projected SRS. Beberapa parameter memiliki nilai default.<br/>            Beberapa parameter memiliki nilai default yang wajar, sehingga Anda tidak perlu hanya menetapkannya.<br/>            Jika Anda menetapkan <see langword="null" /> ke parameter tersebut, nilai default akan digunakan.<br/>            [ProjectedSpatialReferenceSystemParameters.projection_method_name](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) dan [ProjectedSpatialReferenceSystemParameters.base](/psd/python-net/aspose.gis.spatialreferencing/projectedspatialreferencesystemparameters/) tidak memiliki nilai default -<br/>            Anda harus menetapkan nilai non <see langword="null" /> untuk properti ini. |
| [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/) | Mewakili metode proyeksi dengan parameter, yang mengubah (longitude, latitude) menjadi (x, y). |
| [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | Sistem referensi spasial memetakan koordinat ke tempat di Bumi.<br/>            Ada berbagai jenis SRS, lihat [SpatialReferenceSystem.type](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/).<br/>            Lebih lagi, jika tipe SRS adalah [SpatialReferenceSystemType.GEOGRAPHIC](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) atau<br/>            [SpatialReferenceSystemType.PROJECTED](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/), SRS dapat berupa gabungan atau tunggal, lihat [SpatialReferenceSystem.is_compound](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/). |
| [SpatialReferenceSystemTransformation](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtransformation/) | Transformasi sistem referensi spasial mengubah geometri dari sistem referensi spasial sumber ke sistem referensi spasial target. |
| [TransformationException](/psd/python-net/aspose.gis.spatialreferencing/transformationexception/) | Pengecualian transformasi dilemparkan ketika terjadi kesalahan selama transformasi koordinat atau selama pembuatan transformasi. |
| [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit/) | Mewakili satuan pengukuran. |
| [VerticalDatum](/psd/python-net/aspose.gis.spatialreferencing/verticaldatum/) | Menunjukkan metode yang digunakan untuk pengukuran vertikal. |
| [VerticalSpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/verticalspatialreferencesystem/) | Vertical SRS adalah SRS satu dimensi yang menggambarkan koordinat ketinggian. |
## **Enumerations**
| **Enumerasi** | **Deskripsi** |
| :- | :- |
| [AxisDirection](/psd/python-net/aspose.gis.spatialreferencing/axisdirection/) | Arah sumbu menentukan arah tempat sumbu mengarah. |
| [GeocentricAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geocentricaxisesorder/) | Mewakili urutan sumbu dalam geocentric SRS. |
| [GeographicAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/geographicaxisesorder/) | Mewakili urutan sumbu dalam geographic SRS. |
| [ParameterType](/psd/python-net/aspose.gis.spatialreferencing/parametertype/) | Menentukan tipe parameter dalam [Projection](/psd/python-net/aspose.gis.spatialreferencing/projection/). |
| [ProjectedAxisesOrder](/psd/python-net/aspose.gis.spatialreferencing/projectedaxisesorder/) | Mewakili urutan sumbu dalam geographic SRS. |
| [SpatialReferenceSystemType](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystemtype/) | Mewakili tipe sistem referensi spasial. |
