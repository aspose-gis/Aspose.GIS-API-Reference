---
title: SimpleLabeling
second_title: Aspose.GIS for .NET API Referansı
description: Basit bir etiketleme her özelliğin üzerine etiket yerleştirir.
type: docs
weight: 1600
url: /tr/net/aspose.gis.rendering.labelings/simplelabeling/
---
## SimpleLabeling class

Basit bir etiketleme, her özelliğin üzerine etiket yerleştirir.

```csharp
public class SimpleLabeling : Labeling
```

## yapıcılar

| İsim | Tanım |
| --- | --- |
| [SimpleLabeling](simplelabeling#constructor)() | Yeni bir örneğini başlatır[`SimpleLabeling`](../simplelabeling) sınıf. |
| [SimpleLabeling](simplelabeling#constructor_1)(SimpleLabeling) | Yeni bir örneğini başlatır[`SimpleLabeling`](../simplelabeling) sınıf. |
| [SimpleLabeling](simplelabeling#constructor_2)(string) | Yeni bir örneğini başlatır[`SimpleLabeling`](../simplelabeling) sınıf. |

## Özellikleri

| İsim | Tanım |
| --- | --- |
| [FeatureBasedConfiguration](../../aspose.gis.rendering.labelings/simplelabeling/featurebasedconfiguration) { get; set; } | Bir özelliği işlemeden önce bu etiketlemeyi yapılandırmak için kullanılan bir geri arama. |
| [FontColor](../../aspose.gis.rendering.labelings/simplelabeling/fontcolor) { get; set; } | Metnin rengini belirler. |
| [FontFamily](../../aspose.gis.rendering.labelings/simplelabeling/fontfamily) { get; set; } | Metin oluşturmak için kullanılacak yazı tipi ailesi. Varsayılan, sisteme bağlı değerdir. |
| [FontSize](../../aspose.gis.rendering.labelings/simplelabeling/fontsize) { get; set; } | Metnin boyutu. |
| [FontStyle](../../aspose.gis.rendering.labelings/simplelabeling/fontstyle) { get; set; } | Metne uygulanacak stil. |
| [GeometryExpression](../../aspose.gis.rendering.labelings/simplelabeling/geometryexpression) { get; set; } | Unsur geometrisini etiketleme için değiştirilmiş olanla değiştirmenin bir yolunu sağlar. Bu geri arama,[`FeatureBasedConfiguration`](./featurebasedconfiguration) . Varsayılan`null` (özellik geometrisini olduğu gibi kullanın). |
| [HaloColor](../../aspose.gis.rendering.labelings/simplelabeling/halocolor) { get; set; } | Metnin etrafındaki halenin (kontur) rengi. |
| [HaloSize](../../aspose.gis.rendering.labelings/simplelabeling/halosize) { get; set; } | Metnin etrafındaki halenin (kontur) boyutu. |
| [LabelAttribute](../../aspose.gis.rendering.labelings/simplelabeling/labelattribute) { get; set; } | Etiket kaynağı olarak kullanılacak özellik adı. yoksa yoksayıldı[`LabelExpression`](./labelexpression) ayarlandı. Her ikisi de[`LabelAttribute`](./labelattribute) veya[`LabelExpression`](./labelexpression) oluşturmadan önce ayarlanmalıdır; InvalidOperationException aksi halde atılır. |
| [LabelExpression](../../aspose.gis.rendering.labelings/simplelabeling/labelexpression) { get; set; } | Etiket metnini özelleştirmek ve biçimlendirmek için bir yol sağlar. Ayarlanırsa, geçersiz kılar[`LabelAttribute`](./labelattribute) . Ya[`LabelAttribute`](./labelattribute) veya[`LabelExpression`](./labelexpression) oluşturmadan önce ayarlanmalıdır; InvalidOperationException aksi halde atılır. |
| [MultipartMode](../../aspose.gis.rendering.labelings/simplelabeling/multipartmode) { get; set; } | Çok parçalı geometriler için işleme davranışını belirtir. VarsayılanAll . |
| [Placement](../../aspose.gis.rendering.labelings/simplelabeling/placement) { get; set; } | Etiket yerleşimi, etiketlerin özelliğin geometrilerine göre nasıl yerleştirileceğini belirtir. |
| [Priority](../../aspose.gis.rendering.labelings/simplelabeling/priority) { get; set; } | Başka bir etiketle çakışması durumunda bu etiketin önceliğini belirtir. Daha düşük önceliğe sahip etiket oluşturulmaz. Varsayılan değer 1000. |

## yöntemler

| İsim | Tanım |
| --- | --- |
| [Clone](../../aspose.gis.rendering.labelings/simplelabeling/clone)() | Bu örneği klonlar. |

### Ayrıca bakınız

* class [Labeling](../labeling)
* ad alanı [Aspose.Gis.Rendering.Labelings](../../aspose.gis.rendering.labelings)
* toplantı [Aspose.GIS](../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->