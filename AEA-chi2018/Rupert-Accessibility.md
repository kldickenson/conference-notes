# The Four Divine Beasts of Accessibility - Dave Rupert

[The A11y Project](//a11yproject.com)

## Evolving Expectations

Evolving requirements

[Nutrition Cards for Accessible Components](https://davatron5000.github.io/a11y-nutrition-cards/)

## Popups (slides 24card 27html 28js)

Add aria-controls

## Tooltips (slides 31card 32html 33js)

## Tabs (slides 36card 38html 39js)

Add the aria attributes via JS in case the JS does not trigger (then the aria attributes specific for tabs will not be included). When the JS does not trigger the user will get the UL as a list.

## Accordion (slides 43card 45html 46js)

## Up and coming HTML
* ``` <details><summary></summary>content</details> ``` (good except for IE and Edge, slide 60)
* ``` <button>Open Dialog</button><dialog>Dialog content</dialog> ``` (esc to close, far from ready, Chrome only, slide  54, replacement from modals!)
* ``` :focus-visible { slide 58 } ``` (keyboard focus only, only in FireFox right now)
* ``` @inert { slide 61 } ``` (used to hide the hamburger menu! Not in any browsers yet)
