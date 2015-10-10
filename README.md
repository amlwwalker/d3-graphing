# VisuaLearn

* I wanted an easy way to drop CSV or JSON files and immediately be able to graph them using d3 (so I could get SVG images)
* Libraries already existed to draw the graphics like [metricsgraphics](http://metricsgraphicsjs.org/) and [function-plot](http://maurizzzio.github.io/function-plot/), so I just built a simple interface to be able to use the graphs these libraries provided.
* The left most (ace) text area can have `.csv` and `.json` files dropped onto it. `.csv` will be converted to `json` on dropping. 
* The central area is where the code to configure the graph is loaded. On choosing a graph type a sample code snippet will be loaded in. 
* Any of the features of metricsgraphics or function-plot can be used here, however not mixed together.
On the right the graph will be drawn and the SVG can be downloaded


### Future

* Implement downloading as PNG
* Fix title above graph/chart/SVG