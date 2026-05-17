---
title: "Elipsoit Sınıfı"
type: docs
weight: 40
url: /tr/python-net/aspose.gis.spatialreferencing/ellipsoid/
---

**Summary:** Ellipsoid represents an ellipsoid, which approximates earth.

**Module:** [aspose.gis.spatialreferencing](/psd/python-net/aspose.gis.spatialreferencing/)

**Full Name:** aspose.gis.spatialreferencing.Ellipsoid

**Inheritance:** IdentifiableObject

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [Ellipsoid(name, semi_major_axis, inverse_flattening, identifier)](#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1) | Yeni bir Elipsoit oluşturur. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| airy [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | Airy elipsoidi. |
| epsg_code | int | r | Eğer bu nesnenin tanımlayıcısı EPSG tanımlayıcısıysa - kodunu döndür. Aksi takdirde -1 döndür. |
| grs80 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | GRS 1980 Elipsoidi. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | r | Bu tanımlanabilir nesnenin tanımlayıcısı. |
| inverse_flattening | double | r | Elipsoidin ters yassılaşması. Bu bir küre ise 0. |
| is_sphere | bool | r | Bu elipsoidin bir küre olup olmadığını algılar. |
| is_valid | bool | r | Elipsoidin geçerli olup olmadığını algılar: yarı büyük ekseni 0'dan büyük olmalı ve ters yassılaşma pozitif ya da 0'a eşit olmalıdır. |
| ad | string | r | Bu nesnenin adı. |
| semi_major_axis | double | r | Elipsoidin yarı büyük ekseni. |
| semi_minor_axis | double | r | Elipsoidin yarı küçük ekseni. Bu bir küre ise yarı büyük eksene eşittir. |
| wgs72 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 72 Elipsoidi. |
| wgs84 [static] | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | r | WGS 84 Elipsoidi. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [is_equivalent(ellipsoid1, ellipsoid2)](#is_equivalent_ellipsoid1_ellipsoid2_1) | İki elipsoidin eşit olup olmadığını belirler.<br/>            Elipsoit A, elipsoit B'ye eşitse, aynı yarı büyük eksene ve ters yassılaşmaya sahiptir. |
| [is_equivalent(other)](#is_equivalent_other_2) | İki elipsoidin eşit olup olmadığını belirler.<br/>            Elipsoit A, elipsoit B'ye eşitse, aynı yarı büyük eksene ve ters yassılaşmaya sahiptir. |


### Constructor: Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) {#Ellipsoid_name_semi_major_axis_inverse_flattening_identifier_1}


```
 Ellipsoid(name, semi_major_axis, inverse_flattening, identifier) 
```

Yeni bir Elipsoit oluşturur.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ad | string | Elipsoitin adı. |
| semi_major_axis | double | Elipsoidin yarı büyük ekseni. |
| inverse_flattening | double | Elipsoidin ters yassılaşması. Bir sferoid oluşturmak için 0 olmalıdır. |
| identifier | [Identifier](/psd/python-net/aspose.gis.spatialreferencing/identifier) | Elipsoidin tanımlayıcısı. |

### Method: is_equivalent(ellipsoid1, ellipsoid2)  [static] {#is_equivalent_ellipsoid1_ellipsoid2_1}


```
 is_equivalent(ellipsoid1, ellipsoid2) 
```

İki elipsoidin eşit olup olmadığını belirler.<br/>            Elipsoit A, elipsoit B'ye eşitse, aynı yarı büyük eksene ve ters yassılaşmaya sahiptir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| ellipsoid1 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | İlk elipsoid. |
| ellipsoid2 | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | İkinci elipsoid. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | bool değer, iki elipsoidin eşit olup olmadığını gösterir. |


### Method: is_equivalent(other) {#is_equivalent_other_2}


```
 is_equivalent(other) 
```

İki elipsoidin eşit olup olmadığını belirler.<br/>            Elipsoit A, elipsoit B'ye eşitse, aynı yarı büyük eksene ve ters yassılaşmaya sahiptir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| other | [Ellipsoid](/psd/python-net/aspose.gis.spatialreferencing/ellipsoid) | Diğer elipsoid. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| bool | bool değer, iki elipsoidin eşit olup olmadığını gösterir. |


