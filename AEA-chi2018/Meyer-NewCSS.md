# Fit for Purpose: Making Sense of the New CSS - Eric Meyer

## Feature queries

```
@supports (property: value) {css }
```

```
@supports (--css: variables) {
 /* variable related css goes here */
 Html {
    --color1: navy;
    --color2: red;
  }
  Html.help {
    --color1: teal;
    --color2: maroon
  }
  Body {color: var(--color1);}
  .highlight {color: var(--color2)}
}
```

Make sure you are testing a valid feature (include any variables that are needed).

Slide 13 - two ways to write the same thing (nest or 'and')

## Media Query inside @support vs @support inside Media Query
### Media Outside Supports Statement (MOSS)
### Media Inside Supports Object (MISO)

Slide 22 for recommendations on which one to use.

Stick to one method (MOSS or MISO) and stick with it when working on a team. Be consistent.

## Flexbox

Slide 34\-39

```
.parent {
Display: flexbox
}
.child {
Margin-left: auto; /* when you want the nav pushed right with space between the logo & nav. This will wrap the nav items. */
Margin-top: auto; /* pushing the content to the bottom */
}
```

CSS Grid: layout level

CSS Flexbox: component level

DON'T DO: slides 44\-47

__Do Do__: (not yet, still in CSS Working Group) with feature queries with subgrid  (slide 48)

### Naming Grid areas

For media queries just change the grid-template-area layout with grid area names.