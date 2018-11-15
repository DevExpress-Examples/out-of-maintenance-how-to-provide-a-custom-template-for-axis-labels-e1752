<!-- default file list -->
*Files to look at*:

* [Window1.xaml](./CS/Window1.xaml) (VB: [Window1.xaml](./VB/Window1.xaml))
<!-- default file list end -->
# How to provide a custom template for axis labels


<p>The following example demonstrates how to change the appearance of <a href="https://documentation.devexpress.com/#WPF/CustomDocument6336">Axis Labels</a> by using the <a href="https://documentation.devexpress.com/#WPF/clsDevExpressXpfChartsAxisLabeltopic">AxisLabel</a>.<a href="https://documentation.devexpress.com/#WPF/DevExpressXpfChartsChartTextElement_ElementTemplatetopic">ElementTemplate Property</a>, for example, to rotate them by a specific angle.</p>


<h3>Description</h3>

<p>For this, it is necessary to create a <strong>DataTemplate</strong>, which specifies the appearance of axis labels, and add it to a window&#39;s resources collection. Then, this template can be applied to an axis label via its <strong>AxisLabel.Template</strong> property.</p>

<br/>


