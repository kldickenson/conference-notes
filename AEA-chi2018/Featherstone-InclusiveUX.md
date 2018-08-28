# Inclusive UX \- Techniques for everyone \- Derek Featherstone

Star Wars storyboard of Luke & Yoda (Luke finally figuring out Yoda's identity)

Wireframes -> storyboards

Solve issues and disagreements in the __wireframe__ stage.

Political and technical costs are much "cheaper" at the wireframe stage than at the development stage.

__Accessibility__ is an outcome.

__Inclusive design__ is a process.

Accidental accessibility happens but we want to be intentional.

## Inclusive UX design

The __intentional__ facilitation and __crafting__ of the interactions within an __ecosystem__ that incorporates inclusion as a __core value__.

## Communication

Include interaction "script" to the wireframe (annotate order)
* order notes
* focus path notes

## Reverse Engineering

How could we have solved this issue earlier i.e. fly-out submenu over content?

Remember to add detail to the wireframe i.e. video play buttons to signify type of content.

Controls need to be bigger in mobile. This could have been caught at the wireframe stage.

## Interaction tables (slide 27)

Carousel/Keyboard State - Event - Interaction - Focus Change - ARIA states

Valid targets

There's value in the reference and value in creating it together.

## Practice inclusive design

### WCAG 2.1

We don't have to do that. It's not on the checklist. (Bad excuse!)

WCAG is just a documentation of what has already been determined. You should look beyond.

\1.4.11 Non-text contrast (example: radio buttons that with little contrast)

\2.1.4 Keyboard shortcuts

\2.5.3 Label and name for inputs

Distinguish each link with labels, ARIA labels, and __context text__

## Color palettes (best: slide 42)

Include color contrast ratios

Show in the kitchen sink!

## Design intention

Slide to Confirm 
* How would a screen reader make it work (double tap, a very common interaction)
* Issue with manual dexterity, gitters (allow for larger touch area) 
* A carousel vs a list/grid (tap on a button to change from carousel to list/grid)

## CSS class names (slide 55)

```
.current aria-current="page | date | ..."
.expanded aria-expanded="true"
```

## High contrast tweaks

Beware of menu drop-down arrows. Make sure when reverse contrast is used that the arrow does not dissapear. Add a border around the arrow.

## Navigation Black Holes

Pagers: add a hidden span of total count! (Slide 69)