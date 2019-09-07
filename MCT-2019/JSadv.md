#Not Your Dad's JavaScript - Josh Carroll @jwcarroll

object literal return
`
const funct = () => ({
   prop: "name"
});
console.log(funct); //== returns an object
`

'this' in arrow functions is lexically bound, but does not "bind" 'this' ever.

Destructuring the Family
`const ['husband', 'wife', ...kids] = family;
family[0] = husband;
family[1] = wife;
family[2] to family[family.length-1] = kids array; `

async function with await variables

Generators - for adding pauses withing a function
'function*' with yield statements

Proxy objects for detecting object attribute changes, good for tracing and logging
`get:
set:`

Decorators (still need a transpiler)
`function decorator(constructor: Function){

}`
