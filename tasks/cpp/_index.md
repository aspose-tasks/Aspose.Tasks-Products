---
title: C++ Microsoft Project Documents Parsing Library - Aspose 
weight: 460
url: /cpp/ 
---

{{< blocks/products/pf/main-wrap-class >}}
{{< blocks/products/pf/upper-banner h1="C++ Microsoft Project File Parsing API" h2="Create, Write, Read, Manipulate & Export Microsoft Project files to PDF,  Primavera, HTML, Excel, Images & XML formats from within Native C++ applications." logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/tasks/header/aspose_tasks-for-cpp.png" pfName="Aspose.Tasks" subTitlepfName="for C++" downloadUrl="https://downloads.aspose.com/tasks/cpp" >}}

{{< blocks/products/pf/main-container pfName="Aspose.Tasks" subTitlepfName="for C++" >}}

{{< blocks/products/pf/sub-menu logoImageSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/tasks/272x272/aspose_tasks-for-cpp.png" liveDemosLink="https://products.aspose.app/tasks/family" PricingLink="https://purchase.aspose.com/pricing/tasks/cpp" buyLink="https://purchase.aspose.com" docsLink="https://docs.aspose.com/tasks/cpp/" instalationsDocsLink="https://docs.aspose.com/tasks/cpp/installation/" nugetLink="https://www.nuget.org/packages/Aspose.Tasks.Cpp/" nugetPackageName="Aspose.Tasks.Cpp" >}}

{{< blocks/products/pf/tab-content >}}
<p>The C++ project management library offers complete tracking capabilities, definition, and planning allowing the developers to create and load tasks as well as remove or assign resources to or from tasks from their own applications.</p>
{{< /blocks/products/pf/tab-content >}}

<!--Diagrams Start-->
{{< blocks/products/pf/carousel >}}

{{< blocks/products/pf/carousel-item h3="" description="" >}}
{{< /blocks/products/pf/carousel-item >}}

{{< /blocks/products/pf/carousel >}}
<!--Diagrams End-->

<!--Feature-section Start-->
<div class="container-fluid features-section bg-gray singleproduct">
 <a class="anchor" id="features" name="features">
 </a>
 <div class="row">
  <div class="container">
   <h2 class="pr-ft">
    Advanced C++ Project Management API Features
   </h2>
   <p>
   </p>
   <div class="col-lg-4">
    <em class="fa fa-copy ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Create, read and manipulate Microsoft Project files
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-file-text-o ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Read MPP files and update its summary information
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-pencil-square-o ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Update main and default project settings
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-calendar-check-o ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Define weekdays for project, calendar and calendar exceptions
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-calendar-plus-o ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Read and write calendars for tasks and resources
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-tasks ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Handle task baseline scheduling, duration, and constraints
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-cogs ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Define resource assignment &amp; allocation
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-shield ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Support for the encoding of MPX files
    </p>
   </div>
   <div class="col-lg-4">
    <em class="fa fa-code ico-blue fa-2x col-lg-2">
    </em>
    <p class="col-lg-10">
     Export to PDF, HTML, Images and more formats
    </p>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">
     Export Microsoft Project Data to Various Formats
    </h2>
    <p>
     Aspose.Tasks for C++ exposes data in both MPP and XML formats as well as PDF, HTML for universal distribution of information, CSV, TXT, XLS, XLSX, WBS to any of the standard images and MPT formats. Furthermore, while exporting data to HTML, it exports the fonts, images and CSS styles to separate files.
    </p>
    <div class="codeblock" id="code">
     <h3>
      Export Project Data to Primavera XML, XER and MPX Format - C++
     </h3>
     <pre><code class="cs">System::SharedPtr&lt;Aspose::Tasks::Project&gt; pjc = System::MakeObject&lt;Aspose::Tasks::Project&gt;(dataDir + u"template.mpp");

// save project in desired format

pjc-&gt;Save(dataDir + u"output_PrimaveraP6XML.xml", Aspose::Tasks::Saving::SaveFileFormat::PrimaveraP6XML);

pjc-&gt;Save(dataDir + u"output_PrimaveraXER.mpp", Aspose::Tasks::Saving::SaveFileFormat::PrimaveraXER);

pjc-&gt;Save(dataDir + u"output_MPX.xml", Aspose::Tasks::Saving::SaveFileFormat::MPX);</code></pre>
    </div>
    <p>
     API has built-in rendering engine for rendering to the Microsoft Project with the highest of fidelity. Using the project rendering engine, developers can convert project data to various vector and raster images.
    </p>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">
     Setting up the Project Properties
    </h2>
    <p>
     To speed up the process of setting up a project, API lets users set default, general properties such as metadata, calendar, and currency properties. Default properties include when a new task starts and finishes, the default overtime, standard pay rates and more. API allows to read and set general project properties such as the project's start and end dates, the current date, the status date, the type of calendar used and when a project is scheduled from. Moreover, API also saves summary information including keywords, subject, comments and more.
    </p>
    <p>
     As for currency properties are concerned, the library supports setting the currency code, numbers after the decimal point and currency symbol so that it is easy to read the costs. Reading and writing the fiscal year and weekday properties are also supported.
    </p>
   </div>
   <div class="col-lg-12">
    <h2 class="h2title">
     Tasks Management in an Easy Way
    </h2>
    <p>
     API is capable of handling tasks within a Microsoft Project file using its rich set of classes. It can easily manage task baseline scheduling, budget assessment, duration and constraints on tasks as well as create and manage links between these. Furthermore, API allows developers to read, change and create tasks, milestones, estimated critical or effort driven tasks.
    </p>
   </div>
   <!-- content ends here-->
  </div>
 </div>
</div>
<!--Feature-section End-->

{{< /blocks/products/pf/main-container >}}

{{< blocks/products/pf/testimonials title="" subTitle="" >}}

{{< blocks/products/pf/testimonials-quote >}}
{{< /blocks/products/pf/testimonials-quote >}}

{{< /blocks/products/pf/testimonials >}}

{{< blocks/products/pf/support-learning-resources >}}
{{< blocks/products/pf/slr-tab tabTitle="Learning Resources" tabId="resources" >}}
{{< blocks/products/pf/slr-element name="Documentation" href="https://docs.aspose.com/tasks/cpp/" >}}
{{< blocks/products/pf/slr-element name="Source Code" href="https://github.com/aspose-tasks/Aspose.Tasks-for-C" >}}
{{< blocks/products/pf/slr-element name="API References" href="https://apireference.aspose.com/cpp/tasks" >}}
{{< blocks/products/pf/slr-element name="Tutorial Videos" href="https://www.youtube.com/user/asposevideo" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Product Support" tabId="support" >}}
{{< blocks/products/pf/slr-element name="Free Support" href="https://forum.aspose.com/c/tasks" >}}
{{< blocks/products/pf/slr-element name="Paid Support" href="https://helpdesk.aspose.com/" >}}
{{< blocks/products/pf/slr-element name="Blog" href="https://blog.aspose.com/category/tasks/" >}}
{{< blocks/products/pf/slr-element name="Release Notes" href="https://docs.aspose.com/tasks/cpp/release-notes/" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< blocks/products/pf/slr-tab tabTitle="Why Aspose.Tasks for C++" tabId="success-stories" >}}
{{< blocks/products/pf/slr-element name="Customers List" href="https://company.aspose.com/customers" >}}
{{< blocks/products/pf/slr-element name="Success Stories" href="https://company.aspose.com/customers/success-stories/aspose-tasks" >}}
{{< /blocks/products/pf/slr-tab >}}

{{< /blocks/products/pf/support-learning-resources >}}

{{< blocks/products/pf/download-section downloadFreeTrialLink="https://downloads.aspose.com/tasks/cpp" pricingInformationLink="https://purchase.aspose.com/pricing/tasks/cpp" >}}

{{< blocks/products/pf/offers-section pfName="" >}}

    {{< blocks/products/pf/offers-section-item link="/tasks/net" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/tasks/272x272/aspose_tasks-for-net.png" sdkName="Aspose.Tasks for .NET" >}}
    {{< blocks/products/pf/offers-section-item link="/tasks/java" imgSrc="https://www.aspose.cloud/templates/aspose/App_Themes/V3/images/tasks/272x272/aspose_tasks-for-java.png" sdkName="Aspose.Tasks for Java" >}}

{{< /blocks/products/pf/offers-section >}}

{{< /blocks/products/pf/main-wrap-class >}}