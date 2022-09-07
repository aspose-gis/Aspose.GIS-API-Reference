---
title: SetValues
second_title: Aspose.GIS for .NET API Referansı
description: Tüm öznitelikler için yeni değerler ayarlar. Ayrıca kullanmayı düşününCopyValuesaspose.gis/feature/copyvalues tek bir çağrıda ayar değerlerini düzene sokma yöntemi.
type: docs
weight: 120
url: /tr/net/aspose.gis/feature/setvalues/
---
## Feature.SetValues method

Tüm öznitelikler için yeni değerler ayarlar. Ayrıca kullanmayı düşünün[`CopyValues`](../copyvalues) tek bir çağrıda ayar değerlerini düzene sokma yöntemi.

```csharp
public int SetValues(object[] values)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| values | Object[] | Yeni değerler dizisi. |

### Geri dönüş değeri

Ayarlanan öznitelik değerlerinin sayısı.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Argüman olamaz`null`. |
| ArgumentException | Bu ada sahip öznitelik bu katmanda mevcut değil. |
| InvalidOperationException | Özellik kilitli değil. |
| InvalidCastException | Değerin türü uygulanmıyorIConvertible. |
| FormatException | Değer yanlış biçimde olduğundan dönüştürme başarısız oldu. |
| OverflowException | Taşma nedeniyle dönüştürme başarısız oldu. |

### Notlar

Bu yöntem, her değeri otomatik olarak özniteliğin türüne dönüştürür.  Değerler dizisinin uzunluğunun, özellikteki öznitelik sayısıyla eşleşmesi gerekmez. Dizi uzunluğu öznitelik sayısından büyükse, tüm dizi değerleri özniteliklere kopyalanır; daha azsa, 0. sıralı öznitelik değerinden başlayarak, yalnızca dizi uzunluğu değerleri özniteliklere kopyalanır,

### Ayrıca bakınız

* class [Feature](../../feature)
* ad alanı [Aspose.Gis](../../feature)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->