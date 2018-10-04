# oncor-workshop-notes
Notes and links for dataviz workshop, 2018-10-03

## Agenda

Section 1 (9AM - 12:30PM)

* Introductions
* Using blockbuilder.org
* HTML, CSS, & JavaScript Quickstart
* Hands-on walk-thru of D3.js

Lunch

Section 2 (1:30PM - 3:30)

* Why Visualize?
* Marks & Channels
* Interactive visualization
* Multiple views

Section 3 (3:30 - 5PM)

* Pulling it all together
* Discussion & Questions

## Developing locally
Follow these directions to install Python and start SimpleHTTPServer on Windows:
-  https://developer.mozilla.org/en-US/docs/Learn/Common_questions/set_up_a_local_testing_server

Then download your project as Alan demonstrated:
- Go to the original "gist" for your code (in the URL, replace "blockbuilder.org" with "gist.github.com"
- Click the "Download ZIP" button at the upper right

## Links

HTML basics:
- http://sta.mn/w96
- https://www.teaching-materials.org/htmlcss-1day/html-basics/slides

Blank block:
- http://sta.mn/x3fd

CSS, what is it:
- http://sta.mn/sc4
- http://girldevelopit.github.io/gdi-featured-html-css-intro/class2.html#/6

Session 1 example (part 1):
- http://blockbuilder.org/loganwilliams/a5e487d989097924d93e83393f24b6c0

Intro to JavaScript (variables and functions):
- http://sta.mn/6xw
- https://www.teaching-materials.org/javascript/slides/varsfunctions

Intro to JavaScript (objects):
- http://sta.mn/jrg
- https://www.teaching-materials.org/javascript/slides/objects

DOM manipulation:
- http://sta.mn/f8h
- https://www.teaching-materials.org/jsweb/slides/dom#/

Session 1 example (part 2):
- http://blockbuilder.org/loganwilliams/245decde7c775eac820711ad4ffc4121




Hans Rosling videos:
- BBC's Joy of Stats
  - https://www.youtube.com/watch?v=jbkSRLYSojo
  - http://sta.mn/y6r
- TED talk
  - http://www.ted.com/talks/hans_rosling_shows_the_best_stats_you_ve_ever_seen.html
  - http://sta.mn/shf

Gapminder data:
- https://gist.githubusercontent.com/almccon/e47e8bab24d66e198b1737005664df26/raw/5e7e4fbcaf986482aea142414f84b5046808977e/gapminder_avg.csv
- http://sta.mn/yww 

Data binding to divs (no svg):
- https://blockbuilder.org/almccon/541b024ff7a9b1a10fc2a5beb5657451
- http://sta.mn/jb4

Data binding to SVG:
- https://blockbuilder.org/almccon/22a00b370abcb174b345ad97cd92169d
- http://sta.mn/j9p

Using scales:
- https://blockbuilder.org/almccon/f88974c49a6a03d868aad275f46bedb5
- http://sta.mn/fg2

Adding axes:
- https://blockbuilder.org/almccon/0b6ff5e6cac67142a013255aca297312
- http://sta.mn/wcm

Now let's make a scatterplot:
- https://blockbuilder.org/almccon/ce995a988bc4f0d7f13cb1236b12a1b9
- http://sta.mn/45c

Time series data (needs a new dataset):
- https://blockbuilder.org/almccon/cc8061dff72f040f69cd02d1dcfcd70e
- http://sta.mn/wys
New data:
- https://gist.githubusercontent.com/almccon/cc8061dff72f040f69cd02d1dcfcd70e/raw/e8bc7890b6f2d97112990359fc9460ee24481dc7/gapminder_time_subset.csv
- http://sta.mn/nwk

## Afternoon demos:

Here are the interaction enhancements we added to the gapminder demo:
- https://blockbuilder.org/almccon/bb9062cb4c5b24816d35329ad3bc59e8

Here's a simple map demo that also illustrates d3 version 5:
- http://blockbuilder.org/almccon/43fc43c5e0db2d0f0656fdf6ddb6eb08

Google Public Data Explorer:
- https://www.google.com/publicdata/explore

Stamen's "American Panorama" examples of linked views:
- http://dsl.richmond.edu/panorama/forcedmigration
- http://dsl.richmond.edu/panorama/foreignborn

Brushing a line chart:
- http://blockbuilder.org/ColinEberhardt/000b1721b69868f1ce5d

Another brushing example:
- http://bl.ocks.org/syntagmatic/5441022

Libraries built on top of D3:
- D3fc: https://d3fc.io/
- DC.js: https://dc-js.github.io/dc.js/  (has a nice dashboard)
- Vega: https://vega.github.io/vega/
- Crossfilter: http://square.github.io/crossfilter/

Line chart transitions:
- Bad: https://bl.ocks.org/mbostock/1643051
- Good: https://bl.ocks.org/mbostock/1642874
- More explanation: https://bost.ocks.org/mike/path/

Force simulation:
- https://blockbuilder.org/FrissAnalytics/80d3b7e5494b4095ca52544a34167095

Force Layout:
- https://blockbuilder.org/ColinEberhardt/6ceb7ca74aabac9c8534d7120d31b382

Airports voronoi:
- https://www.jasondavies.com/maps/voronoi/airports/

Using an invisible voronoi to improve mouseover:
- https://www.visualcinnamon.com/2015/07/voronoi.html

Voronoi interaction:
- http://blockbuilder.org/HarryStevens/95cda9c3302f1f938b95c31148bd7823

D3 docs:
- https://github.com/d3/d3

API reference:
- https://github.com/d3/d3/blob/master/API.md

Adding tooltips
- Creating your own tooltips: http://bl.ocks.org/d3noob/a22c42db65eb00d4e369
- Using "d3-tip" https://github.com/Caged/d3-tip
- Using "tipsy" http://bl.ocks.org/ilyabo/1373263
