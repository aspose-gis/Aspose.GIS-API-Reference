---
title: "Kelas FileGdbCoordinatePrecisionGrid"
type: docs
weight: 10
url: /id/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid/
---

**Summary:** A coordinate precision grid inside a FileGDB layer.

**Module:** [aspose.gis.formats.filegdb](/psd/python-net/aspose.gis.formats.filegdb/)

**Full Name:** aspose.gis.formats.filegdb.FileGdbCoordinatePrecisionGrid

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Deskripsi** |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid()](#FileGdbCoordinatePrecisionGrid__1) | Menginisialisasi sebuah instance baru dari kelas FileGdbCoordinatePrecisionGrid |
## **Properties**
| **Name** | **Type** | **Access** | **Deskripsi** |
| :- | :- | :- | :- |
| m_origin | Nullable<double> | r/w | Mendapatkan atau mengatur asal koordinat M. Jika diatur ke <see langword=\"null\" /> nilai default akan digunakan. |
| m_scale | Nullable<double> | r/w | Mendapatkan atau mengatur skala koordinat M. Jika diatur ke <see langword=\"null\" /> nilai default akan digunakan. |
| x_origin | Nullable<double> | r/w | Mendapatkan atau mengatur asal koordinat X. Jika disetel ke <see langword=\"null\" />, nilai default akan digunakan. |
| xy_scale | Nullable<double> | r/w | Mendapatkan atau mengatur skala koordinat X dan Y. Jika disetel ke <see langword=\"null\" />, nilai default akan digunakan. |
| y_origin | Nullable<double> | r/w | Mendapatkan atau mengatur asal koordinat Y. Jika disetel ke <see langword=\"null\" />, nilai default akan digunakan. |
| z_origin | Nullable<double> | r/w | Mendapatkan atau mengatur asal koordinat Z. Jika disetel ke <see langword=\"null\" />, nilai default akan digunakan. |
| z_scale | Nullable<double> | r/w | Mendapatkan atau mengatur skala koordinat Z. Jika disetel ke <see langword=\"null\" />, nilai default akan digunakan. |
## **Methods**
| **Name** | **Deskripsi** |
| :- | :- |
| [create_from_rectangle(p1, p2)](#create_from_rectangle_p1_p2_1) | Membuat <c>FileGdbCoordinatePrecisionGrid</c> baru sehingga semua nilai dalam sebuah persegi panjang dapat direpresentasikan. |


### Constructor: FileGdbCoordinatePrecisionGrid() {#FileGdbCoordinatePrecisionGrid__1}


```
 FileGdbCoordinatePrecisionGrid() 
```

Menginisialisasi sebuah instance baru dari kelas FileGdbCoordinatePrecisionGrid

### Method: create_from_rectangle(p1, p2)  [static] {#create_from_rectangle_p1_p2_1}


```
 create_from_rectangle(p1, p2) 
```

Membuat <c>FileGdbCoordinatePrecisionGrid</c> baru sehingga semua nilai dalam sebuah persegi panjang dapat direpresentasikan.

**Parameters:**

| Parameter | Tipe | Deskripsi |
| :- | :- | :- |
| p1 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Salah satu sudut persegi panjang. |
| p2 | [IPoint](/psd/python-net/aspose.gis.geometries/ipoint/) | Sudut berlawanan dari persegi panjang. Harus memiliki dimensi yang sama dengan <paramref name=\"p1\" />. |

**Returns**

| Tipe | Deskripsi |
| :- | :- |
| [FileGdbCoordinatePrecisionGrid](/psd/python-net/aspose.gis.formats.filegdb/filegdbcoordinateprecisiongrid) | <c>FileGdbCoordinatePrecisionGrid</c> sehingga semua nilai dalam sebuah persegi panjang dapat direpresentasikan.<br/>            Nilai di luar persegi panjang tidak dapat direpresentasikan, sehingga semua koordinat yang akan ditulis ke lapisan FileGDB<br/>            harus berada di dalam persegi panjang. |


