---
translation: true
template: /templates/conversion_net.md
title: C# Microsoft Project ファイルの変換 | .NET | products.aspose.com
url: /net/conversion/
description: Microsoft Project MPP MPT MPX を PDF HTML Excel および画像 JPG PNG BMP TIFF に変換するには、.NET ライブラリを介して数行の C# コードを使用します。
keywords: タスク変換 api .net、タスク変換 api .net、タスク コンバーター c# 統合
family: tasks
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: "C# による Microsoft Project ファイルの変換"
h2: "Microsoft Project MPP、MPT、MPX を PDF、Excel、HTML、および BMP、JPG、PNG、TIFF を含む画像に変換して、クロスプラットフォームの .NET アプリケーションを構築します。"
---

{{<section overview>}}
---
p1: "Microsoft Project アプリケーションは、プロジェクト マネージャーが完全な計画、進捗状況の追跡、リソースの割り当て、ワークロードの分析を支援することを目的としています。また、Microsoft Project をインストールせずに会社の .NET ソリューション内で Microsoft Project MPP、MPT、MPX ファイルを処理する必要がある場合はいつでも、.NET Project ファイル処理 API を使用してこれらすべてを実行できます。ドキュメントの管理、作成、変更、および他のファイルへの変換を簡単に行うことができます。以下のコードは完全に機能し、ソリューション内に簡単に統合できます。"
---

{{<section feature1>}}
---
title: "Microsoft Project から PDF への変換"
h3: "Microsoft Project から PDF への変換用の C# コード"
---
Microsoft Project から PDF への変換、プロセスは、[Project クラス](https://apireference.aspose.com/tasks/net/aspose.tasks/project) を使用して、Microsoft Project ファイル MPP、MPT、または MPX を読み込みます。 save メソッドを呼び出し、出力 PDF ファイルと [SaveFileFormat](https://apireference.aspose.com/tasks/net/aspose.tasks.Saving/savefileformat) .PDF をパラメーターとして使用します。変換プロセス中に、すべてのタスク、リソース、およびリソース割り当てデータがレンダリングされます。

{{<section feature2>}}
---
title: "Microsoft Project を画像 JPG、PNG、BMP、TIFF に変換"
h3: "Microsoft Project を画像形式に変換するための C# コード"
---

Microsoft Project ファイル MPP、MPT、MPX を画像形式に変換する方法はほとんど同じです。唯一の違いは、SaveFileFormat 拡張子と画像形式です。そのため、Project クラスを使用してファイルをロードし、関連する出力画像形式と SaveFileFormat をパラメーターとして渡しながら、save メソッドを呼び出すだけです。追加の画像設定が必要な場合、API は [ImageSaveOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.Saving/imagesaveoptions) を提供し、レンダリングされた画像を JPG、PNG、BMP、または TIFF ファイルに保存します。 .

{{<section feature3>}}
---
title: "Microsoft Project から HTML への変換"
h3: "Microsoft Project から HTML への変換用の C# コード"
---

Microsoft Project から HTML への変換プロセスは PDF とほぼ同じですが、SaveFileFormat HTML 拡張子のみが異なります。そのため、Project クラスを使用してファイルをロードし、関連する出力 HTML ファイルと SaveFileFormat.HTML をパラメーターとして渡しながら、save メソッドを呼び出すだけです。

{{<section feature4>}}
---
title: "Microsoft Project を Excel XLSX、CSV ファイルに変換する"
h3: "Microsoft Project から CSV への変換用の C# コード"
---

Project を XLSX に変換するための .NET MS Project Files API の [XlsxOptions](https://apireference.aspose.com/tasks/net/aspose.tasks. Saving/xlsxoptions) および [CsvOptions](https://apireference.aspose) .com/tasks/net/aspose.tasks. Saving/csvoptions) を参照して、MPP、MPT、MPX を CSV ファイルに変換します。開発者は、これらのクラスを使用して関連するオプションを指定できます。他のすべてのプロセスは同じです。