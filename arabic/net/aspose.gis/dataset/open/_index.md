---
title: "Dataset.Open"
second_title: "مرجع API لـ Aspose.GIS لـ .NET"
description: "طريقة Dataset. تفتح مجموعة البيانات"
type: docs
weight: 20
url: /ar/net/aspose.gis/dataset/open/
---
## Open(string, FileDriver) {#open_3}

يفتح مجموعة البيانات.

```csharp
public static Dataset Open(string path, FileDriver driver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | مسار مجموعة البيانات. |
| المحرك | FileDriver | Driver للاستخدام. |

### قيمة الإرجاع

كائن من [`Dataset`](../).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Open(AbstractPath, FileDriver) {#open}

يفتح مجموعة البيانات.

```csharp
public static Dataset Open(AbstractPath path, FileDriver driver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | مسار مجموعة البيانات. |
| المحرك | FileDriver | Driver للاستخدام. |

### قيمة الإرجاع

كائن من [`Dataset`](../).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Open(string, FileDriver, DriverOptions) {#open_4}

يفتح مجموعة البيانات.

```csharp
public static Dataset Open(string path, FileDriver driver, DriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | String | مسار مجموعة البيانات. |
| المحرك | FileDriver | Driver للاستخدام. |
| options | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`Dataset`](../).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Open(AbstractPath, FileDriver, DriverOptions) {#open_1}

يفتح مجموعة البيانات.

```csharp
public static Dataset Open(AbstractPath path, FileDriver driver, DriverOptions options)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| path | AbstractPath | مسار مجموعة البيانات. |
| المحرك | FileDriver | Driver للاستخدام. |
| options | DriverOptions | خيارات خاصة بالسائق. |

### قيمة الإرجاع

كائن من [`Dataset`](../).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [AbstractPath](../../abstractpath/)
* class [FileDriver](../../filedriver/)
* class [DriverOptions](../../driveroptions/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)

---

## Open(IDbConnection, DatabaseDriver) {#open_2}

يفتح مجموعة البيانات.

```csharp
public static Dataset Open(IDbConnection connection, DatabaseDriver driver)
```

| معامل | نوع | الوصف |
| --- | --- | --- |
| الاتصال | IDbConnection | تم فتح الاتصال بقاعدة البيانات. |
| المحرك | DatabaseDriver | Driver للاستخدام. |

### قيمة الإرجاع

كائن من [`Dataset`](../).

### استثناءات

| استثناء | شرط |
| --- | --- |
| ArgumentException | كائن Options له نوع غير صحيح لهذا السائق. |
| ArgumentNullException | المسار هو `null`. |
| [GisException](../../gisexception/) | خطأ في قراءة مجموعة البيانات. |
| IOException | حدث خطأ في الإدخال/الإخراج. |

### انظر أيضًا

* class [DatabaseDriver](../../databasedriver/)
* class [Dataset](../)
* namespace [Aspose.Gis](../../dataset/)
* assembly [Aspose.GIS](../../../)


