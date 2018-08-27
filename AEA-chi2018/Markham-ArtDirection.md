# Customizable Art Direction on the Web - Mina Markham

Where to start:
* semantic markup
* markup first

## @supports

```css
@supports <supports-condition> {
  <group-rule-body>
}
@supports (--foo: green) {
  body {
    color: var(--varName);
  }
}
```
[MDN @supports](https://developer.mozilla.org/en-US/docs/Web/CSS/@supports)

Localization using support
```css
&:lang(ja) {
  writing-mode: vertical-rl;
}
:focus-visible {
  outline: thin solids @secondary-color;
  outline-offset: .25rem;
}
:focus:not(:focus-visible) {
  outline:none;
}
```
[MDN :focus-visable](https://developer.mozilla.org/en-US/docs/Web/CSS/:focus-visible)