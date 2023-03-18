# Nathan Scully Vale Styles

My own collection of [Vale-compatible](https://github.com/errata-ai/vale) styles. This combines publically available styles from other sources and my own custom ones. I found it easier to pick and choose from other sources than enable/disable rules pulling them all in. 


## Installation

> :exclamation: Readability requires Vale >= **2.13.0**. :exclamation:

Clone this repository directory to your `StylesPath`, and include it in your configuration file:

```ini
# This goes in a file named either `.vale.ini` or `_vale.ini`.
StylesPath = path/to/some/directory
MinAlertLevel = warning # suggestion, warning or error

# Only Markdown and .txt files; change to whatever you're using.
[*.{md,txt}]
# List of styles to load.
BasedOnStyles = ns-vale-styles
```

See [Usage](https://github.com/errata-ai/vale/#usage) for more information.



## References

<dl>
  <dt><a href="https://github.com/errata-ai/Microsoft"><code>Microsoft</code></a></dt>
  <dd>An implementation of the <a href="https://docs.microsoft.com/en-us/style-guide/welcome/"><i>Microsoft Writing Style Guide</i></a>.</dd>

  <dt><a href="https://github.com/errata-ai/Google"><code>Google</code></a></dt>
  <dd>An implementation of the <a href="https://developers.google.com/style/"><i>Google Developer Documentation Style Guide</i></a>.</dd>

  <dt><a href="https://github.com/errata-ai/write-good"><code>write-good</code></a></dt>
  <dd>An implementation of the guidelines enforced by the <a href="https://github.com/btford/write-good"><code>write-good</code></a> linter.</dd>

  <dt><a href="https://github.com/errata-ai/proselint"><code>proselint</code></a></dt>
  <dd>An implementation of the guidelines enforced by the <a href="https://github.com/amperser/proselint/"><code>proselint</code></a> linter.</dd>

  <dt><a href="https://github.com/errata-ai/Joblint"><code>Joblint</code></a></dt>
  <dd>An implementation of the guidelines enforced by the <a href="https://github.com/rowanmanning/joblint"><code>Joblint</code></a> linter.</dd>

  <dt><a href="https://github.com/errata-ai/alex"><code>alex</code></a></dt>
  <dd>An implementation of the guidelines enforced by the <a href="https://github.com/get-alex/alex"><code>alex</code></a> linter.</dd>

  <dt><a href="https://github.com/errata-ai/readability"><code>Readability</code></a></dt>
  <dd>An implementations of many popular "readability" metrics.</dd>
</dl>

