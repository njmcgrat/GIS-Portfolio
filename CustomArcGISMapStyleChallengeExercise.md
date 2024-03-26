# Bid Proposal for Custom Google Map Style for MN DNR
<img src="https://raw.githubusercontent.com/njmcgrat/GIS-Portfolio/main/mn_dnr_logo_white.jpg" alt="MN DNR Logo" width="200" height="100">

## Introduction:
I are pleased to submit my bid for the development of a custom, brand-ready map for the Minnesota Department of Natural Resources. I excel at creating a visually appealing and functional map that aligns with your organization's brand identity and goals.

## Scope of Work:

Custom Map Development: I will design and develop a custom map tailored to match the overall look and feel of your organization's website. The map will incorporate your brand colors, fonts, and visual elements to create a cohesive user experience.

Map Features and Resources: The map will include features that allow site visitors to easily find important resources and information provided by your organization. I will work closely with you to identify and integrate relevant data layers, markers, and labels onto the map.

Deliverables: Google Style Map, Lookup Table Documentation, JSON file

Instructions for Embedding the Map: Simple instructions will be provided, detailing how to effectively use the provided materials, including the screenshots, lookup table, and JSON file, to embed the redesigned basemap into your website. These instructions will ensure seamless integration and maintenance of the map.

## Timeline:
I estimate that the project will be completed within one week, allowing for ample time for consultation, development, and review.

## Budget:
My proposed budget for completing the scope of work outlined above is $1000 (10 hours at $100/hr). This includes all necessary resources, consultation, and deliverables as specified.

## Conclusion:
I are excited about the opportunity to work with your organization on this project and believe that my expertise and dedication will result in a custom map solution that exceeds your expectations. Thank you for considering my bid, and I look forward to the opportunity to collaborate with you.

# Style Examples
## State Park (Local) Level
<img src="https://github.com/njmcgrat/GIS-Portfolio/blob/main/MilleLacsKathioSP.png" alt="State Park Zoom" width="600" height="400">

## Regional Level
<img src="https://github.com/njmcgrat/GIS-Portfolio/blob/main/MilleLacs.png" alt="Region Zoom" width="600" height="400">

## State Level
<img src="https://github.com/njmcgrat/GIS-Portfolio/blob/main/MN.png" alt="State Zoom" width="600" height="400">

# Deliverables 
## Color Pallet
The color pallet was generate by inputing the logo for the Minnesota DNR into the online Adobe tool.  The logo is very simple and only has three colors (if you count white), so I selected a 'muted' pallet to increase the number of distinct colors to use on the map style. 

![dnrcolorpallet.png](https://github.com/njmcgrat/GIS-Portfolio/blob/main/dnrcolorpallet.png "Color Pallet")

 ## Custom Style Details
 <table>
  <thead>
    <tr>
      <th>Element Type</th>
      <th>Feature Type</th>
      <th>Styler Type</th>
      <th>Styler Value</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>geometry</td>
      <td>N/A</td>
      <td>color</td>
      <td>#4a8c5b</td>
    </tr>
    <tr>
      <td>labels.text.fill</td>
      <td>N/A</td>
      <td>color</td>
      <td>#523735</td>
    </tr>
    <tr>
      <td>labels.text.stroke</td>
      <td>N/A</td>
      <td>color</td>
      <td>#f5f1e6</td>
    </tr>
    <tr>
      <td>administrative</td>
      <td>geometry.stroke</td>
      <td>color</td>
      <td>#c9b2a6</td>
    </tr>
    <tr>
      <td>administrative.land_parcel</td>
      <td>geometry.stroke</td>
      <td>color</td>
      <td>#82bf45</td>
    </tr>
    <tr>
      <td>administrative.land_parcel</td>
      <td>labels.text.fill</td>
      <td>color</td>
      <td>#ae9e90</td>
    </tr>
    <tr>
      <td>landscape.natural</td>
      <td>geometry</td>
      <td>color</td>
      <td>#4a8c5b</td>
    </tr>
    <tr>
      <td>poi</td>
      <td>geometry</td>
      <td>color</td>
      <td>#f2f2f2</td>
    </tr>
    <tr>
      <td>poi</td>
      <td>labels.text.fill</td>
      <td>color</td>
      <td>#93817c</td>
    </tr>
    <tr>
      <td>poi.park</td>
      <td>geometry.fill</td>
      <td>color</td>
      <td>#82bf45</td>
    </tr>
    <tr>
      <td>poi.park</td>
      <td>labels.text.fill</td>
      <td>color</td>
      <td>#447530</td>
    </tr>
    <tr>
      <td>road</td>
      <td>geometry</td>
      <td>color</td>
      <td>#f5f1e6</td>
    </tr>
    <tr>
      <td>road.arterial</td>
      <td>geometry</td>
      <td>color</td>
      <td>#fdfcf8</td>
    </tr>
    <tr>
      <td>road.highway</td>
      <td>geometry</td>
      <td>color</td>
      <td>#f8c967</td>
    </tr>
    <tr>
      <td>road.highway</td>
      <td>geometry.stroke</td>
      <td>color</td>
      <td>#e9bc62</td>
    </tr>
    <tr>
      <td>road.highway.controlled_access</td>
      <td>geometry</td>
      <td>color</td>
      <td>#e98d58</td>
    </tr>
    <tr>
      <td>road.highway.controlled_access</td>
      <td>geometry.stroke</td>
      <td>color</td>
      <td>#db8555</td>
    </tr>
    <tr>
      <td>road.local</td>
      <td>labels.text.fill</td>
      <td>color</td>
      <td>#806b63</td>
    </tr>
    <tr>
      <td>transit.line</td>
      <td>geometry</td>
      <td>color</td>
      <td>#dfd2ae</td>
    </tr>
    <tr>
      <td>transit.line</td>
      <td>labels.text.fill</td>
      <td>color</td>
      <td>#8f7d77</td>
    </tr>
    <tr>
      <td>transit.line</td>
      <td>labels.text.stroke</td>
      <td>color</td>
      <td>#ebe3cd</td>
    </tr>
    <tr>
      <td>transit.station</td>
      <td>geometry</td>
      <td>color</td>
      <td>#dfd2ae</td>
    </tr>
    <tr>
      <td>water</td>
      <td>geometry.fill</td>
      <td>color</td>
      <td>#024873</td>
    </tr>
    <tr>
      <td>water</td>
      <td>labels.text.fill</td>
      <td>color</td>
      <td>#92998d</td>
    </tr>
  </tbody>
</table>

## [Download style Json File](https://github.com/njmcgrat/GIS-Portfolio/blob/main/mn_dnr_custom_map.json)

[My attempt at embedding the map](https://njmcgrat.github.io/GIS-Portfolio/customGoogleMap4NP.html)  !buggy!
