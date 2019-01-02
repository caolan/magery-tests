Server-side rendering tests for [Magery][magery] templates.

For each test in `components`, load `*/template.html` and render the
'app-main' component using `*/data.json` as the context data. Check
the result against `*/expected.html`.

In certain occasion, the case is an error case. Implementation of Magery should
produce an error message (in the normal way) for this cases. The test suite provide
a proposition of error message, it is not required to match the exact message.

When using these tests as a guide for your own implementation I
suggest setting your test runner to execute the tests in order (they
generally go from simple to complex) and exit on first error.

[magery]: https://github.com/caolan/magery
