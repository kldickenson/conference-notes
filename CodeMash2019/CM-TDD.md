# Testing Like You've Never Tested Before (because you haven't)
## Steve Grunwell @stevegrunwell

Stevegrunwell.com/slides/intro-to-testing

* Unit
* Integration
* End-to-end (E2E)

Arrange - act - assert

System under test (SUT)

The system we're currently testing:
* A single method (unit)
* A class (integration)
* A whole feature (integration)

For PHP: phpunit.de

Structure
Test Suite - collection of test classes
Test Class (class) collection of test cases
Test Case (method)

### Test Method
Naming convention: testWhatTheUnitDoes

### Test Doubles
* Stub: set the response values
* Mock: replace an object with one that verifies expectations
* Spy: similar to a mock, but tracks wheat has happened
* Dummy: does nothing but satisfy requirements
* Fake: implementation of the contract for testing only

Mockery - popular library for creating text doubles

Behat(gherkin) - describes behavior in plain language, good for integration testing (not unit)

### Assertions
* Equal (==) or same (===)
* Verify content (contains, regex)
* Search for truth
* test for errors
* testing output to the screen

## Basic TDD
_Basic workflow_: write a failing test -> write the minimum code to pass -> refactor, rinse & repeat. (Red Green Refactor)

_Regression tests_: write test to recreate bug

## Code Coverage (usually created during CI)
* What's NOT touch by test?
* No test => higher risk
* Target coverage? (100% is artificially inflated)

WordPress unit testing is BS