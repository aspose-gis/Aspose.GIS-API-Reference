---
title: "Classe DynamicFeature"
type: docs
weight: 650
url: /fr/python-net/aspose.gis/dynamicfeature/
---

**Summary:** A geographic feature composed of a geometry and user-defined attributes.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.DynamicFeature

**Inheritance:** Feature

**Aspose.PSD Version:** 25.9.0

## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| geometry | [IGeometry](/psd/python-net/aspose.gis.geometries/igeometry/) | r/w | Obtient ou définit la géométrie de l'entité.<br/>            Ne peut pas être <see langword=\"null\" />, utilisez [Geometry.null](/psd/python-net/aspose.gis.geometries/geometry/) pour indiquer une géométrie manquante. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [copy_values(input_feature)](#copy_values_input_feature_1) | Copie les valeurs des attributs d'une autre entité. |
| [get_as_node()](#get_as_node__2) | Obtient la fonctionnalité en tant que nœud. Cela peut être utile pour les données personnalisées |
| [get_value(attribute_name)](#get_value_attribute_name_3) | Obtient la valeur d'un attribut. |
| [get_value_or_default(attribute_name, default_value)](#get_value_or_default_attribute_name_default_value_4) | Obtient la valeur d'un attribut, ou [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) si la valeur n'est pas définie ou <c>null</c>. |
| [get_values(values, default_value)](#get_values_values_default_value_5) | Renvoie les valeurs de tous les attributs dans un tableau. |
| [get_values(values_count, default_value)](#get_values_values_count_default_value_6) | Renvoie les valeurs de tous les attributs dans un tableau. |
| [get_values_dump(default_value)](#get_values_dump_default_value_7) | Renvoie les valeurs de tous les attributs dans un tableau.<br/>            Envisagez d'utiliser la méthode Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) pour éviter une allocation mémoire supplémentaire. |
| [get_values_list(attribute_name, separator, count)](#get_values_list_attribute_name_separator_count_8) | Obtient les valeurs d'une séquence d'attributs sous forme de liste. |
| [is_value_null(attribute_name)](#is_value_null_attribute_name_9) | Détermine si l'attribut spécifié a été explicitement défini sur la valeur <c>null</c>. |
| [is_value_set(attribute_name)](#is_value_set_attribute_name_10) | Vérifie si la valeur de l'attribut est définie dans cette fonctionnalité. |
| [set_value(attribute_name, value)](#set_value_attribute_name_value_11) | Définit une nouvelle valeur pour un attribut. |
| [set_value_null(attribute_name)](#set_value_null_attribute_name_12) | Définit la valeur de l'attribut sur <c>null</c>. |
| [set_values(values)](#set_values_values_13) | Définit de nouvelles valeurs pour tous les attributs.<br/>            Envisagez également d'utiliser la méthode [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) pour simplifier la définition des valeurs en un seul appel. |
| [unset_value(attribute_name)](#unset_value_attribute_name_14) | Supprime la valeur de l'attribut de cette fonctionnalité. |


### Method: copy_values(input_feature) {#copy_values_input_feature_1}


```
 copy_values(input_feature) 
```

Copie les valeurs des attributs d'une autre entité.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| input_feature | [Feature](/psd/python-net/aspose.gis/feature) | La fonctionnalité dont il faut copier les valeurs. |

### Method: get_as_node() {#get_as_node__2}


```
 get_as_node() 
```

Obtient la fonctionnalité en tant que nœud. Cela peut être utile pour les données personnalisées

**Returns**

| Type | Description |
| :- | :- |
| [NodeLink](/psd/python-net/aspose.gis/nodelink) | Le NodeLink vers la fonctionnalité |


### Method: get_value(attribute_name) {#get_value_attribute_name_3}


```
 get_value(attribute_name) 
```

Obtient la valeur d'un attribut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Nom de l'attribut. |

**Returns**

| Type | Description |
| :- | :- |
| object | Valeur de l'attribut. |


### Method: get_value_or_default(attribute_name, default_value) {#get_value_or_default_attribute_name_default_value_4}


```
 get_value_or_default(attribute_name, default_value) 
```

Obtient la valeur d'un attribut, ou [FeatureAttribute.default_value](/psd/python-net/aspose.gis/featureattribute/) si la valeur n'est pas définie ou <c>null</c>.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Nom de l'attribut. |
| default_value | object | La valeur à retourner si la valeur de l'attribut est manquante. La valeur par défaut est <see langword="null" />. |

**Returns**

| Type | Description |
| :- | :- |
| object | Valeur de l'attribut. |


### Method: get_values(values, default_value) {#get_values_values_default_value_5}


```
 get_values(values, default_value) 
```

Renvoie les valeurs de tous les attributs dans un tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeurs | object | Le tableau dans lequel copier les valeurs des attributs. |
| default_value | object | La valeur à retourner si la valeur de l'attribut est manquante (non définie). La valeur par défaut est <see langword="null" />.<br/>            Envisagez d'utiliser '.Value' pour différencier les valeurs 'non définies' et '<see langword="null" />'. |

**Returns**

| Type | Description |
| :- | :- |
| int | Un nombre d'attributs copiés. |


### Method: get_values(values_count, default_value) {#get_values_values_count_default_value_6}


```
 get_values(values_count, default_value) 
```

Renvoie les valeurs de tous les attributs dans un tableau.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| values_count | int | Le nombre de valeurs. |
| default_value | object | La valeur à retourner si la valeur de l'attribut est manquante (non définie). La valeur par défaut est <see langword="null" />.<br/>            Envisagez d'utiliser '.Value' pour différencier les valeurs 'non définies' et '<see langword="null" />'. |

**Returns**

| Type | Description |
| :- | :- |
| object | Un nombre d'attributs copiés. |


### Method: get_values_dump(default_value) {#get_values_dump_default_value_7}


```
 get_values_dump(default_value) 
```

Renvoie les valeurs de tous les attributs dans un tableau.<br/>            Envisagez d'utiliser la méthode Aspose.Gis.DynamicFeature.GetValues(System.Object,System.Object) pour éviter une allocation mémoire supplémentaire.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| default_value | object | La valeur à retourner si la valeur de l'attribut est manquante (non définie). La valeur par défaut est <see langword="null" />.<br/>            Envisagez d'utiliser '.Value' pour différencier les valeurs 'non définies' et '<see langword="null" />'. |

**Returns**

| Type | Description |
| :- | :- |
| object | Un nouveau tableau dans lequel copier les valeurs des attributs. |


### Method: get_values_list(attribute_name, separator, count) {#get_values_list_attribute_name_separator_count_8}


```
 get_values_list(attribute_name, separator, count) 
```

Obtient les valeurs d'une séquence d'attributs sous forme de liste.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Nom de l'attribut. |
| separator | string | Une chaîne utilisée pour séparer le nom de l'attribut et la valeur d'index de la séquence. |
| nombre | int | Nombre de valeurs à retourner (les valeurs manquantes sont remplissées avec null) |

**Returns**

| Type | Description |
| :- | :- |
| object | Liste des valeurs des attributs dont les noms diffèrent selon la valeur d'index de la séquence. |


### Method: is_value_null(attribute_name) {#is_value_null_attribute_name_9}


```
 is_value_null(attribute_name) 
```

Détermine si l'attribut spécifié a été explicitement défini sur la valeur <c>null</c>.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Nom de l'attribut. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword="true" /> si la valeur de l'attribut est <c>null</c> ; sinon, <see langword="false" />. |


### Method: is_value_set(attribute_name) {#is_value_set_attribute_name_10}


```
 is_value_set(attribute_name) 
```

Vérifie si la valeur de l'attribut est définie dans cette fonctionnalité.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Nom de l'attribut. |

**Returns**

| Type | Description |
| :- | :- |
| bool | <see langword="true" /> si la valeur de l'attribut spécifié est définie ; sinon, <see langword="false" />. |


### Method: set_value(attribute_name, value) {#set_value_attribute_name_value_11}


```
 set_value(attribute_name, value) 
```

Définit une nouvelle valeur pour un attribut.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Le nom de l'attribut. |
| valeur | object | La valeur de l'attribut. |

### Method: set_value_null(attribute_name) {#set_value_null_attribute_name_12}


```
 set_value_null(attribute_name) 
```

Définit la valeur de l'attribut sur <c>null</c>.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Le nom de l'attribut. |

### Method: set_values(values) {#set_values_values_13}


```
 set_values(values) 
```

Définit de nouvelles valeurs pour tous les attributs.<br/>            Envisagez également d'utiliser la méthode [DynamicFeature.copy_values(input_feature)](/psd/python-net/aspose.gis/dynamicfeature/) pour simplifier la définition des valeurs en un seul appel.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| valeurs | object | Le tableau des nouvelles valeurs. |

**Returns**

| Type | Description |
| :- | :- |
| int | Le nombre de valeurs d'attribut définies. |


### Method: unset_value(attribute_name) {#unset_value_attribute_name_14}


```
 unset_value(attribute_name) 
```

Supprime la valeur de l'attribut de cette fonctionnalité.

**Parameters:**

| Paramètre | Type | Description |
| :- | :- | :- |
| attribute_name | string | Nom de l'attribut. |

