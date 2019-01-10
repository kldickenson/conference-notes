# Be an A11y with React

## Nathan Loding at OST in Grand Rapids @NathanLoding

_P_ Perceivable
_O_ Operable
_U_ Understandable
_R_ Robust

In JSX, "aria-xxx" and "date-xxx" work, no need to camelCase

EsLint-plugin-jsx-a11y- npm
https://www.npmjs.com/package/eslint-plugin-jsx-a11y

React.fragment

Remember the title tag, problem in single page apps.
```js
ComponentDidMount() {document.title = ''};
```
React-Helmet

Keyboard events - onClick() not effective, need to add "onKeyPress={ function }"

## Focus 
No browser refresh in single-page-app
Manage focus state manually with JS

Same issue with Modals.

React "ref" or "createRef"

Reach Router - Router manages the focus of your app on route

https://reach.tech/router

https://medium.com/@jordan.eckowitz/reach-router-react-routing-made-easy-aac7b46cd53c

## Live Announcements

When an asych app fetches new data, screen readers aren't notified of the new data, ```html aria-live="polite/" ```

React-Aria-Live npm

* WAVE
* Google Lighthouse (based on Axe)
* TENON.io (paid service)
* Pa11y
* Deque Axe (npm client)


