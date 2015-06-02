# material-icons-css-selectors
CSS selectors for Google's material icons font

If you haven't heard of Google's material icons font, it's definitely worth checking out: https://www.google.com/design/icons

However, if you're like me and used to the Font Awesome / Glyphicons method of displaying icons, this CSS include is for you. Rather than using the icon name (or numeric character reference for compatibility with older browsers) within the icon tag, this lets you choose the icon via CSS selector, just like how Font Awesome works.

Here's an example of how you'd use it:

```
<i class="material-icons material-thumb-up"></i>
```

(of course, you could also use a span instead, if preferred...)

The selector name matches Google's icon naming, although note that they use hyphens rather than underscores in their naming convention.

Hope you find this useful!
