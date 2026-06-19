---
title: "Map.Render"
second_title: "Aspose.GIS for .NET API 参考文档"
description: "Map 方法。将地图渲染到文件中"
type: docs
weight: 140
url: /zh/net/aspose.gis.rendering/map/render/
---
## Render(string, Renderer) {#render_1}

将地图渲染到文件中。

```csharp
public void Render(string outputPath, Renderer renderer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputPath | 字符串 | 输出文件的路径。 |
| 渲染器 | 渲染器 | 要使用的渲染器。 |

### 另见

* class [Renderer](../../renderer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)

---

## Render(AbstractPath, Renderer) {#render}

将地图渲染到文件中。

```csharp
public void Render(AbstractPath outputPath, Renderer renderer)
```

| 参数 | 类型 | 描述 |
| --- | --- | --- |
| outputPath | AbstractPath | 输出文件的路径。 |
| 渲染器 | 渲染器 | 要使用的渲染器。 |

### 异常

| 异常 | 条件 |
| --- | --- |
| ArgumentNullException | 任意参数为 `null`。 |
| IOException | 发生了 I/O 错误。 |
| [GisException](../../../aspose.gis/gisexception/) | 处理或读取 GIS 数据时出错。 |

### 另见

* class [AbstractPath](../../../aspose.gis/abstractpath/)
* class [Renderer](../../renderer/)
* class [Map](../)
* namespace [Aspose.Gis.Rendering](../../map/)
* assembly [Aspose.GIS](../../../)


