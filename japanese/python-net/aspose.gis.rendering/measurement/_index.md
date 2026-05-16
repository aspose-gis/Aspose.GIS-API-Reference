---
title: "Measurement クラス"
type: docs
weight: 150
url: /ja/python-net/aspose.gis.rendering/measurement/
---

**Summary:** A number that indicates a render measurement.

**Module:** [aspose.gis.rendering](/psd/python-net/aspose.gis.rendering/)

**Full Name:** aspose.gis.rendering.Measurement

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [Measurement()](#Measurement__1) | Measurement クラスの新しいインスタンスを初期化します |
| [Measurement(value, unit)](#Measurement_value_unit_2) | 新しいインスタンスを作成します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | r | 測定単位です。 |
| 値 | double | r | 測定の長さを示す数値です。 |
| zero [static] | [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | r | 長さがゼロの測定です。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [inches(value)](#inches_value_1) | 長さをインチで表す <c>Measurement</c> の新しいインスタンスを返します。 |
| [map_units(value)](#map_units_value_2) | 長さをマップの空間参照単位で表す <c>Measurement</c> の新しいインスタンスを返します。 |
| [meters_on_earth(value)](#meters_on_earth_value_3) | 地球上のメートルで長さを表す <c>Measurement</c> の新しいインスタンスを返します。 |
| [millimeters(value)](#millimeters_value_4) | 長さをミリメートルで表す <c>Measurement</c> の新しいインスタンスを返します。 |
| [pixels(value)](#pixels_value_5) | 長さをピクセルで表す <c>Measurement</c> の新しいインスタンスを返します。 |
| [points(value)](#points_value_6) | 長さをポイントで表す <c>Measurement</c> の新しいインスタンスを返します。 |


### Constructor: Measurement() {#Measurement__1}


```
 Measurement() 
```

Measurement クラスの新しいインスタンスを初期化します

### Constructor: Measurement(value, unit) {#Measurement_value_unit_2}


```
 Measurement(value, unit) 
```

新しいインスタンスを作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 値 | double | 測定の長さを示す数値です。 |
| unit | [Unit](/psd/python-net/aspose.gis.spatialreferencing/unit) | 測定単位です。 |

### Method: inches(value)  [static] {#inches_value_1}


```
 inches(value) 
```

長さをインチで表す <c>Measurement</c> の新しいインスタンスを返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 値 | double | インチ数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> クラスの新しいインスタンスです。 |


### Method: map_units(value)  [static] {#map_units_value_2}


```
 map_units(value) 
```

長さをマップの空間参照単位で表す <c>Measurement</c> の新しいインスタンスを返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 値 | double | 単位数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> クラスの新しいインスタンスです。 |


### Method: meters_on_earth(value)  [static] {#meters_on_earth_value_3}


```
 meters_on_earth(value) 
```

地球上のメートルで長さを表す <c>Measurement</c> の新しいインスタンスを返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 値 | double | メートル数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> クラスの新しいインスタンスです。 |


### Method: millimeters(value)  [static] {#millimeters_value_4}


```
 millimeters(value) 
```

長さをミリメートルで表す <c>Measurement</c> の新しいインスタンスを返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 値 | double | ミリメートル数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> クラスの新しいインスタンスです。 |


### Method: pixels(value)  [static] {#pixels_value_5}


```
 pixels(value) 
```

長さをピクセルで表す <c>Measurement</c> の新しいインスタンスを返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 値 | double | ピクセル数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> クラスの新しいインスタンスです。 |


### Method: points(value)  [static] {#points_value_6}


```
 points(value) 
```

長さをポイントで表す <c>Measurement</c> の新しいインスタンスを返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| 値 | double | ポイント数。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [Measurement](/psd/python-net/aspose.gis.rendering/measurement) | <c>Measurement</c> クラスの新しいインスタンスです。 |


