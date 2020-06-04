---
title: Introduction
page_title: Introduction
description: "Download and install {{ site.product_long }}, and run the sample application."
previous_url: /aspnetmvc-apps/mvc-6/introduction, /mvc-6/introduction, /getting-started/kendo-ui-vs-mvc-wrappers
slug: overview_aspnetmvc6_aspnetmvc
position: 1
---
{% if site.core %} 
    {% assign telerik_product_url = "aspnet-core-ui" %}
{% else %}
    {% assign telerik_product_url = "aspnet-mvc" %}
{% endif %}

## Welcome to {{ site.product }}

Thank you for choosing Progress<sup>®</sup> Telerik<sup>®</sup> {{ site.product_short }}!  

[{{ site.product }}](https://www.telerik.com/{{ telerik_product_url }}) is a set of server-side wrappers (HTML{% if site.core %} and Tag{% endif %} helpers) that allow you to use the Kendo UI widgets in .NET {{ site.framework_short }}. From a client-side point of view, the vanilla HTML/JavaScript Kendo UI widgets and their {{ site.framework }} helpers represent the same functionalities and provide the same capabilities.

The {{ site.product }} HTML{% if site.core %} and Tag{% endif %} helpers:
* Allow you to configure a Kendo UI widget through the C# or VB.NET code&mdash;for example, to set its value, data source, and so on.
* Render the HTML and JavaScript that are needed to initialize a Kendo UI widget whose options propagate to the client-side through its initialization script.

To read more about the benefits of using {{ site.product }}, please visit the {% if site.core %}[product overview page](https://www.telerik.com/aspnet-core-ui){% else %}[product overview page](https://www.telerik.com/aspnet-mvc){% endif %}.

<style>
/* UI for ASP.NET download trial button */
div#aspnet_trial {
	text-align: center !important;
}
div#aspnet_trial .aspnet_download_btn {	
	color: #fff;
	background-color: #e74b3c;
	padding:.44em .9em .52em;
	font-size: 20px;
	font-weight:400;
	letter-spacing:-.025em;
	position:relative;
	display:inline-block;
	line-height:1.2;
	-webkit-transition:color .2s ease,background-color .2s ease;
	transition:color .2s ease,background-color .2s ease;
	border-radius:2px;
	-webkit-appearance:none;
	font-family:Metric,Arial,Gadget,sans-serif;
	text-align:center	
}
</style>

<div id="aspnet_trial">
<br />
    <a href="https://www.telerik.com/download-trial-file/v2/{{ telerik_product_url }}" class="aspnet_download_btn">Download Free Trial</a>
</div>

## Getting Started

{% if site.core %}
<iframe width="853" height="480" src="https://www.youtube.com/embed/jAOZY9TZi78?list=PLvmaC-XMqeBaHWzU1zyFgaNi2pcuix6Ps" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

More resources on getting started with {{ site.product_short }}:

* [First Steps with {{ site.product_short }} on Visual Studio for Windows]({% slug gettingstarted_aspnetmvc6_aspnetmvc %})
* [First Steps with {{ site.product_short }} on Visual Studio for Mac]({% slug gettingstarted_firststeps_vsmac %})
* [First Steps with {{ site.product_short }} with CLI]({% slug gettingstartedcli_aspnetmvc6_aspnetmvc %})
{% else %}
* [First Steps with {{ site.product_short }}]({% slug gettingstarted_aspnetmvc %})
* [Telerik UI for ASP.NET MVC fundamentals]({% slug fundamentals_aspnetmvc %})
* [Installing Telerik UI for ASP.NET MVC with NuGet]({% slug aspnetmvc_nuget %})
* [Scaffolding the Telerik UI for ASP.NET MVC project]({% slug scaffolding_aspnetmvc %})
* [Integrating the Telerik UI for ASP.NET MVC project with Visual Studio]({% slug overview_visualstudio_aspnetmvc %})
{% endif %}

### List of Helpers

{% include_relative list-of-helpers.html %}

### Supported Environments

{% if site.core %}
{{ site.product_short }} targets the stable releases of the {{ site.framework }} framework. The target runtime is [CoreCLR](https://github.com/dotnet/coreclr). The {{ site.product_short }} suite also supports the full desktop CLR.
{% else %}
Telerik {{ site.product_short }} supports:

* [.NET Framework v3.5](https://www.microsoft.com/en-us/download/details.aspx?id=21) and later.
* [ASP.NET MVC 3](http://www.asp.net/mvc/mvc3) and later.
* Visual Studio 2012 and later.
* [IIS 5](https://www.microsoft.com/en-us/download/details.aspx?id=24843) and later.
* [C#](https://msdn.microsoft.com/en-us/library/aa288436(v=vs.71).aspx)  and [VB.NET](http://www.tutorialspoint.com/vb.net/).
* [SharePoint 2010](https://msdn.microsoft.com/en-us/library/office/dd776256(v=office.12).aspx) and later.

The Telerik UI for ASP.NET MVC Visual Studio extensions support Visual Studio 2015 and later.
{% endif %}

### Monitoring the Progress Live Services

Progress provides up-to-date information about the live services it delivers to its customers on a daily basis&mdash;for example, the Kendo UI CDN services, Kendo UI Dojo playground, and Telerik NuGet feed.

* [Progress<sup>®</sup> Telerik<sup>®</sup> Live Services Status Page](http://status.telerik.com/)

### Trial Version and Commercial License

This {{ site.product_short }} library is a commercial UI library. You are welcome to explore its full functionality and get technical support from the team when you register for a free 30-day trial. To use it commercially, you need to [purchase a license](https://www.telerik.com/purchase/kendo-ui). Feel free to review the Telerik {{ site.product_short }} [License Agreement](https://www.telerik.com/purchase/license-agreement/kendo-ui) to get acquainted with the full terms of use.

### Support Options

For any issues you might encounter while working with {{ site.product_short }}, use any of the available support channels:

* {{ site.product_short }} license holders and active trialists can take advantage of the outstanding customer support delivered by the developers building the library. To submit a support ticket, use the [{{ site.product_short }} dedicated support](https://www.telerik.com/account/support-tickets/) system.
* [{{ site.product_short }} forums](https://www.telerik.com/forums/{{ telerik_product_url }}) are part of the free support you can get from the community and from the {{ site.product_short }} team on all kinds of general issues.
* [{{ site.product_short }} feedback portal](https://feedback.telerik.com/{{ telerik_product_url }}) and [{{ site.product_short }} roadmap](https://www.telerik.com/support/whats-new/kendo-ui/roadmap) provide information on the features in discussion and also the planned ones for release.
* You may still need a tailor-made solution for your project. In such cases, go straight to [Progress Services](https://www.progress.com/services).

## Learning Resources

{% if site.core %} 
* [Virtual Classroom](https://progress.exceedlms.com/student/path/497495-telerik-ui-for-asp-net-core)
* [Knowledge Base](https://docs.telerik.com/aspnet-core/knowledge-base.html)
* [Support Resources Hub Page](https://www.telerik.com/support/aspnet-core)
* [Collected Examples on Telerik UI for ASP.NET Core](https://github.com/telerik/ui-for-aspnet-core-examples)
{% else %}
* [Virtual Classroom](https://progress.exceedlms.com/student/path/498054-telerik-ui-for-asp-net-mvc)
* [Tutorials]({% slug overview_timeefficiencyapp_aspnetmvc6 %})
* [Support Resources Hub Page](https://www.telerik.com/support/aspnet-mvc)
* [Collected Examples on ASP.NET MVC](https://github.com/telerik/kendo-examples-asp-net-mvc)
* [Collected Examples on ASP.NET Web Technologies](https://github.com/telerik/kendo-examples-asp-net)
* [Collected Examples on Telerik UI for ASP.NET MVC](https://github.com/telerik/ui-for-aspnet-mvc-examples)
{% endif %}

### Next Steps

{% if site.core %}
* [First steps on Visual Studio for Windows (online guide)]({% slug gettingstarted_aspnetmvc6_aspnetmvc %})
* [First steps on Visual Studio for Mac (online guide)]({% slug gettingstarted_firststeps_vsmac %})
* [First steps with CLI (online guide)]({% slug gettingstartedcli_aspnetmvc6_aspnetmvc %})
* [Including client-side resources]({% slug copyclientresources_aspnetmvc6_aspnetmvc %})
* [Integrating UI for ASP.NET Core in Visual Studio]({% slug overview_visualstudio_aspnetcore %})
* [Upgrading UI for ASP.NET Core in Visual Studio]({% slug upgrade_aspnetcore %})
{% else %}
* [Downloading and installing Telerik UI for ASP.NET MVC]({% slug overview_downloadinstallation_mvc %})
* [Exploring the Telerik UI for ASP.NET MVC fundamentals]({% slug fundamentals_aspnetmvc %})
* [Integrating Telerik UI for ASP.NET MVC in Visual Studio]({% slug overview_visualstudio_aspnetmvc %})
* [Upgrading Telerik UI for ASP.NET MVC]({% slug upgrade_aspnetcore %})
{% endif %}
