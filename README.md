## Power BI for Physics

Power BI for analysing high-energy physics events. Data cleaning and selection criteria implemented using Power Query M, or dynamically set using slicers in a Power BI report.
The files included here utilise the [ATLAS Open Data](https://opendata.atlas.cern/) for finding the Higgs peak.

<table>
  <tr>
    <th> File </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> <a href="Documentation.pdf">Documentation.pdf</a> </td>
    <td> Detailed documentation of the Power BI projects in this repository. </td>
  </tr>
  <tr>
    <td> <a href="hyy_simple.pbix">hyy_simple.pbix</a> </td>
    <td> Visualise the Higgs peak in $H\to\gamma\gamma$ events. Analysis follows the example <a href="https://github.com/atlas-outreach-data-tools/notebooks-collection-opendata/blob/master/13-TeV-examples/uproot_python/HyyAnalysis.ipynb">here</a>. </td>
  </tr>
  <tr>
    <td> hyy_interactive.pbix </td>
    <td> Utilise slicer elements to dynamically visualise the impact of different selection criteria on the data distribution. (<i>Not included in repository due to large filesize.</i>) </td>
  </tr>
</table>

#### Features:
- [x] Implement selections in Power Query M and plot the Higgs peak via Python scripting functionality
- [x] Utilise M and DAX to create an interactive report where selection criteria can be modified using slicers
