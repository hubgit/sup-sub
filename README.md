# sup-sub

A custom HTML element providing vertical alignment for a pair of sup and sub elements.

# Usage

First, import the custom element:

```html
<link rel="import" href="sup-sub.html">
```

Then use the custom element within HTML, adding the `<sup>` and `<sub>` elements within the parent `<sup-sub>` element, like this:

```html
CO<sup-sub><sup>+</sup><sub>2</sub></sup-sub>
```

# Demonstration

[A very simple demonstration](http://git.macropus.org/sup-sub/demo.html)

# Compatibility

* There is no attempt to provide backwards compatibility for browsers that do not yet support [Web Components](http://webcomponents.org/) or `display: inline-flex` and `flex-direction: column`, so it only really works without polyfills in the latest version of Chrome.

