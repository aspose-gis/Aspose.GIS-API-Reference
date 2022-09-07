---
title: GetValueOrDefault
second_title: Aspose.GIS for .NET API Referansı
description: Bir özniteliğin değerini alır veyaDefaultValueaspose.gis/featureattribute/defaultvalue değer ayarlanmamışsa veyahükümsüz .
type: docs
weight: 40
url: /tr/net/aspose.gis/feature/getvalueordefault/
---
## GetValueOrDefault&lt;T&gt;(string) {#getvalueordefault_1}

Bir özniteliğin değerini alır veya[`DefaultValue`](../../featureattribute/defaultvalue) değer ayarlanmamışsa veya`hükümsüz` .

```csharp
public T GetValueOrDefault<T>(string attributeName)
```

| Parametre | Tanım |
| --- | --- |
| T | Değer için istenen tür. |
| attributeName | Özelliğin adı. |

### Geri dönüş değeri

Özelliğin değeri.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Özellik adı`null`. |
| ArgumentException | Bu ada sahip öznitelik bu katmanda mevcut değil. |
| InvalidOperationException | Özellik kilitli değil. |
| InvalidOperationException | Bu özelliğin değeri bu özellik için ayarlanmamıştır. |
| InvalidCastException | İstenen tür uygulanmıyorIConvertible. |
| InvalidCastException | Özelliğin değeri:`null`, ancak istenen tür bir değer türüdür. |
| FormatException | Değer yanlış biçimde olduğundan dönüştürme başarısız oldu. |
| OverflowException | Taşma nedeniyle dönüştürme başarısız oldu. |

### Notlar

Bu yöntem, değeri otomatik olarak genel tür parametresinde istenen türe dönüştürür.

### Ayrıca bakınız

* class [Feature](../../feature)
* ad alanı [Aspose.Gis](../../feature)
* toplantı [Aspose.GIS](../../../)

---

## GetValueOrDefault(string, object) {#getvalueordefault}

Bir özniteliğin değerini alır veya[`DefaultValue`](../../featureattribute/defaultvalue) değer ayarlanmamışsa veya`hükümsüz` .

```csharp
public object GetValueOrDefault(string attributeName, object defaultValue = null)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| attributeName | String | Özelliğin adı. |
| defaultValue | Object | Öznitelik değeri eksikse döndürülecek değer. Varsayılan değer`null` . |

### Geri dönüş değeri

Özelliğin değeri.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Özellik adı`null`. |
| ArgumentException | Bu ada sahip öznitelik bu katmanda mevcut değil. |
| InvalidOperationException | Özellik kilitli değil. |
| InvalidOperationException | Bu özelliğin değeri bu özellik için ayarlanmamıştır. |

### Ayrıca bakınız

* class [Feature](../../feature)
* ad alanı [Aspose.Gis](../../feature)
* toplantı [Aspose.GIS](../../../)

---

## GetValueOrDefault&lt;T&gt;(string, object) {#getvalueordefault_2}

Bir özniteliğin değerini alır veya[`DefaultValue`](../../featureattribute/defaultvalue) değer ayarlanmamışsa veya`hükümsüz` .

```csharp
public T GetValueOrDefault<T>(string attributeName, object defaultValue)
```

| Parametre | Tanım |
| --- | --- |
| T | Değer için istenen tür. |
| attributeName | Özelliğin adı. |
| defaultValue | Öznitelik değeri eksikse döndürülecek değer. |

### Geri dönüş değeri

Özelliğin değeri.

### istisnalar

| istisna | şart |
| --- | --- |
| ArgumentNullException | Özellik adı`null`. |
| ArgumentException | Bu ada sahip öznitelik bu katmanda mevcut değil. |
| InvalidOperationException | Özellik kilitli değil. |
| InvalidOperationException | Bu özelliğin değeri bu özellik için ayarlanmamıştır. |
| InvalidCastException | İstenen tür uygulanmıyorIConvertible. |
| InvalidCastException | Özelliğin değeri:`null`, ancak istenen tür bir değer türüdür. |
| FormatException | Değer yanlış biçimde olduğundan dönüştürme başarısız oldu. |
| OverflowException | Taşma nedeniyle dönüştürme başarısız oldu. |

### Notlar

Bu yöntem, değeri otomatik olarak genel tür parametresinde istenen türe dönüştürür.

### Ayrıca bakınız

* class [Feature](../../feature)
* ad alanı [Aspose.Gis](../../feature)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->