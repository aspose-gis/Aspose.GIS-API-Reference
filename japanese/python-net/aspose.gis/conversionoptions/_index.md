---
title: "ConversionOptions クラス"
type: docs
weight: 380
url: /ja/python-net/aspose.gis/conversionoptions/
---

**Summary:** Options for converting data between formats.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.ConversionOptions

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [ConversionOptions()](#ConversionOptions__1) | ConversionOptions クラスの新しいインスタンスを初期化します |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| attributes_converter | [IAttributesConverter](/psd/python-net/aspose.gis/iattributesconverter) | r/w | 属性用のカスタムコンバータです。宛先属性の名前変更または除外が可能です。<br/>            <see langword="null" /> でない場合、ソースレイヤーの各属性に対して呼び出され、必要に応じて変更されます。 |
| destination_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | 宛先レイヤー用のドライバー固有オプション。 |
| destination_spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | 宛先レイヤーに割り当てる空間参照系。 |
| source_driver_options | [DriverOptions](/psd/python-net/aspose.gis/driveroptions) | r/w | ソースレイヤー用のドライバー固有オプション。 |


### Constructor: ConversionOptions() {#ConversionOptions__1}


```
 ConversionOptions() 
```

ConversionOptions クラスの新しいインスタンスを初期化します

