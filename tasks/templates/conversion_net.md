---
template: true
title: {{i18n.title}}
description: {{i18n.description}}
url: {{i18n.url}}
family: tasks
platformtag: net
feature: conversion
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true" >}}
{{< blocks/products/pf/agp/upper-banner-autogen h1="{{i18n.banner.h1}}" h2="{{i18n.banner.h2}}">}}

{{< blocks/products/pf/main-container pfName="Aspose.Tasks" subTitlepfName="for .NET" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/tasks/aspose_tasks-for-net.svg" liveDemosLink="https://products.aspose.app/tasks/applications" PricingLink="https://purchase.aspose.com/pricing/tasks/net" buyLink="https://purchase.aspose.com/buy" docsLink="https://docs.aspose.com/tasks/net/" installationsDocsLink="https://docs.aspose.com/tasks/net/installation/" nugetLink="https://www.nuget.org/packages/Aspose.Tasks/" nugetPackageName="Aspose.Tasks" mavenRepoLink="" directDownloadLink="https://releases.aspose.com/tasks/net/" >}}

{{% blocks/products/pf/agp/content %}}
{{i18n.overview.p1}}

{{% blocks/products/pf/feature-page-section  h2="{{i18n.feature1.title}}" %}}

{{i18n.feature1}}

<h3>{{i18n.feature1.h3}}</h3>

```cs
1. // load the file to be converted

2. var prjectToHTML = new Project(dir + "template.mpp");

3. // save in different formats

4. prjectToHTML.Save(dir + "output.html", SaveFileFormat.HTML);
```

<div class="container"><div class="row other-converters"><div class="col-md-2 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpp-to-pdf/">MPP to PDF</a></div><div class="col-md-2 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpt-to-pdf/">MPT to PDF</a></div><div class="col-md-2 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpx-to-pdf/">MPX to PDF</a></div></div><br/></div>

<h2>{{i18n.feature2.title}}</h2>

{{i18n.feature2}}

<h3>{{i18n.feature2.h3}}</h3> 

```cs
1. // load project file

2. var projectToImages = new Project(dir + "template.mpp");

3. // create ImageSaveOptions with desired Image format currently MPP to JPG

4. var ImageOptions = new ImageSaveOptions(Aspose.Tasks.Saving.SaveFileFormat.JPEG)

5.  {
    CustomPageSize = new SizeF(2200, 1100),
    HorizontalResolution = 96f,
    VerticalResolution = 96f,

    JpegQuality = 70

    };

6. // render data to image format

7. projectToImages.Save(dir + "output.jpg", ImageOptions);
```

<div class="container"><div class="row other-converters"><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpp-to-bmp/">MPP to BMP</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpp-to-png/">MPP to PNG</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpp-to-jpeg/">MPP to JPEG</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpp-to-tiff/">MPP to TIFF</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpx-to-bmp/">MPX to BMP</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpx-to-png/">MPX to PNG</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpx-to-jpeg/">MPX to JPEG</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpx-to-tiff/">MPX to TIFF</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpt-to-bmp/">MPT to BMP</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpt-to-png/">MPT to PNG</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpt-to-jpeg/">MPT to JPEG</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpt-to-tiff/">MPT to TIFF</a></div></div><br/></div>

<h2>{{i18n.feature3.title}}</h2>

{{i18n.feature3}}

<h3>{{i18n.feature3.h3}}</h3>

```cs
1. // Read the input Project MPP file
2. Project projectToCSV = new Project("Project.mpp");

3. // Initialize CsvOptions class instance
4. Aspose.Tasks.Saving.CsvOptions CSVOpts = new Aspose.Tasks.Saving.CsvOptions();
5. CSVOpts.TextDelimiter = Aspose.Tasks.Saving.CsvTextDelimiter.Semicolon;

6. // Save output CSV file
7. projectToCSV.Save("output.csv", CSVOpts);
```

<div class="container"><div class="row other-converters"><div class="col-md-2 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpp-to-html/">MPP to HTML</a></div><div class="col-md-2 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpt-to-html/">MPT to HTML</a></div><div class="col-md-2 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpx-to-html/">MPX to HTML</a></div><div class="col-md-2 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/xml-to-html/">XML to HTML</a></div></div><br/></div>

<h2>{{i18n.feature4.title}}</h2>

{{i18n.feature4}}

<h3>{{i18n.feature4.h3}}</h3>

```cs
1. // load the file to be converted

2. var prjectToHTML = new Project(dir + "template.mpp");

3. // save in different formats

4. prjectToHTML.Save(dir + "output.html", SaveFileFormat.HTML);
```
<div class="container"><div class="row other-converters"><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpp-to-csv/">MPP to CSV</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpt-to-csv/">MPT to CSV</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpx-to-csv/">MPX to CSV</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpx-to-xlsx/">MPX to XLSX</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpt-to-xlsx/">MPT to XLSX</a></div><div class="col-md-3 other-converter remove-lp remove-rp"><a href="/tasks/net/conversion/mpp-to-xlsx/">MPP to XLSX</a></div></div></div>