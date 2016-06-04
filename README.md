Cross-platform tests for [Magery][magery] templates.

To test, load `base/valid/*/template.html` and render with
`base/valid/*/data.json`, checking the result against
`base/valid/*/expected.html`.

**Whitespace:** try to match the whitespace in the `expected.html`
files. In general, any line in a template which includes only
whitespace and Magery block tags should be removed from the output.


[magery]: https://github.com/caolan/magery
