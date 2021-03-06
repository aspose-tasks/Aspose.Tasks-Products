---
title: View or Edit MPP Files Metadata via .NET 
weight: 1130
url: /net/metadata/mpp/ 
description: C# source code to edit or view MPP format metadata on .NET Framework, Mono and COM Interop.
---

{{< blocks/products/pf/main-wrap-class isAutogenPage="true">}}
{{< blocks/products/pf/upper-banner h1="Extract MPP Metadata via .NET" h2="Build your own .NET apps to add, edit, remove or extract metadata from MPP files using server-side APIs." logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/tasks/aspose_tasks-for-net.svg" sourceAdditionalConversionTag="" additionalConversionTag="MPP" pfName="Aspose.Tasks" subTitlepfName="for .NET" downloadUrl="" fileiconsmall1="PPTX" fileiconsmall2="DOCX" fileiconsmall3="XLSX" fileiconsmall4="PDF" fileiconsmall5=" ODP " >}}

{{< blocks/products/pf/main-container pfName="Aspose.Tasks " subTitlepfName="for .NET" >}}
{{< blocks/products/pf/sub-menu autoGeneratedVersion="true" logoImageSrc="https://www.aspose.cloud/templates/aspose/img/products/tasks/aspose_tasks-for-net.svg" apiHomeLink="" codeSamplesLink="https://github.com/aspose-tasks" liveDemosLink="https://products.aspose.app/tasks/family" docsLink="https://docs.aspose.com/tasks/net" installationsDocsLink="https://docs.aspose.com/tasks/net" nugetLink="https://www.nuget.org/packages/aspose.tasks" nugetPackageName="" downloadAsLink="https://downloads.aspose.com/tasks/net" learnAsLink="https://docs.aspose.com/tasks/net" apiReference="" mavenRepoLink="" >}}

{{% blocks/products/pf/agp/content h2="How to Extract MPP Metadata Using C#" %}}

 In order to extract MPP metadata, we’ll use
 [Aspose.Tasks for .NET](https://products.aspose.com/tasks/net) 
 API which is a feature-rich, powerful and easy to use document metadata API for C# platform. Open
 [NuGet](https://www.nuget.org/packages/aspose.tasks) 
 package manager, search for
 **Aspose.Tasks** 
 and install. You may also use the following command from the Package Manager Console.

{{% blocks/products/pf/agp/code-block title="Command" offSpacer="true" %}}

```cs

PM> Install-Package Aspose.Tasks

```

{{% /blocks/products/pf/agp/code-block %}}

{{% /blocks/products/pf/agp/content %}}

{{< blocks/products/pf/agp/feature-section isGrey="true" >}}

{{% blocks/products/pf/agp/feature-section-col title="Steps to Extract Metadata of MPP via C#" %}}

{{% blocks/products/pf/agp/text %}}

{{% /blocks/products/pf/agp/text %}}

+  Load MPP using Project Class
+  Use respective Class objects like Task, ResourceAssignment
+  Set the relevant properties
+  Save the project

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/feature-section-col title="System Requirements" %}}

{{% blocks/products/pf/agp/text %}}

 Aspose.Tasks for .NET is supported on all major operating systems. Just make sure that you have the following prerequisites.

{{% /blocks/products/pf/agp/text %}}

-  Microsoft Windows or a compatible OS with .NET Framework, Mono and COM Interop.
-  Development environment like Microsoft Visual Studio.
-  Aspose.Tasks for .NET referenced in your project.

{{% /blocks/products/pf/agp/feature-section-col %}}

{{% blocks/products/pf/agp/code-block title="Extract Metadata of MPP - C#" offSpacer="" %}}

```cs

Project project = new Project("Project1.mpp");

// Add working times to project calendar
WorkingTime wt = new WorkingTime();
wt.FromTime = new DateTime(2010, 1, 1, 19, 0, 0);
wt.ToTime = new DateTime(2010, 1, 1, 20, 0, 0);
WeekDay day = project.Get(Prj.Calendar).WeekDays.ToList()[1];
day.WorkingTimes.Add(wt);

// Change calendar name
project.Get(Prj.Calendar).Name = "CHANGED NAME!";

// Add tasks and set task meta data
Task task = project.RootTask.Children.Add("Task 1");
task.Set(Tsk.DurationFormat, TimeUnitType.Day);
task.Set(Tsk.Duration, project.GetDuration(3));
task.Set(Tsk.Contact, "Rsc 1");
task.Set(Tsk.IsMarked, true);
task.Set(Tsk.IgnoreWarnings, true);
Task task2 = project.RootTask.Children.Add("Task 2");
task2.Set(Tsk.DurationFormat, TimeUnitType.Day);
task2.Set(Tsk.Contact, "Rsc 2");

// Link tasks
project.TaskLinks.Add(task, task2, TaskLinkType.FinishToStart, project.GetDuration(-1, TimeUnitType.Day));

// Set project start date
project.Set(Prj.StartDate, new DateTime(2013, 8, 13, 9, 0, 0));

// Add resource and set resource meta data
Resource rsc1 = project.Resources.Add("Rsc 1");
rsc1.Set(Rsc.Type, ResourceType.Work);
rsc1.Set(Rsc.Initials, "WR");
rsc1.Set(Rsc.AccrueAt, CostAccrualType.Prorated);
rsc1.Set(Rsc.MaxUnits, 1);
rsc1.Set(Rsc.Code, "Code 1");
rsc1.Set(Rsc.Group, "Workers");
rsc1.Set(Rsc.EMailAddress, "This email address is being protected from spambots. You need JavaScript enabled to view it.");
rsc1.Set(Rsc.WindowsUserAccount, "user_acc1");
rsc1.Set(Rsc.IsGeneric, new NullableBool(true));
rsc1.Set(Rsc.AccrueAt, CostAccrualType.End);
rsc1.Set(Rsc.StandardRate, 10);
rsc1.Set(Rsc.StandardRateFormat, RateFormatType.Day);
rsc1.Set(Rsc.OvertimeRate, 15);
rsc1.Set(Rsc.OvertimeRateFormat, RateFormatType.Hour);

rsc1.Set(Rsc.IsTeamAssignmentPool, true);
rsc1.Set(Rsc.CostCenter, "Cost Center 1");

// Create resource assignment and set resource assignment meta data
ResourceAssignment assn = project.ResourceAssignments.Add(task, rsc1);
assn.Set(Asn.Uid, 1);
assn.Set(Asn.Work, task.Get(Tsk.Duration));
assn.Set(Asn.RemainingWork, assn.Get(Asn.Work));
assn.Set(Asn.RegularWork, assn.Get(Asn.Work));
task.Set(Tsk.Work, assn.Get(Asn.Work));

rsc1.Set(Rsc.Work, task.Get(Tsk.Work));
assn.Set(Asn.Start, task.Get(Tsk.Start));
assn.Set(Asn.Finish, task.Get(Tsk.Finish));

// Add extended attribute for project and task
ExtendedAttributeDefinition attr = ExtendedAttributeDefinition.CreateTaskDefinition(CustomFieldType.Flag, ExtendedAttributeTask.Flag1,  "My Flag Field");
project.ExtendedAttributes.Add(attr);

ExtendedAttribute taskAttr = attr.CreateExtendedAttribute();
taskAttr.FlagValue = true;
task2.ExtendedAttributes.Add(taskAttr);

// Save project as MPP
project.Save("WriteMetaData_out.mpp", SaveFileFormat.MPP);  

```

{{% /blocks/products/pf/agp/code-block %}}

{{< /blocks/products/pf/agp/feature-section >}}

    {{< blocks/products/pf/agp/faq-item question="" answer="" >}}
 

<!-- aboutfile Starts -->

    {{% blocks/products/pf/agp/content h2="About Aspose.Tasks for .NET API" %}}

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

{{< blocks/products/pf/agp/other-supported-section title="Other Supported Metadata Formats" subTitle="Using C#, One can also manipulate metadata of many other formats including." >}}

{{< blocks/products/pf/agp/other-supported-section-item href="/" name="" description="" >}}

{{< /blocks/products/pf/agp/other-supported-section >}}

{{< /blocks/products/pf/main-container >}}
    
{{< /blocks/products/pf/main-wrap-class >}}