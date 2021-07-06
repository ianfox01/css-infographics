# css-infographics
Accessible, responsive, CSS infographics.


## Structure
Infographics use CSS grid and flexbox properties.

Class|Fuction|Required
--|--|--
`.grid-container`|Sets global grid values. Every infographic section must be wrapped in a container.|Yes
`.half`| Sets grid to 50% / 50%|No
`.thirds`| Sets grid to 33% / 33% / 33%|No
`.quarters`| Sets grid to 25% / 25% / 25% / 25%|No
`.fifths`| Sets grid to 40% / 60%|No


## Content
- Pie charts use the class `.pie` and apply a single-stop conic gradient to the same value as the chart's content. Use to illustrate single data point.
- Donut charts use the class `.pie` and .donut, and apply mulitiple-stop conic gradient. Use to illustrate up to four data points that add up to 100%.
- Bar charts are standard HTML tables formatted with CSS `grid`, with the class `.single-bar-chart` or `.double-bar-chart` applied. CSS `var()`s define the value for each bar and the overall scale of the chart. CSS `calc()` converts these values to a percentage and renders the bar length accordingly.
- Icons are Font Awesome 5.

## Utilities
Class|Fuction|Applies to
--|--|--
`.card`|Wraps a parent or child in a bordered container with a drop shadow.|Grid containers, data blocks
`.dark`|Changes an infographic to gold-on-black.|Pie charts, data blocks
`.gold`|Changes an infographic to black-on-gold.|Pie charts, data blocks
`.stripe`|Adds striped background to component.|Data blocks where `.gold` or `.dark` are applied.
`.reverse`|Reverses order of elements from top-to-bottom to bottom-to-top.|Data blocks
`.responsive-fit`|Overrides a grid container's layout to stack children in a single column at the 720 breakpoint instead of 500.|Grid containers
