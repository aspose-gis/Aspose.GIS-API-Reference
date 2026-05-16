---
title: "MultiStreamPath クラス"
type: docs
weight: 2760
url: /ja/python-net/aspose.gis/multistreampath/
---

**Summary:** This class works with formats which contains several files.

**Module:** [aspose.gis](/psd/python-net/aspose.gis/)

**Full Name:** aspose.gis.MultiStreamPath

**Inheritance:** AbstractPath

**Aspose.PSD Version:** 25.9.0

## **Constructors**
| **Name** | **説明** |
| :- | :- |
| [MultiStreamPath(entry_file_name, file_names, streams)](#MultiStreamPath_entry_file_name_file_names_streams_1) | 新しい [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) クラスのインスタンスを初期化します。 |
## **Properties**
| **Name** | **Type** | **Access** | **説明** |
| :- | :- | :- | :- |
| location | string | r | この <c>AbstractPath</c> の場所の文字列表現を取得します。 |
| separator | char | r | ディレクトリ階層を区切るために使用される区切り文字を取得します（[MultiStreamPath.location](/psd/python-net/aspose.gis/multistreampath/) 文字列）。 |
## **Methods**
| **Name** | **説明** |
| :- | :- |
| [combine(location)](#combine_location_1) | この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) と指定されたパスコンポーネントを結合します。 |
| delete() | このパスが指すファイルを削除します。 |
| [from_local_path(path)](#from_local_path_path_2) | ローカルファイルシステム上の場所を表す [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) を作成します。 |
| [from_stream(stream)](#from_stream_stream_3) | ストリームから [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) を作成します。 |
| [get_extension()](#get_extension__4) | この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) の拡張子を返します。 |
| [get_file_name()](#get_file_name__5) | この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) のファイル名と拡張子を返します。 |
| [get_file_name_without_extension()](#get_file_name_without_extension__6) | この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) の拡張子なしのファイル名を返します。 |
| [is_file()](#is_file__7) | このパスが既存のファイルを指し、読み取り用に開くことができるかどうかを示す値を取得します。 |
| [list_directory()](#list_directory__8) | この <c>AbstractPath</c> がディレクトリの場合、その内部にあるパスを返します。 |
| [open(access)](#open_access_9) | データにアクセスするためのパスとして、オープンストリーミングのマルチファイル形式のセットを抽象化します。 |
| [with_extension(new_extension)](#with_extension_new_extension_10) | ファイル拡張子が指定された値に変更された新しい [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) を返します。 |


### Constructor: MultiStreamPath(entry_file_name, file_names, streams) {#MultiStreamPath_entry_file_name_file_names_streams_1}


```
 MultiStreamPath(entry_file_name, file_names, streams) 
```

新しい [MultiStreamPath](/psd/python-net/aspose.gis/multistreampath/) クラスのインスタンスを初期化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| entry_file_name | string | エントリーファイルの名前です。 |
| file_names | string | ファイル名です。 |
| streams | _io.BufferedRandom[] | ストリームです。 |

### Method: combine(location) {#combine_location_1}


```
 combine(location) 
```

この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) と指定されたパスコンポーネントを結合します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| location | string | この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) に追加するパスコンポーネントです。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) と<br/>            引数の場所を組み合わせた [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) を指す新しい [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)です。 |


### Method: from_local_path(path)  [static] {#from_local_path_path_2}


```
 from_local_path(path) 
```

ローカルファイルシステム上の場所を表す [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| path | string | ローカルファイルシステム上のパスで、例えば <c>\"C:\\\\file.shp\"</c> や <c>\"D:\\\\directory\\\\\"</c> のようなものです。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | <paramref name="path" /> で定義された場所を表す [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) です。 |


### Method: from_stream(stream)  [static] {#from_stream_stream_3}


```
 from_stream(stream) 
```

ストリームから [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) を作成します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| stream | _io.BufferedRandom | [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) を作成するためのストリームです。<c>Aspose.GIS</c> はストリームを破棄しません。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 指定されたストリームを内容とする [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) のインスタンスです。 |


### Method: get_extension() {#get_extension__4}


```
 get_extension() 
```

この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) の拡張子を返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| string | この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) の拡張子（ピリオド「.」を含む）または<br/>            拡張子がない場合は空文字列です。 |


### Method: get_file_name() {#get_file_name__5}


```
 get_file_name() 
```

この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) のファイル名と拡張子を返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| string | この [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) における最後の [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) 文字の後の文字列です。もし<br/>            最後の文字が [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) 文字である場合、空文字列が返されます。もし<br/>            [AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) に [AbstractPath.separator](/psd/python-net/aspose.gis/abstractpath/) 文字が存在しない場合、[AbstractPath.location](/psd/python-net/aspose.gis/abstractpath/) 自体が<br/>            返されます。 |


### Method: get_file_name_without_extension() {#get_file_name_without_extension__6}


```
 get_file_name_without_extension() 
```

この [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) の拡張子なしのファイル名を返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| string | [AbstractPath.get_file_name()](/psd/python-net/aspose.gis/abstractpath/) が返す文字列から、最後のピリオドとそれ以降のすべての文字を除いたものです。 |


### Method: is_file() {#is_file__7}


```
 is_file() 
```

このパスが既存のファイルを指し、読み取り用に開くことができるかどうかを示す値を取得します。

**Returns**

| 型 | 説明 |
| :- | :- |
| bool | 場所がファイルを指す場合は <see langword="true" />、それ以外の場合は <see langword="false" /> です。 |


### Method: list_directory() {#list_directory__8}


```
 list_directory() 
```

この <c>AbstractPath</c> がディレクトリの場合、その内部にあるパスを返します。

**Returns**

| 型 | 説明 |
| :- | :- |
| System.Collections.Generic.IEnumerable<AbstractPath> | この <c>AbstractPath</c> 内にあるパスです。 |


### Method: open(access) {#open_access_9}


```
 open(access) 
```

データにアクセスするためのパスとして、オープンストリーミングのマルチファイル形式のセットを抽象化します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| アクセス | System.IO.FileAccess | ストリームで実行できる操作のサブセットを指定します。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| _io.BufferedRandom | これは、   またはクライアントが元々渡したストリームのいずれかです。 |


### Method: with_extension(new_extension) {#with_extension_new_extension_10}


```
 with_extension(new_extension) 
```

ファイル拡張子が指定された値に変更された新しい [AbstractPath](/psd/python-net/aspose.gis/abstractpath/) を返します。

**Parameters:**

| パラメーター | 型 | 説明 |
| :- | :- | :- |
| new_extension | string | 新しい拡張子です。 |

**Returns**

| 型 | 説明 |
| :- | :- |
| [AbstractPath](/psd/python-net/aspose.gis/abstractpath) | 同じディレクトリ内のファイルを指し、しかし新しい拡張子を持つ新しい [AbstractPath](/psd/python-net/aspose.gis/abstractpath/)です。 |


