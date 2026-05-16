---
title: "LocalDatum クラス"
type: docs
weight: 120
url: /ja/python-net/aspose.gis.spatialreferencing/localdatum/
---

**Summary:** Indicates method used for measurements in local spatial reference system.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.LocalDatum

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [LocalDatum(name, datum_type, identifier)](#LocalDatum_name_datum_type_identifier_1) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| datum_type | int | r | 使用された測定方法を示す整数です。 |
| epsg_code | int | r | このオブジェクトの識別子が EPSG 識別子の場合はそのコードを返します。そうでない場合は -1 を返します。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | この識別可能オブジェクトの識別子。 |
| 名前 | string | r | このオブジェクトの名前。 |


### Constructor: LocalDatum(name, datum_type, identifier) {#LocalDatum_name_datum_type_identifier_1}


```
 LocalDatum(name, datum_type, identifier) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 名前 | string | データムの名前。 |
| datum_type | int | データムのタイプを表す整数。 |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | データムの識別子。 |

