# How to create a 2D Funnel chart


<p>The following example demonstrates how to create a 2D Funnel chart.</p>
<p>For this, it's necessary to create a <a href="https://documentation.devexpress.com/#Silverlight/clsDevExpressXpfChartsChartControltopic">ChartControl</a>, choose a <a href="https://documentation.devexpress.com/#Silverlight/clsDevExpressXpfChartsSimpleDiagram2Dtopic">SimpleDiagram2D</a> object as its diagram and put <strong> FunnelSeries2D</strong> into its series collection. Each point of a funnel series should contain an argument and a value.</p>
<p>Note that in this sample the label's <strong>TextPattern</strong> and<strong> LegendTextPattern</strong> properties are set to "{}{A}: {VP: ##.##%}", which allows showing a point's argument and its percentage value separated by a colon. The available placeholders are detailed below.<br /><strong>{A}</strong>     Use it to display a series point's arguments.</p>
<p><strong>{VP}</strong>   Use it to display a series point's values as percent.</p>
<p><strong>{S}</strong>     Use it to display the series name.</p>

<br/>


