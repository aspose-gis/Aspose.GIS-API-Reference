---
title: Open
second_title: Aspose.GIS for .NET API Referansı
description: Bunu açarSoyutYoldosya olarak.
type: docs
weight: 120
url: /tr/net/aspose.gis/abstractpath/open/
---
## AbstractPath.Open method

Bunu açar`SoyutYol`dosya olarak.

```csharp
public abstract Stream Open(FileAccess access)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| access | FileAccess | üzerinde gerçekleştirilebilecek işlemlerin bir alt kümesini belirtir.Stream. |

### Geri dönüş değeri

AStream belirtilen ile açıldıFileAccess .

### Notlar

Eğer*access* bayrağı varWrite ayarlanmışsa ve dosya mevcut değilse, bir mirasçı onu oluşturmalıdır. Bir`SoyutYol` tarafından birden çok kez açılabilir`Aspose.GIS` . Bu, bir file dosyasını birden çok akışla bağımsız olarak okumak için gereklidir. Sonucu önbelleğe almamalı, bunun yerine yenisini döndürmelisiniz.Stream her time bu yöntem çağrılır.

### Ayrıca bakınız

* class [AbstractPath](../../abstractpath)
* ad alanı [Aspose.Gis](../../abstractpath)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->