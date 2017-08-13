This is a fork of https://github.com/simonh1000/elm-charts that adds a few features. Will send some patches upstream to get them included there instead in the future.


# Elm Chart library

An Elm library for creating simple horizontal and vertical bar charts, and for pie charts.

This library supports three basic chart types. The horizontal bar chart is built with simple div elements (based on an idea from [D3](https://d3js.org)); the vertical one uses a flexbox layout and some CSS transforms, while the Pie chart builds on [this post](http://www.smashingmagazine.com/2015/07/designing-simple-pie-charts-with-css/) using Svg elements.

![Pie chart](https://github.com/simonh1000/elm-charts/blob/master/pie.png?raw=true)

## Try the examples

```
cd examples
elm-reactor
```

load http://localhost:8000

## Changelog

3.3.0 - Add ability to use a custom number format function
3.2.0 - Make chart title optional instead of defaulting it as empty
3.1.0 - Add dimensions to model and use these for the line chart
