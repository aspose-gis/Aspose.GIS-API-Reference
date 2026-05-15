---
title: "IDatabaseDataSource.ReadAsync"
second_title: "Aspose.GIS for .NET API 参考"
description: "IDatabaseDataSource 方法。读取地理空间数据的方法"
type: docs
weight: 10
url: /zh/net/aspose.gis.formats.database/idatabasedatasource/readasync/
---
## ReadAsync(DbConnection, IDictionary&lt;string, object&gt;) {#readasync}

读取地理空间数据的方法。

```csharp
public Task<VectorLayer> ReadAsync(DbConnection connection, 
    IDictionary<string, object> sqlParametrs = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 连接 | DbConnection | 连接对象。 |
| sqlParametrs | IDictionary`2 | SQL 参数集合 |

### 返回值

返回一个 InMemoryLayer 实例，包装在 ReadVectorWrapper 中，以便在需要时执行额外的几何转换。

## 备注

必须配置连接并保持打开状态。

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* interface [IDatabaseDataSource](../)
* namespace [Aspose.Gis.Formats.Database](../../idatabasedatasource/)
* assembly [Aspose.GIS](../../../)

---

## ReadAsync(DbConnection, DbTransaction, IDictionary&lt;string, object&gt;) {#readasync_1}

在事务中读取地理空间数据的方法..

```csharp
public Task<VectorLayer> ReadAsync(DbConnection connection, DbTransaction transaction, 
    IDictionary<string, object> sqlParametrs = null)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| 连接 | DbConnection | 连接对象。 |
| 事务 | DbTransaction | 当前事务。 |
| sqlParametrs | IDictionary`2 | SQL 参数集合 |

### 返回值

返回一个 InMemoryLayer 实例，包装在 ReadVectorWrapper 中，以便在需要时执行额外的几何转换。

## 备注

必须配置连接并保持打开状态。

### 另见

* class [VectorLayer](../../../aspose.gis/vectorlayer/)
* interface [IDatabaseDataSource](../)
* namespace [Aspose.Gis.Formats.Database](../../idatabasedatasource/)
* assembly [Aspose.GIS](../../../)


