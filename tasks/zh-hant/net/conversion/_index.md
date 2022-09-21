---
translation: true
template: /templates/conversion_net.md
title: C# Microsoft Project 文件轉換 | .NET |產品.aspose.com
url: /net/conversion/
description: 通過 .NET 庫使用幾行 C# 代碼將 Microsoft Project MPP MPT MPX 轉換為 PDF HTML Excel 和圖像 JPG PNG BMP TIFF。
keywords: 任務轉換 api .net, 任務轉換 api .net, 任務轉換器 c# 集成
family: tasks
platformtag: net
feature: conversion
---

{{<section banner>}}
---
h1: "通過 C# 進行 Microsoft Project 文件轉換"
h2: "將 Microsoft Project MPP、MPT、MPX 轉換為 PDF、Excel、HTML 和圖像，包括 BMP、JPG、PNG、TIFF，以構建跨平台的 .NET 應用程序。"
---

{{<section overview>}}
---
p1: "Microsoft Project 應用程序旨在協助項目經理完成計劃、跟踪進度、分配資源和分析工作量。每當需要在公司 .NET 解決方案中處理 Microsoft Project MPP、MPT、MPX 文件而不安裝 Microsoft Project 時，.NET Project 文件處理 API 就可以完成所有這些工作。它可以輕鬆管理、創建、修改文檔以及轉換為其他文件。下面的代碼運行良好，可以輕鬆集成到解決方案中。"
---

{{<section feature1>}}
---
title: "Microsoft Project 到 PDF 轉換"
h3: "Microsoft Project 到 PDF 轉換的 C# 代碼"
---
Microsoft Project 到 PDF 的轉換，過程是，使用 [Project class](https://apireference.aspose.com/tasks/net/aspose.tasks/project) 加載 Microsoft Project 文件 MPP、MPT 或 MPX。調用 save 方法並以輸出 PDF 文件和 [SaveFileFormat](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/savefileformat) .PDF 作為參數。在轉換過程中，將呈現所有任務、資源和資源分配數據。

{{<section feature2>}}
---
title: "將 Microsoft Project 轉換為圖像 JPG、PNG、BMP、TIFF"
h3: "用於將 Microsoft Project 轉換為圖像格式的 C# 代碼"
---

將 Microsoft Project 文件 MPP、MPT、MPX 轉換為圖像格式幾乎相同，唯一的區別是 SaveFileFormat 擴展名和圖像格式。因此，只需使用 Project 類加載文件並調用 save 方法，同時將相關的輸出圖像格式和 SaveFileFormat 作為參數傳遞。如果需要額外的圖像設置，API 提供 [ImageSaveOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/imagesaveoptions) 以將渲染圖像保存為 JPG、PNG、BMP 或 TIFF 文件.

{{<section feature3>}}
---
title: "Microsoft Project 到 HTML 轉換"
h3: "Microsoft Project 到 HTML 轉換的 C# 代碼"
---

Microsoft Project 轉換為 HTML 的過程與 PDF 幾乎相同，唯一的區別是 SaveFileFormat HTML 擴展名。因此，只需使用 Project 類加載文件並調用 save 方法，同時將相關的輸出 HTML 文件和 SaveFileFormat.HTML 作為參數傳遞。

{{<section feature4>}}
---
title: "將 Microsoft Project 轉換為 Excel XLSX、CSV 文件"
h3: "Microsoft Project 到 CSV 轉換的 C# 代碼"
---

.NET MS Project Files API proivdes [XlsxOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/xlsxoptions) 用於將 Project 轉換為 XLSX 和 [CsvOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/csvoptions)用於將 MPP、MPT、MPX 轉換為 CSV 文件。開發人員可以通過使用這些類來指定相關選項。所有其他過程都相同。