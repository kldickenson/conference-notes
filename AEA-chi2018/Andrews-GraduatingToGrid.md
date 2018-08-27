# Everything You Know About Web Design Just Changed - Jen Simmons

Understand CSS:

* Inheritance
* Specificity
* Layout
    * block (y axis) and inline (x axis) dimensions (flips when when using vertical layout)
    * row & columns

CSS Intrinsic and Extrinsic Sizing
Intrinsic (determined by content)
Extrinsic (determined by container)

__Min content__: width determined by longest word (for wrap)

__Max content__: width of full content (will cause overflow if content is wider than it's parent container)

## Flex Box

Content will default to max content unless an item of the flex container has wrapping text. In that case the default will be min content for the smaller items.

Remedy: 
```
flex: 1 1 auto;
```

For equal width columns:
```
Flex: 1 1 0;
```

__Flexbox__ is starting from max-content and taking space away.

__Grid__ starting at min-content and adding space.

```
.grid {
    Display: grid;
Grid-template-columns: repeat(4, fit-content(15ch))
}
```

```
Grid-area: content
/* shorthand for:*/
Grid-area: content / content / content / content
Grid-row-start / grid-column-start / grid-row-end / grid-column-end
```

You should still use __float__ if you want text wrap.

__Flex__ for justify-content (space-between)

__Grid__ for specific placement 


### Working with less capable browsers

For other desktop browsers supporting the __last 2 versions__ is common.

Subgrid (child using the parent grid for the "lines")
Not yet, but on the way.

No support: mainly mobile browsers

__Lack of support especially in countries where hardware is less powerful and data is expensive.__

Using Grid rather than loading a big framework can help create a better experience even for browsers that don't support Grid. (Example: UC mobile browser in India)

