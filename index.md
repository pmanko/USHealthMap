# US Health Map Overview and Tutorial
## <http://vizhub.healthdata.org/subnational/usa>


### Overview
The US Health Map tool, created by the [Institute for Health Metrics and Evaluation (IHME)](http://www.healthdata.org/about), provides impressive online data visualization capabilities for mortality, life expectancy, and risk factor data across the United States. The underlying datasets are part of the Global Health Data Exchange (GHDx), a catalog of data compiled and managed by IHME. This catalog aims to gather and standardize world-wide public health data generated both by IHME initiatives and outside sources. The US Health Map tool uses a subset of this data catalog to allow for the visualization of health trends across the United States. 

### Features
![Overview](US%20Health%20Map%20%20%20IHME%20Viz%20Hub.png)	

1. **Dataset Selection** - provides the choice for the visualization of *Life Expectancy*, *Mortality Rates*, or *Risk Factors* on the map. 
2. **Locations** - provides the ability to select of multiple states or counties for comparison of data. *Warning - selection of locations should match the selected Administrative Division (3). If `State` is chosen in the Administrative Division (3), county data will not show up in the time trend (6) or colored dot plot (7). Time trend (6) comparisons between counties and states do show up if Admin. Division is set to county and both county and state locations are chosen.*    
3. **Administrative Division** - allows the choice of the granularity of the displayed map and dotplot data between `State` and `County`.
4. **Sex** - Filters the displayed data by a specific sex.
5. **Time Interval** - Filters data by specific year. Use of the slider allows for the visualization of trends over time. Play button automatically animates the year-to-year transitions. 
6. **Time Trend** - Overlays a line plot that plots the chosen locations and variables over time. Location selection can be fine-tuned on the overlaid panel, and uncertainty intervals can also be viewed. 
7. **Dot Plot** - Plots the selected data for all states or counties (depending on your selection in the Administrative Division (3) menu). The data is automatically scaled and colored on a blue to red gradient. Selected locations show up as open black circles. Detailed information about a given datapoint is visible by hovering the cursor over the datapoint.
8. **Advanced Options for Dot Plot Scale** - These options allow for modifying the color scale for the map and dotplot. 
   * `Set scale` rescales the colors to the interval selected by dragging the two white bars on each side of the color bar. 
   * `Rate of change` toggles the display of the rate of change for a given variable.
   * `Lock scale` freezes the scale for the data to prevent it from varying across different years. 

### Tutorial
1.  Using your mouse and the map controls, zoom in on your home county (or some county of your choice) and select both it and a neighboring county. 

2.  Using the Locations (2) select box, add King County, WA, the state of New Mexico, and Somerset County, NJ as selected locations. You should have six locations selected, including the entire United States, which is selected by default. 

3.  Visualize the 2012 prevalence data for Binge Drinking among drinkers for both sexes. Use the dotplot to view individual data points on the prevalence scale. 
    * What are the worst 3 counties for this risk factor?
    * What do these 3 counties have in common?

4. The dataset includes computed rates of change for this risk factor. Click on `Show advanced options` and click the white box to the right of `Rate of change` to toggle this option on. 
    * What is the annual percent change for Somerset County, NJ?
    * Switch between the sexes. Is there a noticable national difference between change among females and males?
    * Toggle `Rate of change` off again before continuing to the next step.
 
5. Most of the map is colored by some shade of blue, since the outlier counties are pulling the color scale to the right. Click on `Show advanced options` and drag the two white bars on the prevalence scale to include the middle section of the data (from ~24% to ~58%). Click the `Set Scale` button to rescale the color gradient to this range.
    * What is the binge drinking prevalence among your selected locations? What color does this prevalence correspond to?
    * What is the uncertainty of the prevalence in King County, WA?

6. Examine the time trends for this Risk factor. 
    * What years is this data available for?
    * Is there a general trend for binge drinking among drinkers?
    * Compare the trends for males and females. Is there a noticible difference?
    * Add Sioux County, ND as a location and view the uncertainty intervals. What are your impressions?

7. This online tool is very useful for data exploration. However, accessing the raw datasets is vital for doing additional analyses. Click on the "Download" link in the top right corner of the screen. 
    * What dataset was used as a source for the data you were viewing?
    * Who created this dataset? 
    * What underlying dataset was used to create these alcohol use prevalence estimates?
    * What year and journal was this data first published in, and who was the first author?
    
8.  Download the Alcohol Use Prevalence data from GHDx and open in Excel.
    * How many sheets does the dataset include?
    * How is `Binge Drinking` defined in this dataset?

### Additonal Information
* [About the Tool](http://www.healthdata.org/data-visualization/us-health-map)
* [Risk Factor Definitions](http://www.healthdata.org/sites/default/files/files/Data_viz/US-Health-Map-Risk-Factor-Definitions.pdf)

### Citation
*Institute for Health Metrics and Evaluation (IHME). US Health Map. Seattle, WA: IHME, University of Washington, 2016. Available from http://vizhub.healthdata.org/subnational/usa.*
