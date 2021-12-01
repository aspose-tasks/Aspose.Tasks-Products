---
title: C# Microsoft Project Files Conversion
url: /net/conversion/
description: Convert Microsoft Project MPP MPT MPX to PDF HTML Excel and Images JPG PNG BMP TIFF SVG with few lines of C# code via .NET library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Project Files Conversion Via C#" h2="Convert Microsoft<sup>&reg;</sup> Project MPP, MPT, MPX to PDF, Excel, HTML and Images including BMP, JPG, PNG, TIFF to build cross-platform .NET applications." >}}

{{% blocks/products/pf/feature-page-summary %}}


Microsoft Project application is to assist project managers for complete planning, tracking progress, assigning resources and analyzing workloads. And whenever there is need to handle Microsoft Project MPP, MPT, MPX files within company .NET solution without installing  Microsoft Project, .NET Project file handling API is there to do all this. It can easily manage, create, modify documents as well as convert to other files. Below code works perfactly well and can easily be integrated within the solution.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Project to PDF Conversion" %}}

Microsoft Project to PDF conversion, Process is, Load the Microsoft Project file MPP, MPT or MPX using [Project class](https://apireference.aspose.com/tasks/net/aspose.tasks/project). Call the save method and with output PDF file and [SaveFileFormat](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/savefileformat).PDF as parameters. Dureing conversion process all the tasks, resources, and resource assignment data will be rendered.

{{% blocks/products/pf/feature-page-code h3="C# Code for Microsoft Project to PDF Conversion" %}}

``cs
// load the Project MPP file to be converted

var mpptopdf = new Project(dir + "sourceFile.mpp");

// Save Project MPP to PDF

mpptopdf.Save(dir + "output.pdf", SaveFileFormat.PDF);
``

{{< gist "aspose-com-gists" "0484545ed20cb073e4bcf7ce894343f0" "convert-project-mpp-to-pdf.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mpp-to-pdf mpt-to-pdf mpx-to-pdf" >}}
{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft Project to Images JPG, PNG, BMP, TIFF" %}}

Converting Microsoft Project files MPP, MPT, MPX to image formats is almost same, the only difference is SaveFileFormat extension and image format. So Just load the file using Project class and call the save method while passing the relevant output image format and SaveFileFormat as parameters. If there is need for additional Image settings, API provides [ImageSaveOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/imagesaveoptions) to save rendered images in JPG, PNG, BMP or TIFF files.


{{% blocks/products/pf/feature-page-code h3="C# Code for Converting Microsoft Project to Image Formats" %}}

{{< gist "aspose-com-gists" "0484545ed20cb073e4bcf7ce894343f0" "convert-project-mpp-to-images.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mpp-to-bmp mpp-to-png mpp-to-jpeg mpp-to-tiff mpx-to-bmp mpx-to-png mpx-to-jpeg mpx-to-tiff mpt-to-bmp mpt-to-png mpt-to-jpeg mpt-to-tiff" >}}

{{% blocks/products/pf/feature-page-section  h2="Microsoft Project to HTML Conversion" %}}

Process of conversion of Microsoft Project to HTML is almost same as of PDF, the only difference is SaveFileFormat HTML extension. So Just load the file using Project class and call the save method while passing the relevant output HTML file and SaveFileFormat.HTML as parameters.

{{% blocks/products/pf/feature-page-code h3="C# Code for Microsoft Project to HTML Conversion" %}}

{{< gist "aspose-com-gists" "0484545ed20cb073e4bcf7ce894343f0" "convert-project-mpp-to-html.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mpp-to-html mpt-to-html mpx-to-html xml-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft Project to Excel XLSX, CSV File" %}}

.NET MS Project Files API proivdes [XlsxOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/xlsxoptions) for converting Project to XLSX and [CsvOptions](https://apireference.aspose.com/tasks/net/aspose.tasks.saving/csvoptions) for converting MPP, MPT, MPX to CSV files. Developers can specify relevant options by using these classes. All other process is same. 

{{% blocks/products/pf/feature-page-code h3="C# Code for Microsoft Project to CSV Conversion" %}}

{{< gist "aspose-com-gists" "0484545ed20cb073e4bcf7ce894343f0" "convert-project-mpp-to-csv.cs" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mpp-to-csv mpt-to-csv mpx-to-csv mpx-to-xlsx mpt-to-xlsx mpp-to-xlsx" >}}