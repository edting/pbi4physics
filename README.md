## Power BI for Physics

Power BI for analysing high-energy physics events. Cleaning and selection criteria can be implemented using Power Query M, or dynamically chosen using slicers in a Power BI report.
The files included here utilise the [ATLAS Open Data](https://opendata.atlas.cern/) for finding the Higgs peak.

<table>
  <tr>
    <th> File </th>
    <th> Description </th>
  </tr>
  <tr>
    <td> hyy_simple.pbix </td>
    <td> Visualise the Higgs peak in $H\to\gamma\gamma$ events. Analysis follows the example <a href="https://github.com/atlas-outreach-data-tools/notebooks-collection-opendata/blob/master/13-TeV-examples/uproot_python/HyyAnalysis.ipynb">here</a>. </td>
  </tr>
</table>

#### Features:
- [x] Implement selections in Power Query M and plot the Higgs peak via Python scripting functionality
- [ ] Load pre-selected data and generate an interactive report where selection criteria can be scaled using slicers
