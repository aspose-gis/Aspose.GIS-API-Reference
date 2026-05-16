---
title: "PrimeMeridian クラス"
type: docs
weight: 140
url: /ja/python-net/aspose.gis.spatialreferencing/primemeridian/
---

**Summary:** PrimeMeridian represents a meridian at which longitude is defined to be 0.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.PrimeMeridian

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [PrimeMeridian(name, longitude, identifier)](#PrimeMeridian_name_longitude_identifier_1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| epsg_code | int | r | このオブジェクトの識別子が EPSG 識別子の場合はそのコードを返します。そうでない場合は -1 を返します。 |
| greenwich [static] | [PrimeMeridian](/psd/python-net/aspose.gis.spatialreferencing/primemeridian) | r | グリニッジ子午線。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | この識別可能オブジェクトの識別子。 |
| 経度 | double | r | グリニッジ子午線から本初子午線までの距離（度）。 |
| 名前 | string | r | このオブジェクトの名前。 |


### Constructor: PrimeMeridian(name, longitude, identifier) {#PrimeMeridian_name_longitude_identifier_1}


```
 PrimeMeridian(name, longitude, identifier) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | この本初子午線の名前。 |
| 経度 | double | グリニッジに対する本初子午線の経度（度）。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | 本初子午線の識別子。 |

