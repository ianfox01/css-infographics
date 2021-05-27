# css-infographics
Accessible, responsive, CSS infographics.


## Structure
- Infographics use CSS grid and flexbox properties.
- The `.grid-container` sets global grid values. Every infographic section must be wrapped in a container. This class is REQUIRED.
- Desktop gridsset to `.thirds` (33%/33%/33%) or `.fifths` (40%/60%). This class is REQUIRED.

## Content
- Pie charts use the class .pie and apply a single-stop conic gradient to the same value as the chart's content.
- Icons are Font Awesome 5.

## Utilities
- `.card` can added optionally to any parent or child container to add a border and drop shadow and give the item a card-like effect.
- `.dark` can be aplied to an icon to change it from black-on-gold to gold-on-black.
- `.reverse` moves labels from the top of an item to the bottom.
