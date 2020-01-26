## Vocabulary
* Unit testing
* assertion
* unittest
* nose
* test coverage
* test suite
* test

## Topics
* Unit Testing
* Test Driven Development
* PyPI/pip/that whole ecosystem
* setting up test files/structuring directories/etc.
* importing files in python
* test suites are made of tests, which are made of assertions
* using a function decorator to skip tests
reason:
```python
@pytest.mark.skip(reason="no way of currently testing this")
def test_the_unknown():
    ...
```

## PyTest
* Grouping tests into classes
* `approx`, the floating point problem in computing
* `raises`, and exceptions
* As soon as the first assertion fails, the test exits.

## Outcomes
* Rely on official pytest documentation ()
* Define unit testing, test driven development, and other key terms
* One guided practice setting up a testing environment
* Multiple at-bats on simple tests
* One code challenge problem when you'd have to write tests first
