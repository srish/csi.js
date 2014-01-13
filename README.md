csi.js
======

client side includes via javascript

usage
======

Simply include `csi.min.js` in your `<head>` and add a `data-include` attribute on any valid HTML element. csi.js will fetch the value of that attribute, and **replace** the element with the fetched document.

If, `include-me.html` looked like this:

```
<h1>Hello, world!</h1>
```

Then, a document like this:

```
<body>
<div data-include="include-me.html"></div>
</body>
```

would end up rendering like this:

```
<body>
<h1>Hello, world!</h1>
</body>
```
