# OS Open Built Up Areas

These are **lyrx** files for OS Open Built Up Areas in **Geopackage format** for use in **ESRI ArcPro**.

*They have been designed to work with the data as it is supplied.*

## Quick start guide

**1.**  Fork or [download](https://github.com/OrdnanceSurvey/OS-Open-Built-Up-Areas-stylesheets/archive/master.zip) the contents of this repository

**2.**  In ArcPro, right-click on ‘Map’ towards the top of the Contents panel, select Properties… > then under Coordinate System > choose British National Grid (Projected Coordinate System, National Grids, Europe). You may need to reposition to the data extent

**3.**  In the top toolbar of ArcPro, under Labeling, click 'More' and ensure the 'Use Maplex Label Engine' is ticked on.

**4.**  Click on the ‘Add Data’ button and navigate to the stylesheets folder and the directory that matches your data format (geopackage) and stylesheet format (ESRI ArcPro stylesheets LYRX)

**5.**  Select the lyrx file and click ‘Add’

**6.**  In the Contents panel in ArcPro, double-click on a layer to access the Layer Properties window > select the ‘Source’> click on ‘Set Data Source…’ > navigate to your OS Open Built Up Areas geopackage data > select relevant dataset > select ‘Add’. For example, for the OS Open Built Up Areas layer, you'd select main.OS_Open_Built_Up_Areas layer.

Repeat step 6 for all other layers.

We recommend viewing of the data between **1:1,250** and **1:250,000** for maximum legibility.

We recommend viewing the data with OS OpenMap Local in the backdrop style or the light style of the OS Maps API.


Your map should now look similar to this: 

  ![Screenshot](https://github.com/OrdnanceSurvey/OS-Open-Built-Up-Areas-stylesheets/blob/9cb9e971c5c9cbe25c06a0ef9237966b91a92a17/ESRI%20ArcPro%20stylesheets%20(LYRX)/images/BuiltUpAreas.png "Screenshot of the Built Up Areas layer over the OS Maps API in light style")

## Additional information

Scale limits can be turned off from the General tab of Layer Properties.

[For more information about data styling and visualisation, take a look at our GeoDataViz toolkit](https://github.com/OrdnanceSurvey/GeoDataViz-Toolkit)

[More information about OS Open Built Up Areas](https://www.ordnancesurvey.co.uk/business-government/products/os-open-built-up-areas)

## Licence

By using these stylesheets you are accepting the terms of the [Open Government Licence](http://www.nationalarchives.gov.uk/doc/open-government-licence/)
