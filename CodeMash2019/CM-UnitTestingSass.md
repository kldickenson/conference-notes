# Unit Testing in Sass
## Lindsey of Sparkbox @stananick

Github/lindseywild/sass-unit-testing-presentation

When and what type of projects

Visual regression testing tools - PhantomCSS

## Why & When?

_Benefits_
* Alleviate some manual UI regression testing
* Ensure out put from mixins/functions is as expected (especially 3rd party)
* Double check important updates, such as changing the main color
* CSS could still compile without errors
* Shipping less errors

_When_
* You're working on a large project with numerous Sass files/partials
* A component exists in many places with many context
* Your project includes 3rd part  functions/mixins
* Complex functions/mixins
* Styles are very important and if they change, it could break

_Not Use_
* Small projects
* Static content websites
* Your project doesn't heavily rely on a consistent UI

## What

* Functions (especially calculations or that take parameters)
* Mixins
* Any important output
* Variables? Probably overkill

True: Sass unit testing (Miriam Suzanne at Oddbird!)
Set up with a JS testing library such as Jasmine or Mocha (Jest?)

Npm install sass-true -save-dev

./spec/true-sass-test/tests.scss
./spec/true-sass-test.js

Slides in GitHub link above

Test Driven Development
* Write unit tests before you write your code
    * Write the minimum code to pass the test
    * Test, refactor,repeat
* Organize throughs about functionality
* Find additional feature to include
* Test are already written!
* Write less code.

Write behavior to test