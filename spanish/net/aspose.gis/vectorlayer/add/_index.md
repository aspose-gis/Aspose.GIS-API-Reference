---
title: Add
second_title: Referencia de API de Aspose.GIS para .NET
description: Agrega una nueva entidad a la capa si es compatible con elVectorLayeraspose.gis/vectorlayer sDriveraspose.gis/vectorlayer/driver .
type: docs
weight: 80
url: /es/net/aspose.gis/vectorlayer/add/
---
## Add(Feature) {#add}

Agrega una nueva entidad a la capa, si es compatible con el[`VectorLayer`](../../vectorlayer) s[`Driver`](../driver) .

```csharp
public void Add(Feature feature)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| feature | Feature | La característica a agregar. |

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | se lanza si la capa es de solo lectura. |

### Ver también

* class [Feature](../../feature)
* class [VectorLayer](../../vectorlayer)
* espacio de nombres [Aspose.Gis](../../vectorlayer)
* asamblea [Aspose.GIS](../../../)

---

## Add(Feature, IFeatureStyle) {#add_1}

Agrega una nueva entidad con el estilo especificado a la capa, si es compatible con el[`VectorLayer`](../../vectorlayer) s[`Driver`](../driver) .

```csharp
public virtual void Add(Feature feature, IFeatureStyle style)
```

| Parámetro | Escribe | Descripción |
| --- | --- | --- |
| feature | Feature | La característica a agregar. |
| style | IFeatureStyle | El estilo de función. Usar`null` para indicar el estilo faltante. |

### Excepciones

| excepción | condición |
| --- | --- |
| InvalidOperationException | se lanza si la capa no admite estilos o si la capa es de solo lectura. |
| InvalidOperationException | se lanza si las capas editables no admiten estilos. |
| ArgumentException | se lanza si el estilo no coincide con el tipo de controlador. |

### Ver también

* class [Feature](../../feature)
* interface [IFeatureStyle](../../ifeaturestyle)
* class [VectorLayer](../../vectorlayer)
* espacio de nombres [Aspose.Gis](../../vectorlayer)
* asamblea [Aspose.GIS](../../../)

<!-- DO NOT EDIT: generated by xmldocmd for Aspose.GIS.dll -->