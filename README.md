# Phase 4 Project
![png](https://www.phoenixfl.org/wp-content/uploads/2020/05/iStock-1069431162_1500w.jpg)

## Outline

This project examines the median sale prices by zip code for houses within the state of Florida. In an effort to provide actionable information to potential home buyers, we have forecasted the returns for each zip code both 24 and 60 months into the future. 

## Links

[Presentation](presentationlink)<br/>
[Purpose](README.md#Purpose) <br/>
[Data Description](README.md#Data-Description) <br/>
[Maps](README.md#Maps)<br/>
  -[Map of Two Year Returns](README.md#Map-of-Florida-(Two-Year-Returns)) <br/>
  -[Map of Five Year Returns](README.md#Map-of-Florida-(Five-Year-Returns)) <br/>
  -[Comprehensive Map](README.md#Comprehensive-Map---Top-5-Zipcodes-for-Both-Timeframes) <br/>
[Top 5 Zip Codes](README.md#Top-5-Zip-Codes) <br/>
[Financial Crisis](README.md#Financial-Crisis) <br/>
[Summary](README.md#Summary) <br/>

## Purpose
To build a forecast model for the prices of homes in Florida, in order to predict the top five zip codes for investment over a two and five year horizon.

## Data Description

The housing data used in this analysis comes from [Zillow Research](https://www.zillow.com/research/data/). The data contains information on 785 zip codes in Florida, and spans a 22 year period, from 1996 - 2018. <br/>
<br/>
<p align="center">
  <a href="https://www.zillow.com/research/data/" title="Zillow Research">
    <img src="http://filecache.mediaroom.com/mr5mr_zillow/204622/Zillow_Wordmark_Blue_RGB.jpg" />
  </a>
</p>

## Maps

Below are the respective maps for the 2 and 5 year windows as well as a map showing the top 5 zip codes for the entirety of Florida over both timeframes. The returns were calculated starting from the last day of the historical data  until the last day for the forecasted timeframe. The ROIs were then arranged into octiles and colored accordingly. The numerical values in the legends correspond with the percent returns for the time period.

## Map of Florida (Two Year Returns)

![img2year](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/map%20-%202%20year.png)

## Map of Florida (Five Year Returns)
    
![img5year](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/map%20-%205%20year.png)

## Comprehensive Map - Top 5 Zipcodes for Both Timeframes

![imgcomp](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/map%20-%20comprehensive.png)

## Top 5 Zip Codes

Below are the historical median plots for the 5 best zip codes to invest for the 2 and 5 year windows, respectively. The tables that accompany the charts show the forecasted ROI for the corresponding zip codes over these windows. The dropdown bar shows the corresponding forecast plots for each of the zipcodes.

<div align="center">

![imghistorical](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/2%20year%20historical.png)
  
<h3> Top 5 Zip Codes - 2 year forecast </h3>

| Zip Codes - City | Percent Return|
| ---------------- | :--------------: |
| 32621 - Bronson | 130.76% | 
| 32461 - Panama City Beach | 125.85% |
| 34449 - Inglis | 123.48% |
| 32455 - Ponce De Leon | 121.36% |
| 32625 - Panama City Beach| 117.45% |

    
  <h4> Corresponding Forecast Plots </h4>
  
  <details>
  <summary> 32621 - Bronson </summary>
  
  ![32621](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/2%20year%20-%2032621.png)
  
  </details>
  <details>
  <summary> 32461 - Panama City Beach </summary>
  
  ![32461](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/2%20year%20-%2032461.png)
  
  </details>
  <details>
  <summary> 34449 - Inglis </summary>
  
  ![34449](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/2%20year%20-%2034449.png)
  
  </details>
  <details>
  <summary> 32455 - Ponce De Leon </summary>
  
  ![32455](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/2%20year%20-%2032455.png)
  
  </details>
  <details>
  <summary> 32625 - Cedar Key </summary>
  
  ![32625](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/2%20year%20-%2032625.png)
  
  </details> 

</details>
  </div> 

<div align="center">
  
![imghistorical5yr](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/5%20year%20historical.png)  
  
<h3> Top 5 Zip Codes - 5 year forecast </h3>

| Zip Codes| Percent Return|
| :-------------: | :-------------: |
| 33181 - North Miami | 728.86% |
| 32320 - Apalachicola| 342.46% | 
| 33701 - St. Petersburg| 292.44% |
| 33704 - St. Petersburg| 233.41% |
| 32680 - Old Town| 223.31% |
    
 <h4> Corresponding Forecast Plots </h4>
 
 <details>
  <summary> 33181 - North Miami </summary>
  
  ![33181](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/5%20year%20-%2033181.png)
  
  </details>
  <details>
  <summary> 32320 - Apalachicola </summary>
  
  ![32320](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/5%20year%20-%2032320.png)
  
  </details>
  <details>
  <summary> 33701 - St. Petersburg </summary>
  
  ![33701](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/5%20year%20-%2033701.png)
  
  </details>
  <details>
  <summary> 33704 - St. Petersburg </summary>
  
  ![33704](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/5%20year%20-%2033704.png)
  
  </details>
  <details>
  <summary> 32680 - Old Town </summary>
  
  ![32680](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/5%20year%20-%2032680.png)
  
  </details>
    </div> 

## Financial Crisis

By aggregating the information for all zipcodes within Florida, we are able to clearly see the trend occurring within the housing market over the past two decades. The "top" in the housing market was seen close to July 2007 and didn't subsequently bottom out until January 2012.

<div align="center">
  
![financialcrisisimg](https://github.com/Nick-Kolowich/dsc-phase-4-project/blob/main/images/financial%20crisis.png)

</div>

## Summary

This project seeks to not only provide an answer to "which are the best zip codes for investment in Florida," but also to serve as a framework for this type of analysis, which could be scaled up and applied to any state. The incorporation of other price factors, such as school district rigorousness, could help to construct a more comprehensive model for future work.<br/>
