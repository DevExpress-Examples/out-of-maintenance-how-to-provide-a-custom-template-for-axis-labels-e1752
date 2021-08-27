<!-- default badges list -->
![](https://img.shields.io/endpoint?url=https://codecentral.devexpress.com/api/v1/VersionRange/128570086/19.2.3%2B)
[![](https://img.shields.io/badge/Open_in_DevExpress_Support_Center-FF7200?style=flat-square&logo=DevExpress&logoColor=white)](https://supportcenter.devexpress.com/ticket/details/E1752)
[![](https://img.shields.io/badge/📖_How_to_use_DevExpress_Examples-e9f6fc?style=flat-square)](https://docs.devexpress.com/GeneralInformation/403183)
<!-- default badges end -->
<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/Window1.xaml) (VB: [Window1.xaml](./VB/Window1.xaml))
<!-- default file list end -->
# How to provide a custom template for axis labels

 You can specify label properties or define a [data template](https://docs.microsoft.com/en-us/dotnet/desktop/wpf/data/data-templating-overview?view=netframeworkdesktop-4.8) for axis labels to change their appearance. 
 
 This example specifies the following properties for X-axis labels: [Angle](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.AxisLabel.Angle),
[Background](https://docs.microsoft.com/en-us/dotnet/api/system.windows.controls.control.background?view=netcore-3.1#System_Windows_Controls_Control_Background), [FontSize](https://docs.microsoft.com/en-us/dotnet/api/system.windows.controls.control.fontsize?view=netcore-3.1#System_Windows_Controls_Control_FontSize), [FontStyle](https://docs.microsoft.com/en-us/dotnet/api/system.windows.controls.control.fontstyle?view=netcore-3.1#System_Windows_Controls_Control_FontStyle),  [FontWeight](https://docs.microsoft.com/en-us/dotnet/api/system.windows.controls.control.fontweight?view=netcore-3.1#System_Windows_Controls_Control_FontWeight), [Foreground](https://docs.microsoft.com/en-us/dotnet/api/system.windows.controls.control.foreground?view=netcore-3.1#System_Windows_Controls_Control_Foreground), and [TextPattern](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.AxisLabel.TextPattern).


The example defines a [data template](https://docs.microsoft.com/en-us/dotnet/desktop/wpf/data/data-templating-overview?view=netframeworkdesktop-4.8) for Y-axis labels. Assign this template to the [ElementTemplate](https://docs.devexpress.com/WPF/DevExpress.Xpf.Charts.ChartTextElement.ElementTemplate) property to apply it to labels.

<br/>


