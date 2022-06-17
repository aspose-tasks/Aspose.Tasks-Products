---
title: Edit or View MPP Document Metadata via C++ 
weight: 1090
url: /cpp/metadata/mpp/ 
description: C++ example code to edit or view MPP file metadata on C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extract MPP Metadata via C++" h2="Build your own C++ apps to add, edit, remove or extract metadata from MPP files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/tasks/aspose_tasks-for-cpp.svg" sourceAdditionalConversionTag="" additionalConversionTag="MPP" pfName="Aspose.Tasks" subTitlepfName="for C++" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Tasks " subTitlepfName="for C++" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/tasks/aspose_tasks-for-cpp.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-tasks" liveDemosLink="https://products.aspose.app/tasks/family" docsLink="https://docs.aspose.com/tasks/cpp" installationsDocsLink="https://docs.aspose.com/tasks/cpp" nugetLink="https://www.nuget.org/packages/aspose.tasks" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/tasks/cpp" learnAsLink="https://docs.aspose.com/tasks/cpp" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Get MPP Metadata Using C++" %}}

 In order to extract MPP metadata, we’ll use
 [Aspose.Tasks for C++](https://products.aspose.com/tasks/cpp) 
 API which is a feature-rich, powerful and easy to use document metadata extraction API for C++ platform. You can download its latest version directly, just open
 [NuGet](https://www.nuget.org/packages/aspose.tasks) 
 package manager, search for
 **Aspose.Tasks.Cpp** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Tasks.Cpp

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Extract Metadata of MPP via C++" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

+  Load MPP file
+  Use methods like DefaultTaskType, DefaultStandardRate for required properties
+  Print properties

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Tasks for C++ supports on all major platforms and Operating Systems. Please make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with C++ Runtime Environment for Windows 32 bit, Windows 64 bit and Linux 64 bit.
-  Aspose.Tasks for C++ DLL referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extract Metadata of MPP - C++" offSpacer="" %}}

```cs

// Create project
System::SharedPtr<Project> project = System::MakeObject<Project>(dataDir + u"DefaultProperties.mpp");
    
// Display default properties
System::Console::WriteLine(System::String(u"New Task Default Start: ") + project->Get<System::DateTime>(Prj::DefaultStartTime()).ToShortDateString());
System::Console::WriteLine(System::String(u"New Task Default Type: ") + System::ObjectExt::ToString(project->Get<TaskType>(Prj::DefaultTaskType())));
System::Console::WriteLine(System::String(u"Resouce Default Standard Rate: ") + System::Convert::ToString(project->Get<double>(Prj::DefaultStandardRate())));
System::Console::WriteLine(System::String(u"Resource Default Overtime Rate: ") + System::Convert::ToString(project->Get<double>(Prj::DefaultOvertimeRate())));
System::Console::WriteLine(System::String(u"Default Task EV Method: ") + System::ObjectExt::ToString(project->Get<EarnedValueMethodType>(Prj::DefaultTaskEVMethod())));
System::Console::WriteLine(System::String(u"Default Cost Accrual: ") + System::ObjectExt::ToString(project->Get<CostAccrualType>(Prj::DefaultFixedCostAccrual())));  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Tasks for C++ API" %}}

 Aspose.Tasks is a Microsoft Project API to view and convert project documents. One can load, create, modify and render Microsoft Project files to Primavera, Excel, PDF, HTML, images and XML formats. Aspose.Tasks is a standalone API and does not require Microsoft Project or any other software to be installed.  



    {{% /blocks/products/pf/agp/content %}}

    {{< blocks/products/pf/agp/about-file-section >}}

        {{< blocks/products/pf/agp/demobox sectionTitle="Extract Metadata of MPP via Online App" sectionDescription="View & edit Metadata to MPP documents by using our [Live Demos](https://products.aspose.app/tasks/metadata) with following benefits." >}}
            {{< blocks/products/pf/agp/democard icon="fa-cogs" text=" No need to download or setup anything" >}}
            {{< blocks/products/pf/agp/democard icon="fa-edit" text=" No need to write any code" >}}
            {{< blocks/products/pf/agp/democard icon="fa-file-text" text=" Just upload your MPP file & edit document properties" >}}
            {{< blocks/products/pf/agp/democard icon="fa-download" text=" Instantly get the download link for the resultant file" >}}

        {{< blocks/products/pf/agp/about-file-text fileFormat="MPP" readMoreLink="https://docs.fileformat.com/project-management/mpp/" >}}
A file with MPP extension is Microsoft Project data file that stores information related to project management in an integrated manner. It is proprietary file format developed by Microsoft as file format for Microsoft Project (MSP) which is a project management application software. Besides MPP, MSP supports other file formats as well like project XML schema. Several APIs and applications provide the facility to convert MPP file format to others. Microsoft now has online Project Server where project management files can be uploaded for collaboration by multiple users.

        {{< /blocks/products/pf/agp/about-file-text >}}

    {{< /blocks/products/pf/agp/about-file-section >}}

<!-- aboutfile Ends -->

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Metadata Formats" subTitle="Using C++, One can also manipulate metadata of many other formats including" >}}

{{< blocks/products/pf/agp/other-supported-section-item href="//" name="" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}