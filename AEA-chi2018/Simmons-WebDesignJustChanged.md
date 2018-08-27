# Everything You Know About Web Design Just Changed - Jen Simmons

## History of web layout

1. Pre\-1996 \- __Flow__ Layout
2. 1996 \- __Tables__ (for layout), slicing and dicing images, lack of web browser consistency (need to specify the best browser to the user)
3. 2000 \- __Flash__ (fixed window size, each item was an object placed by coordinates)
4. 2003 \- __Semantic Markup__ &amp; __Separation of Concerns__ (intro of CSS)
5. \~1999 \- __Absolute Positioning__ (layover from Flash but taking out of the flow, very short lived)
6. 2002 \- __Fluid Layouts__ using Floats (fluid columns)
7. 2004 \- __Fixed Width__ (opposing floats)
8. 2010 \- __Responsive Web Design__ (fluid images, media queries, one web, slide 64)


The 4 current methods:
* Flow (writing-mode)
* CSS Grid
* Flexbox
* Multicolumn

Slide 69 \- suggested use of each method within a page template

## Currently - Intrinsic Web Design

1. __Ways to Contract and Expand space__ 
    * wrap and reflow (flow)
    * enlarge / shrink
    * add / remove white space [white space Video](youtube.com/layoutland)
    * slide / overlap [Overlap Video](youtube.com/layoutland)
1. __Flexibility__
    1. Images
        * fixed images
        * fluid images
        * fluid vertical (vh)
        * set the height and width and __object fit__ [object fit Video](youtube.com/layoutland)
    2. Columns
        * with Grid (fixed, %, __fr__, minmax(min-content: 1fr), auto)

                growing minmax() gets space until it's max then the frs

                shrinking: frs loose their space until their min-content then minmax() starts shrinking to it's min
    3. Rows
    4. Programming Flexibility Model
1. __Viewport__
        1. Fluid
        2. Fixed
        3. Responsive
        4. Intrinsic (programing to all four edges with vertical centering, vertical viewport units (vh), and rows) [viewport playlist](youtube.com/layoutland)

The Big Web Show #176

[Labs.jensimmons.com](Labs.jensimmons.com)