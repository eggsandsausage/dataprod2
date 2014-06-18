---
title       : Indexinator 2000 Pitch
subtitle    : This presentation will blow your mind
author      : Hampus B
job         : misc
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : prettify  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : [bootstrap, quiz, shiny, interactive]           
mode        : selfcontained # {standalone, draft}
---

## What is the Indexinator 2000

The Indexinator 2000 provides unparallalled indexing capabilities on the fly and its as simple as the click of a button. Have you ever wanted to compose your own index of how the worlds countries are actually faring? Constantly frustrated with tedious measurements provided by the U.N. and other uninspired organizations? Well look no further, the Indexinator 2000 will allow you compose your own metrics and judge for yourselves. It uses Googles Visualizations so you'll be able to do cools stuff like kind of like the chart in the next slide:

--- &interactive

## Interactive Console

<!-- MotionChart generated in R 3.1.0 by googleVis 0.5.2 package -->
<!-- Wed Jun 18 17:05:17 2014 -->


<!-- jsHeader -->
<script type="text/javascript">
 
// jsData 
function gvisDataMotionChartID1e5a232e4e8c () {
var data = new google.visualization.DataTable();
var datajson =
[
 [
 "Apples",
2008,
"West",
98,
78,
20,
"2008-12-31" 
],
[
 "Apples",
2009,
"West",
111,
79,
32,
"2009-12-31" 
],
[
 "Apples",
2010,
"West",
89,
76,
13,
"2010-12-31" 
],
[
 "Oranges",
2008,
"East",
96,
81,
15,
"2008-12-31" 
],
[
 "Bananas",
2008,
"East",
85,
76,
9,
"2008-12-31" 
],
[
 "Oranges",
2009,
"East",
93,
80,
13,
"2009-12-31" 
],
[
 "Bananas",
2009,
"East",
94,
78,
16,
"2009-12-31" 
],
[
 "Oranges",
2010,
"East",
98,
91,
7,
"2010-12-31" 
],
[
 "Bananas",
2010,
"East",
81,
71,
10,
"2010-12-31" 
] 
];
data.addColumn('string','Fruit');
data.addColumn('number','Year');
data.addColumn('string','Location');
data.addColumn('number','Sales');
data.addColumn('number','Expenses');
data.addColumn('number','Profit');
data.addColumn('string','Date');
data.addRows(datajson);
return(data);
}
 
// jsDrawChart
function drawChartMotionChartID1e5a232e4e8c() {
var data = gvisDataMotionChartID1e5a232e4e8c();
var options = {};
options["width"] =    600;
options["height"] =    500;

    var chart = new google.visualization.MotionChart(
    document.getElementById('MotionChartID1e5a232e4e8c')
    );
    chart.draw(data,options);
    

}
  
 
// jsDisplayChart
(function() {
var pkgs = window.__gvisPackages = window.__gvisPackages || [];
var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
var chartid = "motionchart";
  
// Manually see if chartid is in pkgs (not all browsers support Array.indexOf)
var i, newPackage = true;
for (i = 0; newPackage && i < pkgs.length; i++) {
if (pkgs[i] === chartid)
newPackage = false;
}
if (newPackage)
  pkgs.push(chartid);
  
// Add the drawChart function to the global list of callbacks
callbacks.push(drawChartMotionChartID1e5a232e4e8c);
})();
function displayChartMotionChartID1e5a232e4e8c() {
  var pkgs = window.__gvisPackages = window.__gvisPackages || [];
  var callbacks = window.__gvisCallbacks = window.__gvisCallbacks || [];
  window.clearTimeout(window.__gvisLoad);
  // The timeout is set to 100 because otherwise the container div we are
  // targeting might not be part of the document yet
  window.__gvisLoad = setTimeout(function() {
  var pkgCount = pkgs.length;
  google.load("visualization", "1", { packages:pkgs, callback: function() {
  if (pkgCount != pkgs.length) {
  // Race condition where another setTimeout call snuck in after us; if
  // that call added a package, we must not shift its callback
  return;
}
while (callbacks.length > 0)
callbacks.shift()();
} });
}, 100);
}
 
// jsFooter
</script>
 
<!-- jsChart -->  
<script type="text/javascript" src="https://www.google.com/jsapi?callback=displayChartMotionChartID1e5a232e4e8c"></script>
 
<!-- divChart -->
  
<div id="MotionChartID1e5a232e4e8c"
  style="width: 600px; height: 500px;">
</div>


---

## Still need more convincing?

The Indexinator has been proven (on significance levels of *.99*) to imbue the following benefits in its user:

1. You will become stronger
2. You will become faster
3. Your taxes will be severly reduced
4. You will be able to eat unlimited amounts of ice cream without getting a brain freeze.

--- &radio

## Quiz time! 

Do you want the Indexinator 2000?

1. _Yes_
2. No
3. Maybe
4. It's complicated

*** .hint
Yes, yes you do. You want it bad.

*** .explanation
I just explained it to you. It's awesome. Now go get it.

