---
translation: true
template: /templates/conversion_net.md
title: C# Microsoft Project 文件转换 | .NET |产品.aspose.com
url: /net/conversion/
description: 通过 .NET 库使用几行 C# 代码将 Microsoft Project MPP MPT MPX 转换为 PDF HTML Excel 和图像 JPG PNG BMP TIFF。
keywords: 任务转换 api .net, 任务转换 api .net, 任务转换器 c# 集成
family: tasks
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: "通过 C# 进行 Microsoft Project 文件转换"
h2: "将 Microsoft Project MPP、MPT、MPX 转换为 PDF、Excel、HTML 和图像，包括 BMP、JPG、PNG、TIFF，以构建跨平台的 .NET 应用程序。"
---

{{<section overview>}}
---
p1: "Microsoft Project 应用程序旨在协助项目经理完成计划、跟踪进度、分配资源和分析工作量。每当需要在公司 .NET 解决方案中处理 Microsoft Project MPP、MPT、MPX 文件而不安装 Microsoft Project 时，.NET Project 文件处理 API 就可以完成所有这些工作。它可以轻松管理、创建、修改文档以及转换为其他文件。下面的代码运行良好，可以轻松集成到解决方案中。"
---

{{<section feature1>}}
---
title: "Microsoft Project 到 PDF 转换"
h3: "Microsoft Project 到 PDF 转换的 C# 代码"
---
Microsoft Project 到 PDF 的转换，过程是，使用 [Project class](https://apireference.aspose.com/tasks/net/aspose.tasks/project) 加载 Microsoft Project 文件 MPP、MPT 或 MPX。调用 save 方法并以输出 PDF 文件和 [SaveFileFormat](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/savefileformat) .PDF 作为参数。在转换过程中，将呈现所有任务、资源和资源分配数据。

{{<section feature2>}}
---
title: "将 Microsoft Project 转换为图像 JPG、PNG、BMP、TIFF"
h3: "用于将 Microsoft Project 转换为图像格式的 C# 代码"
---

将 Microsoft Project 文件 MPP、MPT、MPX 转换为图像格式几乎相同，唯一的区别是 SaveFileFormat 扩展名和图像格式。因此，只需使用 Project 类加载文件并调用 save 方法，同时将相关的输出图像格式和 SaveFileFormat 作为参数传递。如果需要额外的图像设置，API 提供 [ImageSaveOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/imagesaveoptions) 以将渲染图像保存为 JPG、PNG、BMP 或 TIFF 文件.

{{<section feature3>}}
---
title: "Microsoft Project 到 HTML 转换"
h3: "Microsoft Project 到 HTML 转换的 C# 代码"
---

Microsoft Project 转换为 HTML 的过程与 PDF 几乎相同，唯一的区别是 SaveFileFormat HTML 扩展名。因此，只需使用 Project 类加载文件并调用 save 方法，同时将相关的输出 HTML 文件和 SaveFileFormat.HTML 作为参数传递。

{{<section feature4>}}
---
title: "将 Microsoft Project 转换为 Excel XLSX、CSV 文件"
h3: "Microsoft Project 到 CSV 转换的 C# 代码"
---

.NET MS Project Files API proivdes [XlsxOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/xlsxoptions) 用于将 Project 转换为 XLSX 和 [CsvOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/csvoptions)用于将 MPP、MPT、MPX 转换为 CSV 文件。开发人员可以通过使用这些类来指定相关选项。所有其他过程都相同。