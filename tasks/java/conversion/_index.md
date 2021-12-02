---
title: Java Microsoft Project Files Conversion
url: /java/conversion/
description: Convert Microsoft Project MPP MPT MPX to HTML PDF Excel and JPG PNG BMP TIFF Images via Java library.
---

{{< blocks/products/pf/feature-page-wrap >}}
{{< blocks/products/pf/feature-page-header h1="Microsoft<sup>&reg;</sup> Project Files Conversion Via Java" h2="Convert Microsoft<sup>&reg;</sup> Project MPP, MPT, MPX to Excel, PDF, HTML and BMP, JPG, PNG, TIFF Images to build cross-platform Java applications." >}}

{{% blocks/products/pf/feature-page-summary %}}


Project managers use Microsoft Project for planning, assigning resources, tracking progress and analyzing workloads. Java Project API facilitates for handling Microsoft Project MPP, MPT, MPX files as well as converting these files to other formats  without its installation within Java application. After including the API, write just few lines of code and run the application to manage, create, modify MS Proct files. Below code works perfactly well.

{{% /blocks/products/pf/feature-page-summary  %}}

{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft Project to PDF Files" %}}

Java API provides [Project class](https://apireference.aspose.com/tasks/java/com.aspose.tasks/Project) for loading Microsoft Project MPP, MPT or MPX files. Load the file using it and call the [save method](https://apireference.aspose.com/tasks/java/com.aspose.tasks/project#save(java.lang.String,int)) having output PDF file and SaveFileFormat.PDF as parameters. [SaveFileFormat](https://apireference.aspose.com/tasks/java/com.aspose.tasks/SaveFileFormat) enumeration for saving project format choice and PDF currently as of our choice.

{{% blocks/products/pf/feature-page-code h3="Java Code for Microsoft Project to PDF Conversion" %}}

{{< gist "aspose-com-gists" "217f0999451404991cca03101961f026" "project-mpp-to-pdf-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mpp-to-pdf mpt-to-pdf mpx-to-pdf" >}}
{{% blocks/products/pf/feature-page-section  h2="Microsoft Project to  JPG, PNG, BMP, TIFF Images Conversion" %}}

Conversion process is similar to PDF, loading the file, calling the save method with appropriate parameters like image output file and SaveFileFormat with relevant image selection. If there is need for specific image settings such as vertical resolution, type of compression to apply and page numbers etc., API provides [ImageSaveOptions class](https://apireference.aspose.com/tasks/java/com.aspose.tasks/ImageSaveOptions) for the required JPG, PNG, BMP or TIFF settings.

{{% blocks/products/pf/feature-page-code h3="Java Code for Converting Microsoft Project to Image Formats" %}}

{{< gist "aspose-com-gists" "217f0999451404991cca03101961f026" "project-mpp-to-images-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mpp-to-bmp mpp-to-png mpp-to-jpeg mpp-to-tiff mpx-to-bmp mpx-to-png mpx-to-jpeg mpx-to-tiff mpt-to-bmp mpt-to-png mpt-to-jpeg mpt-to-tiff" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft Project to HTML File" %}}

As of similarity of conversion process, HTML rendering can be done via providing SaveFileFormat HTML extension and HTML file as parameters within save method. Moreover, API provides [HtmlSaveOptions](https://apireference.aspose.com/tasks/java/com.aspose.tasks/HtmlSaveOptions) class for specific settings like css, fonts, export image options and more.

{{% blocks/products/pf/feature-page-code h3="Java Code for Microsoft Project to HTML Conversion" %}}

{{< gist "aspose-com-gists" "217f0999451404991cca03101961f026" "project-mpp-to-html-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mpp-to-html mpt-to-html mpx-to-html xml-to-html" >}}

{{% blocks/products/pf/feature-page-section  h2="Convert Microsoft Project to Excel XLSX, CSV File" %}}

Java MS Project API also facilitate to export data to  CSV, TXT and Excel XLSX formats. With the use of relevant SaveFileFormat save format, process of converions is almost same or use the API specific format classes [CsvOptions](https://apireference.aspose.com/tasks/java/com.aspose.tasks/CsvOptions), [Spreadsheet2003SaveOptions](https://apireference.aspose.com/tasks/java/com.aspose.tasks/Spreadsheet2003SaveOptions),  [XlsxOptions](https://apireference.aspose.com/tasks/java/com.aspose.tasks/XlsxOptions) and including the options as parameter within save method.

Other then the above conversions, API also suuports saving MS Project files to other formats and provides relevant classes such as [XpsOptions](https://apireference.aspose.com/tasks/java/com.aspose.tasks/XpsOptions), [PrimaveraSaveOptions](https://apireference.aspose.com/tasks/java/com.aspose.tasks/PrimaveraSaveOptions), [PrimaveraXmlSaveOptions](https://apireference.aspose.com/tasks/java/com.aspose.tasks/PrimaveraXmlSaveOptions) etc.
 

{{% blocks/products/pf/feature-page-code h3="Java Code for Microsoft Project to XLSX, Spreadsheet2003 Conversion" %}}

{{< gist "aspose-com-gists" "217f0999451404991cca03101961f026" "project-mpp-to-xlsx-spreadsheet2003-conversion.java" >}}

{{% /blocks/products/pf/feature-page-code  %}}

{{% /blocks/products/pf/feature-page-section %}}
{{< blocks/products/pf/feature-page-options pairs="mpp-to-csv mpt-to-csv mpx-to-csv mpx-to-xlsx mpt-to-xlsx mpp-to-xlsx" >}}