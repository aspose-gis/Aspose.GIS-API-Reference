---
title: "Extent Sınıfı"
type: docs
weight: 820
url: /tr/python-net/aspose.gis/extent/
---

**Summary:** A two-dimensional spatial bounding box.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.Extent

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Extent()](#Extent__1) | Yeni bir örnek oluşturur. |
| [Extent(srs)](#Extent_srs_2) | Yeni bir örnek oluşturur. |
| [Extent(x_min, y_min, x_max, y_max, srs)](#Extent_x_min_y_min_x_max_y_max_srs_3) | Yeni bir örnek oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| center | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | r | Extent'in merkezi. |
| yükseklik | double | r | Extent'in yüksekliği. |
| is_valid | bool | r | Bu [Extent](/psd/python-net/aspose.gis/extent/) geçerli olup olmadığını belirler. |
| spatial_reference_system | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | r/w | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) bu extent ile ilişkilidir.<br/>            Eğer [Extent.spatial_reference_system](/psd/python-net/aspose.gis/extent/) bilinmiyorsa <see langword="null" /> olabilir.<br/>            Aspose.Gis.Extent.GetTransformed(Aspose.Gis.SpatialReferencing.SpatialReferenceSystem) yöntemini kullanın<br/>            farklı mekansal referans sistemleri arasında extent'i dönüştürmek için. |
| genişlik | double | r | Extent'in genişliği. |
| x_max | double | r/w | X koordinatının maksimum değeri. |
| x_min | double | r/w | X koordinatının minimum değeri. |
| y_max | double | r/w | Y koordinatının maksimum değeri. |
| y_min | double | r/w | Y koordinatının minimum değeri. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [clone()](#clone__1) | Bu örneği klonlar. |
| [contains(extent)](#contains_extent_2) | Bu kapsamın argümanı içerip içermediğini belirler. |
| [contains(geometry)](#contains_geometry_3) | Bu kapsamın argümanı içerip içermediğini belirler. |
| [contains(x, y)](#contains_x_y_4) | Bu kapsamın, argümanlar tarafından tanımlanan bir koordinatı içerip içermediğini belirler. |
| [get_transformed(target_srs)](#get_transformed_target_srs_5) | Bu kapsamı içeren, belirtilen [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) içinde yeni bir kapsam döndürür. |
| [grow(extent)](#grow_extent_6) | Bu kapsamı, argümanı içerecek şekilde genişletir. |
| [grow(x, y)](#grow_x_y_7) | Bu kapsamı, belirtilen noktayı içerecek şekilde genişletir. |
| [grow_x(value)](#grow_x_value_8) | Bu kapsamı X ekseni boyunca, belirtilen değeri içerecek şekilde genişletir. |
| [grow_y(value)](#grow_y_value_9) | Bu kapsamı Y ekseni boyunca, belirtilen değeri içerecek şekilde genişletir. |
| [intersects(extent)](#intersects_extent_10) | Bu kapsamın argümanla kesişip kesişmediğini belirler. |
| [intersects(geometry)](#intersects_geometry_11) | Bu kapsamın argümanla kesişip kesişmediğini belirler. |
| normalize() | Eğer [Extent.width](/psd/python-net/aspose.gis/extent/) negatif ise [Extent.x_min](/psd/python-net/aspose.gis/extent/) ile [Extent.x_max](/psd/python-net/aspose.gis/extent/) yer değiştirir ve<br/>            [Extent.height](/psd/python-net/aspose.gis/extent/) negatif ise [Extent.y_min](/psd/python-net/aspose.gis/extent/) ile [Extent.y_max](/psd/python-net/aspose.gis/extent/) yer değiştirir. |
| [to_polygon()](#to_polygon__12) | Bu kapsamı onu temsil eden dikdörtgen bir çokgene dönüştürür. |


### Constructor: Extent() {#Extent__1}


```
 Extent() 
```

Yeni bir örnek oluşturur.

### Constructor: Extent(srs) {#Extent_srs_2}


```
 Extent(srs) 
```

Yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) bu kapsamla ilişkilidir.<br/>            SRS'nin bilinmediğini göstermek için <see langword="null" /> olabilir. |

### Constructor: Extent(x_min, y_min, x_max, y_max, srs) {#Extent_x_min_y_min_x_max_y_max_srs_3}


```
 Extent(x_min, y_min, x_max, y_max, srs) 
```

Yeni bir örnek oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x_min | double | Minimum X değeri. |
| y_min | double | Minimum Y değeri. |
| x_max | double | Maximum X değeri. |
| y_max | double | Maximum Y değeri. |
| srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) bu kapsamla ilişkilidir.<br/>            SRS'nin bilinmediğini göstermek için <see langword="null" /> olabilir. |

### Method: clone() {#clone__1}


```
 clone() 
```

Bu örneği klonlar.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Bu örneğin kopyası. |


### Method: contains(extent) {#contains_extent_2}


```
 contains(extent) 
```

Bu kapsamın argümanı içerip içermediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Başka bir kapsam. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu kapsamın argümanı içerip içermediğini gösteren değer. |


### Method: contains(geometry) {#contains_geometry_3}


```
 contains(geometry) 
```

Bu kapsamın argümanı içerip içermediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | İçerme testi için bir geometri. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu kapsamın argümanı içerip içermediğini gösteren değer. |


### Method: contains(x, y) {#contains_x_y_4}


```
 contains(x, y) 
```

Bu kapsamın, argümanlar tarafından tanımlanan bir koordinatı içerip içermediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | double | Koordinatın X'i. |
| y | double | Koordinatın Y'si. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Koordinatın sınırlayıcı kutunun içinde olup olmadığını gösteren değer. |


### Method: get_transformed(target_srs) {#get_transformed_target_srs_5}


```
 get_transformed(target_srs) 
```

Bu kapsamı içeren, belirtilen [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) içinde yeni bir kapsam döndürür.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| target_srs | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) | [SpatialReferenceSystem](/psd/python-net/aspose.gis.spatialreferencing/spatialreferencesystem/) dönüştürülecek. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Extent](/psd/python-net/aspose.gis/extent) | Bu kapsamın belirtilen SRS'ye dönüşümünün sonucu. |


### Method: grow(extent) {#grow_extent_6}


```
 grow(extent) 
```

Bu kapsamı, argümanı içerecek şekilde genişletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Diğer kapsam. |

### Method: grow(x, y) {#grow_x_y_7}


```
 grow(x, y) 
```

Bu kapsamı, belirtilen noktayı içerecek şekilde genişletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| x | double | Eklenecek X koordinatı. |
| y | double | Eklenecek Y koordinatı. |

### Method: grow_x(value) {#grow_x_value_8}


```
 grow_x(value) 
```

Bu kapsamı X ekseni boyunca, belirtilen değeri içerecek şekilde genişletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | double | Eklenecek değer. |

### Method: grow_y(value) {#grow_y_value_9}


```
 grow_y(value) 
```

Bu kapsamı Y ekseni boyunca, belirtilen değeri içerecek şekilde genişletir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| value | double | Eklenecek değer. |

### Method: intersects(extent) {#intersects_extent_10}


```
 intersects(extent) 
```

Bu kapsamın argümanla kesişip kesişmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| extent | [Extent](/psd/python-net/aspose.gis/extent) | Başka bir kapsam. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu kapsamın argümanla kesişip kesişmediğini gösteren değer. |


### Method: intersects(geometry) {#intersects_geometry_11}


```
 intersects(geometry) 
```

Bu kapsamın argümanla kesişip kesişmediğini belirler.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | Kesişmeyi test etmek için bir geometri |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | Bu kapsamın argümanla kesişip kesişmediğini gösteren değer. |


### Method: to_polygon() {#to_polygon__12}


```
 to_polygon() 
```

Bu kapsamı onu temsil eden dikdörtgen bir çokgene dönüştürür.

**Returns**

| Tür | Açıklama |
| :- | :- |
| [Polygon](/psd/python-net/aspose.gis.geometries/polygon/) | Bu kapsamı temsil eden dikdörtgen bir [Polygon](/psd/python-net/aspose.gis.geometries/polygon/). Geçersiz kapsamlar için<br/>            boş bir poligon döndürülür. |


