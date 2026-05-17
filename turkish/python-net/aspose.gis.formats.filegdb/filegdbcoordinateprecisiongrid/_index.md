---
title: "FileGdbCoordinatePrecisionGrid Sınıfı"
type: docs
weight: 10
url: /tr/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | FileGdbCoordinatePrecisionGrid sınıfının yeni bir örneğini başlatır |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | M koordinatının başlangıç noktasını alır veya ayarlar. <see langword=\"null\" /> olarak ayarlanırsa varsayılan kullanılır. |
| m_scale | Nullable<double> | r/w | M koordinatının ölçeğini alır veya ayarlar. <see langword=\"null\" /> olarak ayarlanırsa varsayılan kullanılır. |
| x_origin | Nullable<double> | r/w | X koordinatının başlangıç noktasını alır veya ayarlar. <see langword="null" /> olarak ayarlanırsa varsayılan kullanılır. |
| xy_scale | Nullable<double> | r/w | X ve Y koordinatlarının ölçeğini alır veya ayarlar. <see langword="null" /> olarak ayarlanırsa varsayılan kullanılır. |
| y_origin | Nullable<double> | r/w | Y koordinatının başlangıç noktasını alır veya ayarlar. <see langword="null" /> olarak ayarlanırsa varsayılan kullanılır. |
| z_origin | Nullable<double> | r/w | Z koordinatının başlangıç noktasını alır veya ayarlar. <see langword="null" /> olarak ayarlanırsa varsayılan kullanılır. |
| z_scale | Nullable<double> | r/w | Z koordinatının ölçeğini alır veya ayarlar. <see langword="null" /> olarak ayarlanırsa varsayılan kullanılır. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Yeni <c>FileGdbCoordinatePrecisionGrid</c> oluşturur, böylece bir dikdörtgen içindeki tüm değerler temsil edilebilir. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

FileGdbCoordinatePrecisionGrid sınıfının yeni bir örneğini başlatır

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Yeni <c>FileGdbCoordinatePrecisionGrid</c> oluşturur, böylece bir dikdörtgen içindeki tüm değerler temsil edilebilir.

**Parameters:**

| Parametre | Tür | Açıklama |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Dikdörtgenin bir köşesi. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Dikdörtgenin karşı köşesi. <paramref name="p1" /> ile aynı boyutlarda olmalıdır. |

**Returns**

| Tür | Açıklama |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | <c>FileGdbCoordinatePrecisionGrid</c> nesnesi, bir dikdörtgen içindeki tüm değerlerin temsil edilebilmesini sağlar.<br/>            Dikdörtgen dışındaki değerler temsil edilemez, bu yüzden FileGDB katmanına yazılacak tüm koordinatlar<br/>            dikdörtgen içinde olmalıdır. |


