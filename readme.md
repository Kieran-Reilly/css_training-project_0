## Introduction
This is a simple css only exercise where we style a single div.

```html
<div class="simple">Hello World</div>
```

There are three states we are styling for

1. Default - no mouse interactions
1. Hover - mouse is over the div
1. Mouse down (active) - mouse button is down

On each state it looks a bit different so the project details will explain what is required for each state.

## Project details

1. Declare a css variable called size that you will use for the width and height.
1. All values changes should take 0.5 seconds and use the ease function. See `transition` for details.

### Default state

1. background: cornflowerblue
1. color: white
1. width and height is equal to size variable
1. border radius: 10px;
1. font size: 2rem
1. cursor: pointer
1. display text in the center of the div
1. center the div in a fixed position on the screen. Keep the size in mind so that you can calculate position using calc.
1. disable user text selection ability on the div so that you can't select text in the div as per normal (user-select).

### Hover

1. background: #e91e63
1. make the div from a round rect into a circle using border-radius 

### Active

1. set the font size to 1.5rem
1. background: green
1. set the box shadow to be inside using 10px blur and 5px speed and color rgba(1, 1, 1, 0.61)
