TODO

5 D3 examples:

 * review the original example code
 * separate insert, update and delete
 * use a model
 * make the visualization react to the model
 * add user interface elements to control

Table of Contents:

 * What is D3?
 * What is Backbone?
 * What is a Bar Chart?
 * Separating insert, update and delete
 * Introducing a visualization model
 * Models in Backbone
 * Models in Angular
 * Models in Ember
 * Functional Reactive Programming
   * Data Flow Systems
   * [Unix Pipes](http://en.wikipedia.org/wiki/Pipeline_(Unix))
   * Functional Reactive Animation
   * [Iteratee](http://en.wikipedia.org/wiki/Iteratee)
   * Bacon.js
   * Reactive.js
   * [Reactive Bacon](https://github.com/raimohanska/reactive-bacon)
   * [Reactive Bacon](https://github.com/raimohanska/reactive-bacon)
 * Dependency Injection
   * Require.js
   * Angular.js
 * Functional Reactive Visualization Models
 * Using Backbone with Reactive.js

Original examples:

 * [Bar Chart](http://bl.ocks.org/mbostock/3885304)
 * [Line Chart](http://bl.ocks.org/mbostock/3883245)
 * [Scatter Plot](http://bl.ocks.org/mbostock/3887118)
 * [Choropleth Map](http://bl.ocks.org/mbostock/4060606)
 * [Streamgraph](http://bl.ocks.org/mbostock/4060954)
 * [Node Link Tree)(http://bl.ocks.org/mbostock/4063550)

## Examples

 * Illustrate D3 example generalization in small increments
 * Check out the [example viewer](http://curran.github.io/screencasts/generalizingD3/exampleViewer).

Listing of all examples:

 * [Example 1](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot01) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot01) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot01/index.html)) - Original D3 Bar Chart Example
 * [Example 2](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot02) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot02) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot02/index.html)) - Split into HTML, CSS and JS files
 * [Example 3](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot03) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot03) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot03/index.html)) - Implement Single Var Pattern
 * [Example 4](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot04) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot04) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot04/index.html)) - Make HTML structure explicit
 * [Example 5](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot05) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot05) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot05/index.html)) - Split bar chart and main program
 * [Example 6](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot06) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot06) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot06/index.html)) - Split up SVG and Group creation and configuration
 * [Example 7](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot07) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot07) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot07/index.html)) - Split up X axis group creation and configuration
 * [Example 8](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot08) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot08) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot08/index.html)) - Split up Y axis group creation and configuration
 * [Example 9](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot09) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot09) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot09/index.html)) - Split up enter and update for bars
 * [Example 10](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot10) - ([run it!](http://curran.github.io/screencasts/introToAngular/examples/snapshots/snapshot10) | [index.html](https://github.com/curran/screencasts/tree/gh-pages/introToAngular/examples/snapshots/snapshot10/index.html)) - Isolate hard-coded visualization size

Final Result:

 * FRD3 - Functional Reactive D3 library and examples gallery
 * Basis for integrating UDC data model and dashboard infrastructure with D3 visualizations