---
title: "MultiStreamPath 클래스"
type: docs
weight: 2760
url: /ko/python-net/aspose.gis/multistreampath/
---

**Summary:** This class works with formats which contains several files.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.MultiStreamPath

**Inheritance:** AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **Description** |
| :- | :- |
| [MultiStreamPath(entry_file_name, file_names, streams)](#MultiStreamPath_entry_file_name_file_names_streams_1) | 새로운 [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) 클래스 인스턴스를 초기화합니다. |
## **Properties**
| **Name** | **Type** | **Access** | **Description** |
| :- | :- | :- | :- |
| location | string | r | 이 <c>AbstractPath</c>의 위치에 대한 문자열 표현을 가져옵니다. |
| separator | char | r | 디렉터리 수준을 구분하는 데 사용되는 구분 문자([MultiStreamPath.location](/psd/python-net/aspose.gis/multistreampath/) 문자열)를 가져옵니다. |
## **Methods**
| **Name** | **Description** |
| :- | :- |
| [combine(location)](#combine_location_1) | 이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)를 지정된 경로 구성 요소와 결합합니다. |
| delete() | 이 경로가 가리키는 파일을 삭제합니다. |
| [from_local_path(path)](#from_local_path_path_2) | 로컬 파일 시스템의 위치를 나타내는 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)를 생성합니다. |
| [from_stream(stream)](#from_stream_stream_3) | 스트림에서 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)를 생성합니다. |
| [get_extension()](#get_extension__4) | 이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)의 확장자를 반환합니다. |
| [get_file_name()](#get_file_name__5) | 이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)의 파일 이름과 확장자를 반환합니다. |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | 이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)의 파일 이름을 확장자 없이 반환합니다. |
| [is_file()](#is_file__7) | 이 경로가 읽기용으로 열 수 있는 기존 파일을 가리키는지 여부를 나타내는 값을 가져옵니다. |
| [list_directory()](#list_directory__8) | 디렉터리인 경우 이 <c>AbstractPath</c> 내부에 위치한 경로들을 반환합니다. |
| [open(access)](#open_access_9) | 데이터에 접근하기 위한 경로로서 여러 파일 형식의 스트리밍을 열 수 있는 집합을 추상화합니다. |
| [with_extension(new_extension)](#with_extension_new_extension_10) | 파일 확장자를 지정된 값으로 변경한 새로운 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)를 반환합니다. |


### Constructor: MultiStreamPath(entry_file_name, file_names, streams) {#MultiStreamPath_entry_file_name_file_names_streams_1}


```
 MultiStreamPath(entry_file_name, file_names, streams) 
```

새로운 [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) 클래스 인스턴스를 초기화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| entry_file_name | string | 엔트리 파일의 이름. |
| file_names | string | 파일 이름들. |
| streams | _io.BufferedRandom[] | 스트림들. |

### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)를 지정된 경로 구성 요소와 결합합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| location | string | 이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)에 추가할 경로 구성 요소. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)와 인수의 위치를 결합한 [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/)을 가리키는 새로운 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/).<br/>            인수. |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

로컬 파일 시스템의 위치를 나타내는 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| path | string | 로컬 파일 시스템의 경로, 예: <c>"C:\\file.shp"</c> 또는 <c>"D:\\directory\\"</c>. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | <paramref name="path" />에 정의된 위치를 나타내는 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)입니다. |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

스트림에서 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)를 생성합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| stream | _io.BufferedRandom | [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)를 생성하기 위한 스트림. <c>Aspose.GIS</c>는 스트림을 해제하지 않습니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 지정된 스트림을 내용으로 갖는 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) 인스턴스. |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)의 확장자를 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)의 확장자(점 "." 포함) 또는<br/>            확장자가 없을 경우 빈 문자열. |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)의 파일 이름과 확장자를 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | 마지막 [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) 문자 뒤의 문자열은 [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/)에 있습니다.<br/>            마지막 문자가 [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/)이면 빈 문자열을 반환합니다.<br/>            [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/)에 [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) 문자가 없으면 [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) 자체<br/>            반환됩니다. |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

이 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)의 파일 이름을 확장자 없이 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| string | [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/)가 반환하는 문자열에서 마지막 점과 그 뒤의 모든 문자를 제외한 문자열. |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

이 경로가 읽기용으로 열 수 있는 기존 파일을 가리키는지 여부를 나타내는 값을 가져옵니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| bool | 위치가 파일을 가리키면 <see langword="true" />; 그렇지 않으면 <see langword="false" />. |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

디렉터리인 경우 이 <c>AbstractPath</c> 내부에 위치한 경로들을 반환합니다.

**Returns**

| 형식 | 설명 |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | 이 <c>AbstractPath</c> 내부에 있는 경로. |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

데이터에 접근하기 위한 경로로서 여러 파일 형식의 스트리밍을 열 수 있는 집합을 추상화합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| 액세스 | System.IO.FileAccess | 스트림에서 수행할 수 있는 작업의 하위 집합을 지정합니다. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| _io.BufferedRandom | 이는 a   또는 클라이언트가 처음 전달한 스트림일 수 있습니다. |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

파일 확장자를 지정된 값으로 변경한 새로운 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)를 반환합니다.

**Parameters:**

| 매개변수 | 형식 | 설명 |
| :- | :- | :- |
| new_extension | string | 새로운 확장자. |

**Returns**

| 형식 | 설명 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 같은 디렉터리의 파일을 가리키지만 새로운 확장자를 가진 새로운 [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)입니다. |


