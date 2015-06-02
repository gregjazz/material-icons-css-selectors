# Material Icons CSS Selectors
If you haven't heard of Google's material icons font, it's definitely worth checking out: https://www.google.com/design/icons

However, if you're like me and used to the Font Awesome / Glyphicons method of displaying icons, this CSS include is for you. Rather than using the icon name (or numeric character reference for compatibility with older browsers) within the icon tag, this lets you choose the icon via CSS selector, just like how Font Awesome works. Just add the included CSS to your HTML head, like this:

```
<link href="material-icons-selectors.css" rel="stylesheet" type="text/css">
```

Of course, you'll need Google's material icons stylesheet included as well, either using them via Google Web Fonts or hosting them locally. There's [documentation on how to do that here](http://google.github.io/material-design-icons/).

Here's an example of how you'd use the material icons CSS selectors:

```
<i class="material-icons material-thumb-up"></i>
```

(of course, you could also use a span instead, if preferred...)

The selector name matches Google's icon naming, although note that you would use hyphens rather than underscores in the naming convention.

Hope you find this useful!
