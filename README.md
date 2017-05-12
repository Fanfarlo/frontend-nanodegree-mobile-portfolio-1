## Website Performance Optimization portfolio project
This a project for optimize this online portfolio for speed! In particular, optimize the critical rendering path and make this page render as quickly as possible by applying the techniques you've picked up in the [Critical Rendering Path course](https://www.udacity.com/course/ud884).

### Getting started
Download this repository [here](https://github.com/Fanfarlo/mobile_portfolio/archive/master.zip).

####Part 1: Optimize PageSpeed Insights score
* Open index.html
* Apply all the techniques you know for optimizations.
* Check your index.html in [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/?hl=es).
* index.html achieves a PageSpeed score of at least 90 for Mobile and Desktop.

####Part 2: Optimize 60 Frames per Second for pizza.html
* Open views/pizza.html
* Apply all the techniques you know for optimizations.
* Check your views/pizza.html performance in the timeline.
* views/pizza.html render with a consistent frame-rate at 60fps when scrolling.
* Time to resize pizzas is less than 5 ms using the pizza size slider on the views/pizza.html page.

### My Optimizations
* Adjusted the layout for any viewport device.
* Inlined CSS and JS.
* Async Attribute for JS files.
* Media attribute for CSS.
* JS minification.
* Compressed images.
* Added HTTP caching.
* Reduced the time to resize pizzas less than 5 ms.
* Solved FSN in \views\js.main
