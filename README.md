

# Consumption-Observation_And_Analysis_by_Visualization
## Table of Contents 📑

[I. Introduction ☀️](#Intro)
- [1. Background](#background)
- [2. Motivation](#motivation)
- [3. Goal🎯](#goal)
- [4. Installation ](#install)
  
[II. Techniques](#Techniques)

[III. Dashboard](#Dashboard)

[IV. Charts](#Charts)
- [1. Pie chart ](#pie)
- [2. Area chart](#area)
- [3. Bubble chart](#bubble)
- [4. Rank chart ](#rank)
- [5. Geo Map ](#map)

===========================

<a name="Intro"></a>
## I. Introduction
<a name="background"></a>
### 1. Background
In the fast-paced world of sales, where every decision counts, the ability to derive actionable insights from data is a game-changer.
That's when the power of data visualization becomes more useful and shines than traditional report. Data visualization make complex data into simple chart and then  businesses can get a bird's-eye view of how their operations are functioning and make well-informed decisions that help increase efficiency, reduce costs, and improve product/service offerings. Business leaders to quickly identify patterns and trends in their data that would otherwise remain hidden or see easily any anomalies, formed correlation, identify the center distribution, compare categories,...

<a name="motivation"></a>
### 2. Motivation
<ul>
<li>		Showing the power of data visualization</li>
<li>		Using this power to implement the complex task in sale business </li>
</ul>

<a name="goal"></a>
### 3. Goals
<ul>
<li>	Consolidating and supplementing knowledge learned in theory class about Data Science and Data Visualization. </li>
<li>	Create a dynamic but comprehensive dashboard to display difficult-to-obtain views from numerical data. </li>
<li>    Provide opportunities to access many tools for data visualization and web presentation. </li>
<li>    Gain experience in project management and code refactoring processes. </li>
</ul>

<a name="install"></a>
### 4. Install
You can open the terminal on your IDE and clone the repo: 

` https://github.com/phamvutuyetanh/Consumption-Observation_And_Analysis_by_Visualization.git `

<a name="Techniques"></a>
## II. Techniques
<ul>
<li>	IDE for web programming: HTML/CSS/D3.js.</li>
<li>	Draft the UI of the dashboard: Microsoft Power BI.</li>
<li>  Library: DC, D3, Crossfilter, Leaf, CSS, ...</li>
</ul>

<a name="Dashboard"></a>
## III. Dashboard
Here, I use PowerBI to create the draft of dashboard. The overall structure of dashboard seem like: 

<img src="Source_Code\image\Dashboard_structure.png" width = 800 height = 300>

<a name="Charts"></a>
## IV. Charts
Here, there are the final result of the dashboard in the web which will be explain later. 

<img src="Source_Code\image\Dashboard_result.png" width = 800 height = 300>

<a name="pie"></a>
### 1. Pie chart

<img src="Source_Code\image\PieChart.png" width = 800 height = 300>

<ul>
    <li> Abstract task for chart: Comparison of proportion and  general overview </li>
    <li> Structure of pie chart: Mark(fraction of area of circles) & Channels (angle, color, label) </li>
    <li> Interaction:
        <ol>
            <li>Hover information</li>
            <li>Highlighting and selection</li>
            <li>Cross - chart interactivy </li>
            <li>Dynamic update</li>
        </ol>
    </li>
</ul>

<a name="area"></a>
### 2. Area chart
<img src="Source_Code\image\AreaChart.png" width = 800 height = 300>

<ul>
    <li> Abstract task for chart: 
        <ol>
            <li>Comparing the sales performance of different product categories over time
            </li>
            <li>Ilustrating the changes over time </li>
            <li>Cross - chart interactivy </li>
            <li>Outlier Detection</li>
        </ol>
    </li>
    <li> Structure of area chart: Mark(Area) & Channels (x-axis, y-axis, the color) </li>
    <li> Interaction:
        <ol>
            <li>Linking and brushing</li>
            <li> Transition</li>   
            <li>Highlighting and selection</li>
            <li>Cross - chart interactivy </li>
            <li>Dynamic update</li>
        </ol>
    </li>
</ul>
<a name="bubble"></a>
### 3. Bubble chart
<img src="Source_Code\image\BubbleChart.png" width = 800 height = 300>

<ul>
    <li> Abstract task for chart: 
        <ol>
            <li>Show correlation </li>
            <li>Comparing data sets</li>
            <li>Pattern Recognition</li>
        </ol>
    </li>
    <li> Structure of bubble chart: Mark(Circle) & Channels (x-axis, y-axis, size, color) </li>
    <li> Interaction:
        <ol>
           <li>Hover information</li>
            <li>Highlighting and selection</li>
            <li>Cross - chart interactivy </li>
            <li> Transitions</li>
            <li>Dynamic update</li>
        </ol>
    </li>
</ul>
<a name="rank"></a>
### 4. Rank chart
<img src="Source_Code\image\RankChart.png" width = 800 height = 300>

<ul>
    <li> Abstract task for chart: 
        <ol>
            <li>Performance Evaluation</li>
            <li>Comparison of Rankings</li>
        </ol>
    </li>
    <li> Structure of rank chart: Mark(Bars) & Channels (Position, length) </li>
    <li> Interaction:
        <ol>
            <li>Hover information</li>
            <li>Highlighting and selection</li>
            <li>Cross - chart interactivy </li>
            <li>Transitions</li>
            <li>Dynamic update</li>
            <li> Sorting options</li>
        </ol>
    </li>
</ul>
<a name="map"></a>
### 5. Geomap 
<img src="Source_Code\image\GeoMap.png" width = 800 height = 300>

<ul>
    <li> Abstract task for map: 
        <ol>
            <li>Provide an overview of Global Revenue </li>
            <li>Spatial Distribution</li>
            <li>Comparison Across Region</li>
        </ol>
    </li>
    <li> Structure of map: Mark(Represents an individual point or region on the map) & Channels (Visual properties like position, color, icon, circle shape) </li>
    <li> Interaction:
        <ol>
            <li>Semantic zooming</li>
            <li>Panning</li>
            <li>Cross - chart interactivy </li>
            <li>Tooltip</li>
        </ol>
    </li>
</ul>






