# How to create a knob-like gauge 


<p>The following example illustrates a gauge control that looks and behaves like a typical 'knob' element of a real-life dashboard. This knob replicates the knob-like appearance and provides the capability to interactively modify its value via mouse clicks.</p><br />



<h3>Description</h3>

<p>In this example, the knob-like gauge imitates the appearance of a real volume control. It is achieved by using custom templates for an arc scale&#39;s needle and layer elements. For your convenience, these templates are stored in the <strong>KnobRestoreDictionary.xaml</strong> file with <strong>OscilloscopeNeedleTemplate </strong>and <strong>OscilloscopeScaleLayerTemplate</strong> names, and thus can be easily re-used in your application.</p><p>The <strong>IsInteractive </strong>property of a gauge&#39;s needle<strong> </strong>is set to<strong> True </strong>to enable its interactivity.</p><p>Finally, below the knob-like gauge, there is a <strong>Label</strong> control, which is bound to the <strong>Value </strong>property of a needle to display the current volume set by knob.</p><br />


<br/>


