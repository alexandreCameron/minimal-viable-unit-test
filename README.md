# minimal-viable-unit-test

Example to write an unit test on a function

## Format

Tests generally have three parts:

1. `given`:

    1. importing the function to test
    2. setting the values needed to run the function
    3. defining the expected outcome of the function

2. `when`: running the function and collecting the outcome

3. `then`: checking that the outcome is consistent with the expected outcome

## Note

1. an outcome can be the result or the error raised or any other side effect
2. checking that the outcome is consistent can require to use tolerance eg:
<https://numpy.org/doc/1.23/reference/generated/numpy.testing.assert_allclose.html>
3. with [pytest](https://docs.pytest.org/en/6.2.x/assert.html), the same test can be executed with different parameters cf:
<https://docs.pytest.org/en/6.2.x/parametrize.html#pytest-mark-parametrize-parametrizing-test-functions>
