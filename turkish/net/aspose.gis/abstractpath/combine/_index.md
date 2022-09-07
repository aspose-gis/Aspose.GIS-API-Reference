---
title: Combine
second_title: Aspose.GIS for .NET API Referansı
description: Bunu birleştirirAbstractPathaspose.gis/abstractpath belirtilen yol bileşenleriyle.
type: docs
weight: 50
url: /tr/net/aspose.gis/abstractpath/combine/
---
## AbstractPath.Combine method

Bunu birleştirir[`AbstractPath`](../../abstractpath) belirtilen yol bileşenleriyle.

```csharp
public virtual AbstractPath Combine(string location)
```

| Parametre | Tip | Tanım |
| --- | --- | --- |
| location | String | Buna eklenecek bir yol bileşeni[`AbstractPath`](../../abstractpath). |

### Geri dönüş değeri

Yeni bir[`AbstractPath`](../../abstractpath) işaret eden bir[`Location`](../location) bu, bunun konumlarının bir kombinasyonudur[`AbstractPath`](../../abstractpath)ve argüman.

### Notlar

Genellikle bu yöntem bir mirasçı tarafından geçersiz kılınmamalıdır. Varsayılan application bunu birleştirir[`Location`](../location) argüman ile ve çağırır[`WithLocation`](../withlocation) Argüman olarak birleştirilmiş dize ile yöntemi. Kombinasyon sonucu şu şekilde tanımlanır:  Argüman ile başlarsa[`Separator`](../separator), kombinasyon sonucu argümana eşittir; Aksi takdirde, eğer[`Location`](../location) ile biter[`Separator`](../separator) , kombinasyon sonucu şuna eşittir:` +`; Aksi takdirde, sonuç eşittir` + +`

### Ayrıca bakınız

* class [AbstractPath](../../abstractpath)
* ad alanı [Aspose.Gis](../../abstractpath)
* toplantı [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->