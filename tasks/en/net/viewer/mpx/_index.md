---
title: View MPX File Formats via .NET 
weight: 1390
url: /net/viewer/mpx/ 
description: C# source code to load, render and display MPX documents on .NET Framework, Mono and COM Interop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="MPX File Viewer for .NET" h2="View Microsoft Project MPX files in any browser without requiring Project application or Office Automation." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/tasks/aspose_tasks-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MPX" pfName="Aspose.Tasks" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="HTML" fileiconsmall2="JPG" fileiconsmall3="PDF" fileiconsmall4="XML" fileiconsmall5="MPX" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Tasks " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/tasks/aspose_tasks-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-tasks" liveDemosLink="https://products.aspose.app/tasks/family" docsLink="https://docs.aspose.com/tasks/net" installationsDocsLink="https://docs.aspose.com/tasks/net" nugetLink="https://www.nuget.org/packages/aspose.tasks" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/tasks/net" learnAsLink="https://docs.aspose.com/tasks/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to View MPX File Using C#" %}}

 In order to view MPX file, we’ll use
 [Aspose.Tasks for .NET](https://products.aspose.com/tasks/net) 
 API which is a feature-rich, powerful and easy to use API for C# platform to be used with any Viewer. Open
 [NuGet](https://www.nuget.org/packages/aspose.tasks) 
 package manager, search for
 **Aspose.Tasks** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Package Manager Console Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Tasks

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to View MPX via C#" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Tasks makes it easy for the developers to view the MPX file with just few lines of code.

{{% /blocks/products/pf/agp/text %}}

1.  Load MPX file with Project class
1.  Call the Project.Save method with HtmlSaveOptions as parameters
1.  Load resultant HTML in default browser with Process.Start

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Tasks for .NET is supported on all major operating systems. Just make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, Mono and COM Interop
-  Development environment like Microsoft Visual Studio
-  Aspose.Tasks for .NET referenced in your project

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="C# code to view MPX" offSpacer="" %}}

```cs

// load MPX file in an instance of Project
var project = new Tasks.Project("template.mpx");
// create an instance of HtmlSaveOptions
var option = new Tasks.Saving.HtmlSaveOptions();
// convert MPX file to HTML format
project.Save(output, option);
// load resultant HTML in default browser
System.Diagnostics.Process.Start(output);

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Tasks for .NET API" %}}

 Aspose.Tasks is a Microsoft Project API to view and convert project documents. One can load, create, modify and render Microsoft Project files to Primavera, Excel, PDF, HTML, images and XML formats. Aspose.Tasks is a standalone API and does not require Microsoft Project or any other software to be installed.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Free App to View MPX" sectionDescription="Check our live demos to [View MPX](https://products.aspose.app/tasks/viewer/mpx) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write or compile code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload MPX file and hit the \"View\" button" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Download MPX file from the link, if required" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MPX" readMoreLink="https://docs.fileformat.com/project-management/mpx/" >}}
MPX, Microsoft Exchange File Format, is an ASCII file format for transferring of project information between Microsoft Project (MSP) and other applications that support the MPX file format such as Primavera Project Planner, Sciforma and Timerline Precision Estimating. The MPX file format allows you to transfer project information that cannot appear in a table, such as detailed resource assignment information, calendar information, or information in the Project Info dialog box.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Viewer Formats" subTitle="Using C#, One can also view many other file formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/tasks/net/viewer/mpp/" name="MPP" description="Microsoft Project Data File" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/tasks/net/viewer/mpt/" name="MPT" description="Microsoft Project Template Files" >}}
{{< blocks/products/pf/agp/other-supported-section-item href="https://products.aspose.com/tasks/net/viewer/xml/" name="XML" description="Extensible Markup Language" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}