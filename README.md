## A heatmap project

It's a heatmap of heat.

Created with D3.js.

Temperature colors were scaled with scaleQuantile so that temps were divided into 11 quantiles associated with 11 colors.
The month values in the data were processed so they'd start with an index = 0 for January. The raw data has January represented with index = 1 which makes working with it a bit trickier.

The legend uses d3.enter() to draw the scales quantiles and their colors
